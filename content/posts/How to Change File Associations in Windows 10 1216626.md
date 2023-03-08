---
title: "Unlock hidden Windows secret: change file associations in seconds and revolutionize your computer experience!"
ShowToc: true 
date: "2023-06-11"
author: "Rachael Larkins"
---
*****
Unlock Hidden Windows Secret: Change File Associations in Seconds and Revolutionize Your Computer Experience!

Are you tired of constantly struggling with file associations on your Windows PC? Do you find it frustrating when your files open with the wrong program, or you have to manually find and select the right program every time you want to open a particular file? Fear not, for there is a hidden Windows secret that can revolutionize your computer experience in seconds – the ability to change file associations with a few simple clicks.

Firstly, what are file associations? Simply put, the file association determines which program is used to open a file type. For example, if you double-click on a .txt file, your computer will automatically open it in a text editor program such as Notepad. However, if you have Microsoft Word installed, you may prefer to have .txt files open in Word instead.

Changing file associations in Windows is incredibly simple, yet many users are not aware of this powerful feature. Here’s how to do it:

1. Right-click on the file in question and select ‘Open with…’

2. Click on ‘Choose another app’

3. Select the program you want to use to open the file in the future, or click on ‘More apps’ to see a full list of your programs

4. If you want to always use this program to open files of this type, tick the box that says ‘Always use this app to open .[file extension] files’

5. Click ‘OK’ to save your changes

That’s it – you can now enjoy seamless, hassle-free file opening on your Windows PC. No longer will you have to manually browse for the correct program or endure frustrating error messages when your files don’t open as intended.

But why stop there? Changing file associations can revolutionize your computer experience in countless ways. For example, you may have multiple image editing programs installed on your PC, but only use one of them regularly. By changing the file association for your image files, you can ensure that they always open in your preferred editor, saving time and increasing efficiency.

Similarly, if you often work with a specific file type in your job or hobbies, you can set the file association to your preferred program so that your computer always defaults to that program when you double-click the file. This can be a huge time-saver and help you stay focused on your work, rather than spending time searching for the right program to use.

In conclusion, changing file associations is a simple yet highly effective way to revolutionize your computer experience on Windows. By taking a few seconds to set your desired program for each file type, you can enjoy seamless, error-free file opening and increased efficiency when working with your favorite programs. So what are you waiting for? Unlock the hidden Windows secret of file associations today and transform your PC experience!

{{< youtube c7o2eevdxeE >}} 



In Summary


File association is the process of associating file types with their compatible apps on your PC to save you the hassle of manually selecting a program for a file every time you want to open it.
While the default file associations work pretty well, there are times when you might want to replace them with third-party programs.
All file associations on Windows 10 are stored as sets of verbs in the Windows Registry, and you can change these associations as described in the guide below.







While the default file associations work pretty well, there are times when you might want to replace them with third-party programs.
In this guide, we’ll take a closer look at Windows files associations and share the different methods you can use to change files associations in Windows 10.

 
## What is Windows File Association?


File association is an essential component of an operating system that associates different kinds of files supported on your system with compatible applications, so you don’t have to manually select the right program for a file every time you want to open it.
All major operating systems—Linux, macOS, and Windows—have their way of implementing file type associations. Talking about Windows, in particular, the operating system uses the “open” verb to invoke the associated program for a file type and present it to the user to perform an edit or some other action.
All file associations on Windows 10 are stored as sets of verbs in the Windows Registry, and you can change these associations based on your preferences.

 
## Determining File Associations of a File Type


Before you jump in and start changing the default program on your system, you first need to determine the current association for the file type whose default application you want to change.
To determine file associations of a file type, open File Explorer and navigate to the folder that contains files of the file type you want to modify.
For example, if you want to find out the default file association for the .txt file type, go to a folder that contains text (.txt) files.
Next, right-click on a file and select Properties from the menu. In the Properties window, check the values against the Type of file and Opens with fields. Type of file, as its name suggests, tells you the file type and its extension. In our example, it’s Text Document.

On the other hand, Opens with identifies the current program or application assigned to open the selected file. In our case, this is Notepad.

 
## How to Change File Associations in Windows 10


Microsoft offers three ways to change file type associations in Windows 10, each with its own advantages and scope of use.

 
### 1. Changing File Associations Using Open With


If you’ve been a Windows user for some time, you’re probably already aware of the Open With method: it’s the easiest way to change file associations on Windows.
Follow the steps below to change the default file association using Open With:

 

Go to the folder holding the file(s) whose association you wish to change.
Right-click on a file, hover over Open With, and select Choose another app.

In the How do you want to open this file window, select an application from the list.
Tick the checkbox next to Always use this app to open .ext files, where .ext is the extension of the file you’ve selected.
Eg: .txt for text files, .jpg and .png for image files.

Hit OK.



If, for some reason, you don’t see your desired program on the list, scroll down and select Look for another app on this PC. Then, use File Explorer to navigate to the installation path of the program you want to use, select it, and hit OK.


 
### 2. Changing File Associations Using Settings


Windows 10 Settings offers a more granular way of managing file associations on your PC. It presents you with all the different file types in use so you can change their default programs with ease. Moreover, you also get the ability to change the default apps for email, music, maps, and web browsing, among others.
For changing file associations from Settings, use the following steps:

 

Hit the Windows + I key shortcut to open the Settings. Here, go to Apps > Default apps.
Scroll down and select Choose default apps by file type.

From the list of file associations, tap on the application corresponding to the extension of the file type you want to modify.

Click on a program in the list that you want to use to open this file type.



With this method, you can also choose the Choose default apps by protocol and Set defaults by app options in step 2. While the former allows you to choose the default program for actions or links, the latter lets you manage an entire program (associated file types and protocols).

 
### 3. Changing File Associations Using Command Prompt


Even though both the methods we’ve listed so far do the job, if you want a quick and efficient way of changing file associations on your computer, you should consider using the Command Prompt.
To use Command Prompt for changing file associations, follow these steps:

 

Press Windows + X shortcut to bring up the Power Users Menu and select Command Prompt (Admin) from the menu. [Click Yes in the User Account Control window.]
In the CMD window, type assoc followed by the file extension whose default program you want to determine and hit Enter.For example, to know the default association for .txt files, run:
assoc .txt
Run your command in the following syntax to change file associations:
assoc file_extension="path_to_program"

For example, to set Notepad as the default program for .txt files, run:
assoc .txt="C:\Program Files\Windows\System32\notepad.exe"
Finally, verify the changes using the syntax below:
assoc file_extension

Eg:
assoc .txt



If the output returns Notepad or the application name you set for that file type, you’ve successfully changed its file association. In case it doesn’t, perform the steps again.

 
## Resetting File Associations in Windows 10


If you’ve misconfigured file associations, you can reset them to change their file associations back to the default apps. Follow the steps below to reset app defaults in Windows 10.

 

Hit the Windows + I shortcut to open Settings.
Select Apps and choose Default apps from the left-hand menu.
Scroll down to the bottom and hit the Reset button below Reset to the Microsoft recommended defaults.


 
## Successfully Changing Windows 10 File Associations


Using this guide, you can easily change file associations for different files types on your Windows 10 PC and run them using your preferred third-party programs.
Although all three methods we’ve mentioned above will get your job done, the second method offers a more comprehensive approach for changing file associations than the other two methods. Additionally, since it presents you the entire list of different file types and their associated default applications, you get to manage pretty much all file extensions with ease in one place.
It’s important to note that file type associations tend to reset back to their defaults upon software update, so you may have to go over the entire process again. Alternatively, you can take a backup of your file associations and restore it after updating your system to save the hassle.

 
### 1. How do I view file associations in Windows 10?


To view file associations in Windows 10, open File Explorer and navigate to the folder that contains files of the file type you want to modify. Next, right-click on a file and select Properties from the menu. In the Properties window, check the values against the Type of file and Opens with fields.
Alternatively, go to Settings (Windows + I) > Apps > Default apps. Here, tap on Choose default apps by file type to view the entire list of file type associations on your Windows 10 PC.

 
### 2. How do I change the default associations in Windows 10?


Like we’ve mentioned earlier in the post, there are three ways to change the default file associations in Windows 10: Open With, Settings, and Command Prompt. So, depending on your requirements and use case, you can pick any of these methods and follow the steps above to change the default file type associations on your computer.

 
### 3. How do I remove a file association in Windows 10?


The easiest way to remove a file association in Windows 10 is to reset the app defaults to the Microsoft recommended defaults. For this, go to Settings (Windows + I) and navigate to Apps > Default apps. On this page, scroll down to the bottom, and hit the Reset button below Reset to the Microsoft recommended defaults.

 
### 4. How to change what program opens a file in Windows 10?


Changing what program opens a file in Windows 10 requires you to change its default file associations. And as we’ve mentioned already, you can perform this operation in three different ways, steps for which are listed above.




