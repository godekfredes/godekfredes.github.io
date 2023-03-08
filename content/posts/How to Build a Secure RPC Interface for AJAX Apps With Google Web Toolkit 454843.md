---
title: "You won't believe how easy it is to create a bulletproof RPC interface for your Ajax apps using Google Web Toolkit!"
ShowToc: true 
date: "2022-12-03"
author: "Matthew Pierson"
---
*****
Title: You Won't Believe How Easy It Is to Create a Bulletproof RPC Interface for Your Ajax Apps Using Google Web Toolkit!

Introduction:
Ajax is a powerful web development technique that allows developers to build web applications that provide a seamless user experience. However, building a robust RPC (Remote Procedure Call) interface for Ajax applications is not always easy. Developers need to ensure that the RPC interface is secure, efficient, and reliable. In this article, we will show you how to create a bulletproof RPC interface for your Ajax apps using Google Web Toolkit (GWT).

What is Google Web Toolkit?
Google Web Toolkit (GWT) is an open-source web framework that allows developers to build complex web applications using Java. GWT is designed to simplify the development of complex Ajax applications by providing a set of tools and libraries that make it easy to create rich, interactive web applications.

Creating a Bulletproof RPC Interface Using GWT:
GWT provides a powerful RPC framework that allows developers to create a robust and secure interface for their Ajax apps. Here's how to do it:

Step 1: Define Your Service Interfaces
The first step in creating a bulletproof RPC interface using GWT is to define your service interfaces. A service interface defines the methods that your Ajax application will call on the server. To define your service interfaces, create a new Java interface and annotate it with the "@RemoteServiceRelativePath" annotation.

Step 2: Create Your Service Implementation
Once you have defined your service interfaces, you need to create your service implementation. This implementation will be responsible for handling the requests and responses from your Ajax application. To create your service implementation, create a new Java class and extend the "RemoteServiceServlet" class.

Step 3: Configure Your Web.xml File
The next step is to configure your web.xml file. This file tells your web server how to map URLs to servlets. To configure your web.xml file, add a new servlet mapping for your service implementation.

Step 4: Use Your Service in Your Ajax Application
Finally, you are ready to use your service in your Ajax application. To use your service, first, create a new instance of your service interface using the "GWT.create()" method. Then, you can call the methods on your service interface using the callback mechanism provided by GWT.

Conclusion:
As you can see, creating a bulletproof RPC interface for your Ajax apps using GWT is not only easy but also efficient and reliable. By following the steps outlined in this article, you can build robust and secure Ajax applications that provide a seamless user experience. So why wait? Start building your bulletproof RPC interface using GWT today!

{{< youtube VOf27ez_Hvg >}} 



These are some of the advantages that I believe makes GWT a good choice for building a web application:

 

GWT is freely available from Google and there is a large developer community for it.
GWT apps are coded entirely in Java and there is no need to understand JavaScript unless you want to add very specialized customization. The Java source is compiled into JavaScript optimized for each possible client browser, so you can take advantage of all browsers equally with a single set of source code.
GWT apps are well supported across most browsers.
All of the development tools needed are available for free, including Eclipse as an IDE and plenty of plugins to enhance it.
Numerous third party toolkits that provide additional widgets, functionality, and support.
GWT utilizes a sophisticated and powerful, yet simple-to-use, Remote Proceedure Call (RPC) mechanism to provide AJAX-style communication between the client and server. 



The last bullet is a key feature of GWT that makes building AJAX functionality quite simple. But if the RPC interface you build is not designed correctly, you could be opening up the server-side of your application to vulnerability. The rest of this article will cover some design principles that should be considered if you want to be sure that the communication between the client and server is secure.

 
### A fictional web application example 


First I’ll be providing a brief overview of how to build a GWT RPC interface.
It is important to note that this article is not meant to be a guide on how to build a GWT RPC interface. The point of this article is to explain how to design your interface in a secure way once you are already familiar with the implementation details. Please refer to the GWT RPC documentation for details on how to build, use, and deploy an interface if you are not already familiar with it.
  The infrastructure that GWT RPC provides gives you the ability to have your server offer Java functions that can be called from the client as if making a regular Java function call, with the only caveat being that all function returns are done asynchronously and never synchronously. You can pass entire objects as input parameters and as return parameters — GWT RPC will take care of the marshalling of these complex data types for you.
 Apache Tomcat is typcially used to host the servlet or servlets that provide the server-side code for the RPC interface. The client code is JaveScript, compiled from the Java source by the GWT compiler, running in the browser.
  Our web application  example will be access to a list of contacts that can be viewed or edited. On the server we will have a database that stores the contacts. The client UI will give the end user the ability to view the current set of contacts, add, edit, or delete contacts from the list, and send an email to anyone on the contact list. To further illustrate security principles in the design of the RPC interface for this app, end users will need to log in and certain users will have access to only certain subsets of the entire list of contacts.
  The RPC service will be called ContactsService and the service interface would be defined in ContactsService.java like this:
 The service async interface would then be defined in ContactsServiceAsync.java like this:
 So in the client code, when you need to call a function in the RPC interface, the client would invoke it like this:

 
### Remember what is on the client and what is on the server


The reason for having an RPC interface is so that you can implement your web application in a way that utilizes code running both in the client browser and on the server. Code running on the server would typically be used to read and write a database or to invoke functionality that cannot be done from a sandboxed web browser, i.e., sending an email or connecting to servers other than the server that served up the client code (most browsers will block this to prevent cross-site scripting attacks).
So in general: code running on the client provides the user interface and direct interaction with the user, and code running on the server provides the actual data manipulation that the client code is driving. For this reason, the server is the side you need to guard carefully.
  Code that executes on the client should not be responsible for security in any way. Client code is served up to the end user and once given to them they have the ability to potentially modify it in any way. There are plenty of browser plugins that allow access to and modification of code served for a web application. And the end user may not even be using a standard browser. HTTP is an open protocol and therefore anyone who has access permission (as administered on the web server) to your web application has the ability to get your application’s code.
  You may think that using an obfuscator on your web application’s client code would make the client code secure from end-user tampering but most obfuscators are able to be foiled – although at this point you have raised the bar a little bit higher.
  But note that the server-side of your RPC service is still open to be called even by someone who has access to your web application but may not be able to access in any usable way the client code meant to invoke that interface.
 The functions on your server are callable by anyone that has access to your web application
  A very important point to be made here (and the crux of this article) is that all of the function calls hosted on your server can be called by anyone that has access to your web application regardless of whatever you put in your client code.  As illustrated in the above section you cannot rely on your client code to guard what can be done through your RPC interface.
  You need to design your RPC interface in a way that only authorized end users can do what you have authorized them to do. 

 
### Use the session to track the end user


The server used to host your RPC interface keeps track of all client sessions with the server. Once a browser instance requests anything from the server, the server will track that particular browser instance and any subsequent request from the same browser instance – even from a different tab or window, they will be tracked as being in the same session. The session will be remembered even if the network connection between client and server is severed for some time period.
The session is tracked on the server with the HttpSession object. In your server code, this can be accessed from the HttpServletRequest object which is available in any RPC function implementation. Note that the RPC implementation class extends RemoteServiceServlet which extends HttpServlet. [The HttpServlet class is a powerful class that provides access to everything about the connection between the client and the server. The javadoc for HttpServlet is a valuable reference.] All of the functions available in HttpServlet are therefore available within the implementation of any of your RPC functions.
The following code gives an example of how to use the session to track if the user is considered by your server implementation to be logged in or not:
   For simplicity the code example uses the username to track the currently logged in user. But you probably want to use something like the database ID of the login entry that is likely to be more persistent over time.
  Note that the session attributes appear to work like a cookie. But setting a session attribute is much different than using a cookie. Cookies are tracked on the client side by the browser. The end user has full access to the store of cookies and can easily tamper with them. Session attributes are stored only on the server and the client has no way of accessing them. If you choose to store any state about the server locally on the client, make sure that it is only in addition to and not instead of storing the same state on the server.
  The bottom line is that the server alone should hold the authoritative state of the ability to access any element of the server. If the client wants to ask if a particular user is currently logged in, it should ask the server via an RPC call — and that RPC function should verify that the caller has the right to ask the question before returning an answer.

 
### Check access rights on every RPC call


  Remember that a malicious attacker will not respect your idea of which RPC functions to call in which order. They can potentially call any function in any order and pass in any data of the types that the functions accept as parameters.
  Every single function in your RPC interface must verify that the current session is authorized to get back any information the function may return (e.g. any of the contacts in the list of contacts) or is authorized to carry out any activity the function may do (e.g. send an email, modify the database, etc.).
  Building on our example, every RPC function must at the very least check to see if the current session is logged in before continuing to carry out the function. And it should additionally verify that the currently logged in user has permissions to carry out the function. For example, when querying the list of contacts, certain users should only see a subset of the list of all contacts. Your database design should contain the information used to track who has access to what.
  The function getContacts() will do nothing if the current session is not logged in and if a user is properly logged in, it will filter out to only the Contacts that the current user has the rights to view:

 
## Summary


This method is one of the safest I know for building an RPC interface. However, there are other methods and you may find another scheme that works better for your particular situation, especially depending on the level of security you need for your server.
I would love to hear from folks if they have different methods that have worked well for them in the comments below.

 
### Useful Links
 

GWT Home Page — The top level of all information Google provides on GWT
GWT Developer’s Guide — The best place to get started with GWT
GWT Server Communication — How to create an RPC interface

HttpServlet





