---
title: "Secret hack revealed: Create a hidden user account in Windows 10 with just a few clicks!"
ShowToc: true 
date: "2023-03-09"
author: "Vivian Philbrick"
---
*****
+++
title = "Secret hack revealed: Create a hidden user account in Windows 10 with just a few clicks!"
date = "2021-05-20"
author = "John Smith"
tags = ["Windows 10", "user account", "hack", "tips and tricks"]
+++

Are you tired of having your friends or family members mess up your personalized settings on your computer? Maybe you want to keep certain files or programs private from prying eyes. Whatever the reason, creating a hidden user account in Windows 10 can allow you to keep your digital life separate and secure. 

Fortunately, this is a simple process that only requires a few clicks. Here is how you can create a hidden user account in Windows 10:

1. Press the **Windows** key and **R** key simultaneously to open the **Run** dialog box.

2. Type in **cmd** and hit **Enter** to open the **Command Prompt** window.

3. Type in **net user /add <username>** and hit **Enter**. Replace **<username>** with the name you want to give your hidden user account.

4. Type in **net localgroup administrators <username> /add** and hit **Enter**. This command will make your new user account an administrator, giving it full control over the computer.

5. Type in **reg add "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\SpecialAccounts\UserList" /v <username> /t REG_DWORD /d 0 /f** and hit **Enter**. This registry edit will hide your new user account from the login screen.

With these simple steps, you have successfully created a hidden user account in Windows 10. To access this account, you will need to log out of your current user account and then type in the name and password of your hidden account on the login screen.

One thing to keep in mind is that while this hidden user account will not be visible on the login screen, it is not entirely secure. Anyone with knowledge of this hack could still gain access to your hidden account. Therefore, it is important to ensure that the password for this account is strong and secure.

In conclusion, creating a hidden user account in Windows 10 can help you keep your computer separate and secure. With just a few clicks and some simple commands, you can create a user account that won't be visible to anyone else who may use your computer. Keep in mind that while this hack is useful, it is not entirely secure, and strong passwords are a necessary precaution.

{{< youtube FyxdyVvEYYA >}} 



While Windows 10 doesn’t officially support hidden administrator or user accounts, there’s a workaround that lets you create one. To create a hidden user account on Windows 10, we need to use Notepad.
So, if you are interested in creating a hidden user account in Windows 10, continue reading the guide till the end. Below, we have shared a step-by-step guide on creating a hidden user account in Windows 10.

 
## Steps To Create a Hidden User Account In Windows 10


Before exploring the method, please remember that the method given below works on Windows 7 and 8.1 computers. However, it might now work on a few Windows 10 builds. So, let’s get started.
Note: To create a hidden user account, we need to use Notepad. Through Notepad, we will create a .bat file. Any wrong implementation of code can trigger different errors. So, make sure to follow the steps accordingly.
1. First, right-click anywhere on the desktop and select New > Notepad.

2. On the notepad, you need to enter the following command:
@echo off net user hidden password abc /add net local group Administrators Myname /add
3. In the above command, you need to replace ‘abc’ with the password of your wish.
4. At the next line, replace ‘Myname’ with the name you would like to have your account.
5. The final results would look like this.

6. Now, you need to save the file with a .bat extension like hidden.bat

7. To create the administrator account, right-click on the .bat file and select ‘Run as administrator’

8. To verify the new account, open the command prompt, type'net users' , and press enter.

9. You will find the new hidden account there.
10. To hide the new net user administrator account, enter net user hidden /active:no on the command prompt.

11. To access the hidden admin account, type in net user hidden /active:yes on the CMD.

That’s it! This is how you can create a secret hidden user account in Windows 10.
So, this article is about how to create a secret hidden administrator account in Windows 10. You can easily enable or disable your hidden user account on Windows 10. If you’re stuck in the steps, let us know in the comments below.




