---
title: "Unlock Secrets of Your PC: Discover How to Erase Microsoft Defender Protection History on Windows 11!"
ShowToc: true 
date: "2023-04-30"
author: "Angela Stiles"
---
*****
Introduction

Microsoft Defender Protection is a helpful tool that aims to protect your device from malware, viruses, and other threats. However, there are instances when you'll need to erase the protection history on your Windows 11 system. This article will provide a step-by-step guide on how to unlock the secrets of your PC by erasing Microsoft Defender Protection history on Windows 11.

Step 1: Open Defender Security Center

The first step in erasing Microsoft Defender Protection history on Windows 11 is to open the Defender Security Center application. To open this app, click on the Start button, type "Defender," and click on the search result for Defender Security Center. Alternatively, you can open the app by pressing the Windows key + I to launch the Settings app. From there, select Update & Security > Windows Security > Open Windows Security.

Step 2: Access the Protection History page

Once you've opened the Defender Security Center app, click on the History tab located on the left-hand side of the screen. This will give you access to the Protection History page, where you can view all the activities that Microsoft Defender Protection has detected on your device.

Step 3: Erase Protection History

To erase Microsoft Defender's Protection history, click on the Clear history button located on the right-hand side of the screen. After clicking the button, a dialogue box will appear asking you to confirm whether you want to clear your protection history. Click "Clear" to proceed with erasing the history.

Step 4: Verify Protection History Erased

After clicking on "Clear," Microsoft Defender Protection history on your Windows 11 device will be erased. You can verify that the history has been erased by returning to the Protection History page and checking that the history list is now empty.

Conclusion

In conclusion, erasing Microsoft Defender Protection history on Windows 11 is a simple process that can help unlock secrets of your PC. This article has provided a step-by-step guide on how to access the Protection History page, clear the history and verify that it's erased. Remember to regularly clear your Microsoft Defender Protection history to ensure that your device remains safe from attacks.

{{< youtube aDul8S6XVdk >}} 



If you are already using Windows Security, you might know that the security app maintains a record of its scans and actions in the Protection History folder. The Windows Security protection history folder allows you to review the changes and undo them.
While Windows Security keeps the record of its scan for fair reasons, at times, you might want to clear it. If you have never checked the Protection History folder of Windows Security, it is likely to be a complete mess. So, to have more control and proper view, it’s best to clear the Protection history folder in Windows 11.
How to Update Drivers on Windows 11

 
## 4 Methods to Clear Microsoft Defender Protection History on Windows 11


Hence, if you are looking for ways to clear the Microsoft Defender or Windows Security Protection History on Windows 11, you have landed on the right page.
Below, we have shared a few best ways to clear Windows Security Protection History on Windows 11. Let’s check out.

 
### 1) Clear Windows Security Protection History Manually


This method will manually clear the Protection history from the local drive. Here are some of the simple steps you need to follow.
1. First of all, open File Explorer on your Windows 11 and navigate to this path:
C:\ProgramData\Microsoft\Windows Defender\Scans\History

2. Double click on the Service on the History folder.

3. On the Service folder, right-click on the History and select Delete.

That’s it! This will clear the Protection History on your Windows 11 computer.

 
### 2) Clear Windows Security Protection History via Event Viewer


You can also use Event Viewer on Windows 11 to clear the Windows Security Protection History. For that, follow some of the simple steps we have shared below.
1. First, click on the Windows 11 search and type in Event Viewer. Next, open the Event Viewer app from the list of options.

2. On the Event Viewer, select the Event Viewer (Local) and then expand the Applications and Services Logs.

3. Next, select the Microsoft folder.

4. On the right side, double click on Windows.
5. On Windows, scroll down and double-click on the Windows Defender.

6. Next, double-click on the Operational on the Windows Defender.

7. On the right pane, click on the Clear log button as shown below.

8. Now, you will see a confirmation prompt. Click on the Save and Clear button to clear the log.

That’s it! This will clear the Microsoft Defender Protection History to log in to your Windows 11 computer.

 
### 3) Clear Microsoft Defender Protection History via Local Group Policy


You can use the Local Group Policy editor to clear the Windows Security Protection History. You need to follow some of the simple steps we have shared below.
1. First, click on the Windows 11 search and type in Local Group Policy. Next, open the Local Group Policy Editor from the list.

2. On the Local Group Policy Editor, navigate to the following path:
Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Antivirus > Scan.

3. On the right side, find and double-click the Turn on removing items from scan history.

4. On the Window that appears, select ‘Enabled‘ and enter the time frame. Don’t set the number of days to zero, as zero means forever. You must enter the days you want Windows security to clear the protection history. Once done, click on the Ok button.

That’s it! This will automatically clear the Windows Security Protection History on Windows 11.

 
### 4) Clear Microsoft Defender Protection History via PowerShell


You can also use the PowerShell utility to clear the Microsoft defender Protection History. For that, follow some of the simple steps we have shared below.
1. First, click on the Windows 11 search and type PowerShell. Next, right-click on PowerShell and select Run as administrator.

2. On the PowerShell Window, paste the following command and hit the Enter button.
Set-MpPreference -ScanPurgeItemsAfterDelay 5

Important: The 5 at the end of the command represents the days after Windows security will clear the Protection History log. You can change the number as per your wish.
How to Fix Sleep Mode Not Working on Windows 11
So, these are some of the best ways to clear the Microsoft Defender or Windows Security Protection History log on Windows 11. If you need more help removing the Defender Protection history log, let us know in the comments below.




