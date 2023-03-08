---
title: "You Won't Believe How Quick and Easy it is to Bulk Install Apps with Windows 10 S Package Manager!"
ShowToc: true 
date: "2023-02-03"
author: "Lucia Hamilton"
---
*****
# You Won't Believe How Quick and Easy it is to Bulk Install Apps with Windows 10 S Package Manager!

If you are a Windows 10 S user, you may already know how frustrating it can be when you have to install multiple applications one by one. It can take up so much of your time and effort, especially if you don't have a lot of knowledge about computers.

However, Windows 10 S Package Manager is here to change that. It is an application that allows you to install multiple apps with just one command. This not only saves you a lot of time but also ensures that you have all the necessary applications installed on your computer.

So, how do you use Windows 10 S Package Manager to bulk install applications? Here are the steps:

1. Open PowerShell as an Administrator.

2. Type the following command:

    `Invoke-WebRequest -Uri https://aka.ms/winsappinstall -OutFile $env:USERPROFILE\Downloads\AppInstaller.Appxbundle`

3. Hit Enter.

4. Type the following command:

    `Add-AppxPackage -Path $env:USERPROFILE\Downloads\AppInstaller.Appxbundle`

5. Hit Enter.

6. Once you have installed the Windows 10 S Package Manager, you can find it in the Start menu.

7. Open the Windows 10 S Package Manager and search for the applications you want to install.

8. Select the applications you want to install and click on the Install button.

9. Wait for the applications to download and install.

And that's it! You have successfully bulk installed applications using the Windows 10 S Package Manager.

One thing to note is that the Windows 10 S Package Manager only works for applications that are available in the Microsoft Store. So, if there are any applications that you want to install that are not available in the Microsoft Store, you will have to install them manually.

In conclusion, the Windows 10 S Package Manager is a very useful tool that can save you a lot of time and effort when installing multiple applications. Give it a try and see how much time you can save!

{{< youtube rz85ey2DZso >}} 



While it’s easy to install apps from the command line, a developer has created a web app that makes things easy and fun. Mehedi Hassan’s winstall is a web app that takes advantage of the new Windows 10’s package manager to install apps in bulk.
Winstall is a useful tool that is pretty much similar to Ninite. The good thing about Winstall is that it works like a charm, and it offers a cool way to share and install your favorite Windows 10 apps.
Also Read: How to Block Access to USB Drives in Windows 10

 
## Steps to Bulk Install Apps with Windows 10’s Package Manager


So, in this article, we are going to share a detailed guide on how to bulk install Windows 10 apps with Winstall. Let’s check out.
Step 1. First of all, click on this link and download the latest appxbundle.

Step 2. Once done, double click on the appxbundle and install it. If it’s already installed, then you will get the ‘Update’ option. Simply click on the ‘Update’ button to update the app installer.

Step 3. To confirm whether the Winget is installed, open Command Prompt and type in ‘winget’. If it shows you the Windows package manager information, then it’s successfully installed.

 
Step 4. Now head to the winstall.app on your browser.

Step 5. Now pick the app that you want to install on your device. To add the apps, click on the (+) button behind the app names.

Step 6. After selecting the apps, click on the ‘Generate Script’ button.

Step 7. Now on the next page, you will get the script to install the apps. Copy the code and paste it on the CMD.

Step 8. Now the Windows Package manager would start to download & install the apps from Microsoft’s repository.

That’s it! You are done. This is how you can bulk install Windows 10 Apps with Winstall.
So, this article is all about how to install apps with Windows 10’s Package Manager easily. I hope this article helped you! Please share it with your friends also. If you have any doubts related to this, let us know in the comment box below.




