---
title: "Unveiling the Mystery: Find Out What Really Happens Behind Your Windows 11 Startup and Shutdown with This Simple Trick!"
ShowToc: true 
date: "2023-05-27"
author: "Ramon Riley"
---
*****
# Unveiling the Mystery: Find Out What Really Happens Behind Your Windows 11 Startup and Shutdown with This Simple Trick!

As computer users, we often encounter issues or problems with our system's performance. And most of the time, we have no idea what's going on behind the scenes. One of the most puzzling aspects of using a computer is the startup and shutdown process. Have you ever wondered what really happens during the startup and shutdown process of your Windows 11 operating system? If so, then have no fear because we have a simple trick to unveil this mystery!

First, let's discuss what happens during the startup process. When you press the power button on your computer or laptop, the motherboard receives a signal, and power supply to the system starts. Depending on various factors like hardware configuration, BIOS settings, and system performance, the computer's hardware starts its initialization process. Once the initialization is complete, the operating system starts loading the required drivers and necessary system services. Finally, the Windows logon screen appears, and you can log in with your credentials.

Now, let's move on to shutdown. During the shutdown process, Windows closes all running applications, saves any open work, and stops all system services. The system then enters the shutdown phase, where it unloads drivers and system services, and finally, the kernel (core of the operating system) terminates, and the system powers off.

But how can you see what's happening in real-time during your Windows 11 startup and shutdown process? Here's the simple trick: you can enable a setting in Windows that will allow you to observe the startup and shutdown processes in detail.

To enable this setting, follow these steps:

1. Open the Start Menu and type "event viewer." Click on the Event Viewer app that appears.
2. In the Event Viewer, click on "Create Custom View" in the right sidebar.
3. In the "Create Custom View" window, check the boxes next to "Critical," "Warning," and "Information."
4. In the "Logged" drop-down menu, select "Last Hour."
5. Name your custom view, such as "Startup and Shutdown."
6. Click on "OK" to create the view.

Now your custom view is saved in the Event Viewer, and you can observe what happens during startup and shutdown. To use it, follow these steps:

1. Open the Event Viewer from the Start Menu.
2. In the left sidebar, click on "Custom Views."
3. In the right sidebar, click on your custom view.
4. In the middle pane, you will see a log of all startup and shutdown events that occurred in the last hour.

You can use this log to troubleshoot any issues you are having with your system during startup and shutdown. For example, if you notice that there are frequent critical errors during the startup process, you can investigate the cause and resolve the issue.

In conclusion, the startup and shutdown processes of a computer can be mysterious, but with this simple trick, you can unveil the mystery and observe the process in detail. Enabling a custom view in the Event Viewer, which logs all startup and shutdown events, can help you diagnose any problems and optimize your system's performance. Try it out, and you might be surprised by what you discover!

{{< youtube L8tdPYqFV7E >}} 



While using Windows 11, sometimes you may want to check the Startup and shutdown history of your PC. There could be various reasons you would like to check when a computer booted up or shut down history. For example, if you share your PC with your family members, you may want to track the startup/shutdown history to know if someone has used your PC in your absence.
Yes, there could be other reasons, such as while troubleshooting BSOD errors, the technician might ask you to provide this report. Whatever might be the reason, you can quickly check your Startup and Shutdown history on Windows 11.

 
## Steps to Check Your Startup and Shutdown History in Windows 11


Hence, this article will share the few best methods to check your Startup and Shutdown history on Windows 11. The methods will be straightforward; just follow them as mentioned below. Let’s get started.

 
### 1) Track Startup & Shutdown History via Event Viewer


We will use the Windows Event Viewer utility to track the Startup & shutdown history in this method. Here are some of the simple steps that you need to follow.
1. First, click on the Windows 11 search and type in Event Viewer. Next, open Event Viewer from the list of matching options.

2. On the Event Viewer, navigate to the Windows Logs > System.

3. Double click on the Filter Current Log.. option on the right pane, as shown below.

4. On the Filter Current Log window, you need to type the Event ID to check the Startup and shutdown logs. For that, enter the IDs 6005 and 6006. Once done, click on the Ok button.


 

ID 6005: This showed the event log when it was started (Windows 11 Startup)
ID 6006: This shows when the event log has stopped (Windows 11 Shutdown)



5. Now, you will see all your Startup and Shutdown history of Windows 11.

That’s it! You are done. This is how you can check your Startup and Shutdown history on Windows 11 via Event Viewer.

 
### 2) Check Startup & Shutdown History via Command Prompt


In this method, we will use the Command Prompt utility of Windows 11 to check the Startup & Shutdown history. Here are some of the simple steps you need to follow.
1. First, click on the Windows 11 search and type in Command Prompt. Next, right-click on the Command Prompt and select Run as administrator.

2. If you want to check the Startup history, execute the command:
wevtutil qe system "/q:*[System [(EventID=6005)]]" /rd:true /f:text /c:1 | findstr /i "date"

3. If you wish to check the Shutdown history, execute the command:
wevtutil qe system "/q:*[System [(EventID=6006)]]" /rd:true /f:text /c:1 | findstr /i "date"

That’s it! You are done. This is how you can check the Startup & Shutdown history on Windows 11 via Command Prompt utility.
It’s pretty easy to check your Startup and shutdown history on Windows 11 operating system. You can also use third-party apps to track the same thing, but third-party also collect the data from your Event Viewer. So, it doesn’t make any sense to use third-party apps for checking the Startup & Shutdown history on Windows 11.




