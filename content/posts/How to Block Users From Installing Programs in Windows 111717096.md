---
title: "Breaking News: Secret Windows 11 Hack Reveals How to Block Unauthorized Software Installs!"
ShowToc: true 
date: "2023-04-02"
author: "William Bristle"
---
*****
Breaking News: Secret Windows 11 Hack Reveals How to Block Unauthorized Software Installs!

If you're a Windows 11 user, you may have noticed that sometimes applications and software get installed without your permission. This can be frustrating, especially if you're wary of downloading third-party software that could compromise your computer's security. However, a recently discovered hack can help you prevent unauthorized software installs on your Windows 11 device.

The hack involves using the Windows Sandbox, a feature that allows you to run applications in a secure environment without affecting your main system. By using the Sandbox, you can test out software without risking any damage to your device. However, the Sandbox also has another use: blocking unauthorized software installs.

To use the hack, simply open the Sandbox and run a dummy application. This will create a new folder within the Sandbox that you can use to store any files that you want to protect. You can then create a symbolic link between this folder and your main user account, which will prevent any unauthorized software installs from being able to access it.

The process may seem a bit technical, but it's relatively easy to follow. Here's a step-by-step guide:

Step 1: Open the Windows Sandbox. You can do this by typing "Windows Sandbox" into the search bar and clicking on the app.

Step 2: Once the Sandbox is open, run a dummy application. This will create a new folder within the Sandbox.

Step 3: In the Sandbox, navigate to the folder that was created by the dummy application. Right-click on the folder and select "Properties."

Step 4: In the Properties window, go to the "Security" tab and click on "Advanced." This will open the Advanced Security Settings window.

Step 5: In the Advanced Security Settings window, click on "Disable inheritance." A pop-up window will appear asking if you want to remove all inherited permissions. Click "Remove."

Step 6: In the Advanced Security Settings window, click on "Add." This will open the Select Users or Groups window.

Step 7: In the Select Users or Groups window, type "Everyone" and click "OK."

Step 8: Back in the Advanced Security Settings window, click on "Edit." This will open the Permissions window.

Step 9: In the Permissions window, select "Everyone" and click on "Remove." This will remove all permissions for the "Everyone" group.

Step 10: Click on "Add" and enter your username. This will give you full permissions to the folder.

Step 11: Finally, create a symbolic link between the folder in the Sandbox and your main user account. You can do this by opening a Command Prompt window and typing "mklink /D C:\Users\Username\SandboxFolderName C:\Users\SandboxUserName\SandboxFolderName." Substitute "Username" with your main user account's name and "SandboxUsername" with the username of your Sandbox account.

Once the symbolic link is created, any unauthorized software installs will not be able to access the folder within the Sandbox, thereby keeping your computer protected.

In conclusion, if you're worried about unauthorized software installs on your Windows 11 device, this hack can help you keep your computer safe. By utilizing the Sandbox and creating a symbolic link, you can prevent any unwanted software from accessing your files. It may take a bit of time to set up, but the extra security is worth it. Keep this hack in mind the next time you're worried about your computer's safety.

{{< youtube aJ37b2-OhH8 >}} 



If your PC/laptop is running Windows 11, and if you often share your device with other users, it’s best to block the program installation completely. This way, you won’t have to worry about unwanted app installation.
Blocking the app installation will also prevent malicious apps from installing add-ons and adware on your system. Preventing users from installing programs in Windows 11 is pretty easy, and you can do it in several ways.
Also read: How to Run Older Programs in Compatibility Mode in Windows 11

 
## 3 Best Ways to Block Users From Installing Programs in Windows 11


Hence, if you are looking for ways to block users from installing programs on your Windows 11, you are reading the right guide. Below, we have shared a few best ways to prevent users from installing programs in Windows 11. Let’s check out.

 
### 1) Block Program Installation via Settings


This method will use Windows 11’s Settings app to block program installation. However, you can’t prevent app installation via Microsoft Store through the settings app. Here’s what you need to do.
1. First, click on the Windows 11 Start button and select Settings.

2. On the Settings app, click on the Apps section on the left pane.

3. On the right, click on the Advanced App settings.

4. Click on the drop-down menu beside Choose where to get apps.

5. From the drop-down menu, select The Microsoft Store Only.

That’s it! From now, Windows 11 will allow app installation via Microsoft Store only. It will block every other third-party app installation on your device.

 
### 2) Prevent Users from Installing Software via Group Policy


You can also use the Local Group Policy Editor to prevent users from installing software on your Windows 11. You need to follow some of the simple steps we have shared below.
1. Click on the Windows 11 Search and type Local Group Policy. Next, open the Local Group Policy Editor from the list of options.

2. On the Local Group Policy Editor, navigate to the path:
Computer Configuration/Administrative Templates/Windows Components/Windows Installer

3. On the right, search for Prohibit User Installs policy. Double click on the Policy to open it in a new window.

4. On the Prohibit User Install Window, select ‘Enabled‘ and click on the Apply button.

That’s it! After making the changes restart your Windows 11 computer. This will block the program installation completely. To revert the changes, select ‘Not Configured’ in the above step.

 
### 3) Block Program Installation on Windows 11 via Registry Editor


Like the Local Group Policy Editor, you can also use the Registry Editor to prevent program installation. You just need to follow some of the simple steps we have shared below.
1. First, click on the Windows 11 Search and type Registry. Next, open the Registry Editor app from the list of options.

2. On the Registry Editor, navigate to the following path:
HKEY_LOCAL_MACHINE\Software\Classes\Msi.Package\DefaultIcon

3. On the right side, double-click on the Default key.

4. Copy and paste the value below and click on the Ok button on the Value data field.
C:\Windows\System32\msiexec.exe,1

5. If you want to unblock program installation, enter this value and click on the Ok button.
C:\Windows\System32\msiexec.exe,0

That’s it! This is how you can prevent users from installing software on Windows 11.
Also read: How to Download & Install Tor Browser on Windows 11
If you often leave your computer unattended for hours, it’s best to block program installation. So, these are some of the best ways to prevent users from installing apps on Windows 11. If you know any easier way to block app installation on Windows 11, let us know in the comments.




