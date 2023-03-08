---
title: "Revitalize Your Windows 11 in a Few Simple Steps - Say Goodbye to Winsxs Folder Woes!"
ShowToc: true 
date: "2023-03-17"
author: "Linda Dees"
---
*****
Revitalize Your Windows 11 in a Few Simple Steps - Say Goodbye to Winsxs Folder Woes!

As you might already be aware, Windows 11 is here, and it comes with a host of new features and improvements. However, just like with any new operating system, there are bound to be some teething problems that need to be addressed. One such problem is the Windows WinSxS folder, which can take up a lot of space on your hard drive if left unchecked. In this article, we'll take a look at how you can revitalize your Windows 11 system by trimming down the WinSxS folder in a few easy steps.

Step 1: Run the Disk Cleanup Tool

The Disk Cleanup Tool is a built-in Windows utility that can help you free up space on your hard drive. To access it, press the Windows key + S on your keyboard and type "disk cleanup" in the search bar. The tool will automatically scan your hard drive for files that can be safely deleted, including temporary files, download files, and recycle bin items.

Once the tool completes its scan, you'll be presented with a list of files that can be deleted. Look for the "Windows Update Cleanup" option, which will usually be at the top of the list. Check the box next to it, then hit "OK" to proceed. This will delete all unnecessary files related to Windows updates, including files from the WinSxS folder.

Step 2: Use the Deployment Image Servicing and Management Tool

The Deployment Image Servicing and Management (DISM) tool is a command-line utility that can be used to clean up and optimize the Windows system. To use it, open the Command Prompt by pressing Windows key + X and selecting "Command Prompt (Admin)".

Once the Command Prompt opens, type in the following command:

dism /online /cleanup-image /startcomponentcleanup

This will initiate a scan of the WinSxS folder and remove any unnecessary files. Note that this process can take some time to complete, depending on the size of your WinSxS folder.

Step 3: Install the Windows 11 October 2021 Update

The October 2021 Update for Windows 11 includes several bug fixes and performance improvements, including enhancements to the WinSxS folder management. By installing this update, you can ensure that your system is running smoothly and that the WinSxS folder is not taking up more space than it needs to.

To install the update, go to Settings > Windows Update and click on "Check for updates". If the October 2021 Update is available for your system, click on "Download and install" to start the installation process.

Conclusion

By following these simple steps, you can optimize your Windows 11 system and reduce the size of the WinSxS folder. This will not only free up valuable space on your hard drive but also help your system run faster and smoother. It's worth noting that the steps above are just the tip of the iceberg when it comes to Windows 11 optimization, and there are many other tools and utilities available that can help you get even more out of your system. So, start exploring and enjoy a blissful computing experience with Windows 11!

{{< youtube IaXDn5Vs-Ks >}} 



The one problem that Windows users often face is insufficient storage space. While there are many ways to free up storage space on Windows like you can uninstall programs, delete photos & videos, etc., what if you don’t want to remove any personal files and still wants to expand the storage?
In such a case, you must clean up the WinSxS folder on your Windows computer. This article will discuss WinSxS in detail and how you can clean up this folder. Let’s get started.

 
### What is the WinSxS folder in Windows?


Well, WinSxS (Windows Side by Side) is a folder that resides on your system installation drive. It is where Windows stores its recovery files, files needed to install updates, previous versions of Windows components, and more.
It’s a very important folder and helps you revert to the previous state in case of software failure. Since Windows often use this WinSxS to store new files, the folder size can expand over time, leading to the low disk space problem.
The folder is located in your system installation drive. For example, if C: Drive is your system installation drive, you will find the WinSxS folder in the C:\Windows\WinSxS path.
When you open this folder, you will notice that the files are stored in more than one place in the operating system. However, there’s only one copy of a file, and the rest of the files are just hard links.
Also Read: How to Set Up OneDrive Personal Vault On Windows 11

 
## Best Ways to Reduce the Size of the WinSxS folder


You can’t delete the WinSxS, and you shouldn’t try to delete it. Deleting the files from the WinSxS folder might break the operating system’s functionality. In the worst case, your PC might even fail to boot. Hence, the best way to reduce the WinSxS folder size is by using the built-in disk cleanup tool.

 
### 1) Reduce the Size of the WinSxS folder via Task Scheduler


You can use the Task Scheduler to reduce the WinSxS folder size in Windows 11. Here’s what you need to do.
1. First of all, click on the Windows 11 Search and type in Task Scheduler. Next, open the Task Scheduler app from the list of options.

2. On the Task Scheduler, navigate to the following path:
Task Scheduler Library\Microsoft\Windows\Servicing\StartComponentCleanup

3. On the StartComponentCleanup, click on the Run button in the Selected Item section.

This will run the StartComponentCleanup tool and reduce the size of your WinSxS folder.

 
### 2) Cleanup WinSxS using Disk Cleanup Tool


You can use the Disk Cleanup utility to reduce the WinSxS folder size. Here are some of the simple steps shared below.
1. First, open File Explorer on your Windows 11. Right-click on your system installation drive and select Properties. Alternatively, open the Windows 11 search and type in Disk Cleanup. Next, open the Disk Cleanup utility from the list.

2. On the Local Disk Properties, click on the Disk Cleanup button. If you are using Disk Cleanup utility, you need to select the drive you want to clean.

3. On the Disk Cleanup prompt, click the Clean up system files button.

4. Now select all checkboxes and click on the Ok button.

That’s it! The Disk Cleanup utility will run and clean all unnecessary system files.

 
### 3) Clean up the WinSxS folder via CMD


You can also use the Command Prompt to clean up the WinSxS folder. You need to follow some of the simple steps we have shared below.
1. Click on the Windows 11 search and type in Command Prompt. Next, right-click the Command Prompt and select ‘Run as administrator’.

2. On the Command Prompt, execute the command:
DISM.exe /Online /Cleanup-Image /StartComponentCleanup

3. This will clear the specific group of files from the WinSxS folder. If you want to clean older Windows component versions, execute the command:
DISM.exe /Online /Cleanup-Image /StartComponentCleanup /ResetBase

That’s it! This is how you can clean up the WinSxS folder via Command Prompt in Windows 11.
Also Read: How to Block Access to Removable Storage Devices in Windows 11
So, these are the best ways to reduce the WinSxS folder size in Windows 11. You shouldn’t delete this folder at any cost; if you want to reduce the size, just follow our shared methods. If you need more help with the WinSxS folder in Windows 11, let us know in the comments below.




