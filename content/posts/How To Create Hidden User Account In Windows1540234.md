---
title: "Uncover the Top-Secret Trick to Creating a Hidden User Account on Your Windows OS - You Won't Believe How Easy It Is!"
ShowToc: true 
date: "2023-01-22"
author: "Charlene Mounts"
---
*****
+++ 
title = "Uncover the Top-Secret Trick to Creating a Hidden User Account on Your Windows OS - You Won't Believe How Easy It Is!" 
date = "2021-10-12" 
author = "OpenAI" 
tags = ["Windows", "User Accounts", "Security"] 
+++ 

If you want to keep your computer more secure or just don't like others messing with your settings or files, creating a hidden user account on your Windows OS is a great way to go about it. Having an additional user account that isn't easily visible can provide added protection and privacy.	

The process of creating a hidden user account is not complicated and can be accomplished even by those without extensive computer experience. This article will give you step-by-step directions for creating a hidden user account on Windows. 

Step 1: Create a New User Account 
The first step is to create a new user account on your computer. To begin the process, open the Control Panel and select User Accounts > User Accounts > Manage Accounts. 

Step 2: Set up the New User Account 
After you've created a new user account, it's time to configure it. Give the account a name and select a password. You can also choose to make it an administrator account or limit its privileges. 

Step 3: Hide the Account 
Now that the account is set up, it's time to make it hidden. Open the Command Prompt by pressing Windows+R and typing "cmd" in the Run interface. In the Command Prompt, type "net user [username] /delete" and press Enter. This step will delete your new user account's "hidden" status. 

Step 4: Modify the Registry 
The next step involves changing a value in the Windows registry. Open the Registry Editor by typing "regedit" in the Start menu search bar. Navigate to HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\SpecialAccounts\UserList.

Step 5: Add Your User Account 
In the UserList folder, right-click on any blank space and select New > DWORD (32-bit) Value. Name the value with the username of the user account you just created. Set the DWORD value data to 0 (zero). 

And that's it! You've created a hidden user account on your Windows OS. At this point, the account will not show up on the login screen or in the Control Panel. To access the account, you will need to press Ctrl+Alt+Del, open the Task Manager, click on the Users tab and select the hidden account. 

In conclusion, creating a hidden user account can add an extra layer of security and privacy to your computer's operation. It's not difficult to do, and if you feel the need to take further protective measures, you could also add a password to the Windows registry, making it more difficult for an unauthorized user to change the hidden account's settings. Stay safe!

{{< youtube ymXsrZqAM98 >}} 



With this, you can easily create an account with complete administrator access. The method is very easy, and it can be done with the help of a notepad.

 
## Steps to Create Hidden User Account In Windows


And with that, you can create a hidden account with desired username and password. Also, you can only access that account. So proceed with the simple steps below.
1. First, you need to open notepad in your windows by pressing the Window button and then entering notepad. Now copy the below code and paste it into notepad.

In the above code, replace hello with your desired password and Tech viral with your desired username.
2. Now save this file as hidden.bat

3. Now open the saved file by right-clicking on it and selecting run as administrator. The command prompt will appear, and your account will be created.

4. To check this account is being created, open the command prompt, type net user, and press enter.

That’s it. A new hidden account with complete administrator access is created in your windows.
So, that’s how easy it is to create a hidden user account in Windows operating system. If you need more help creating a hidden user account in Windows, let us know in the comments below.




