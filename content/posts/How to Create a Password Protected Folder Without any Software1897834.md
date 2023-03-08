---
title: "You won't believe how easy it is to create a password protected folder without any software - protect your files now!"
ShowToc: true 
date: "2023-05-11"
author: "Deborah Murphy"
---
*****
# You won't believe how easy it is to create a password protected folder without any software - protect your files now!

Do you have important files that you want to protect from prying eyes? Are you looking for a way to secure your folders without relying on third-party software? If so, you're in the right place. In this article, we'll show you how easy it is to create a password-protected folder without any software. 

Many people believe that creating a password-protected folder requires specialized software or technical expertise. However, this is not the case. With a few simple steps, you can create a secure folder and protect your files from unauthorized access. 

So, let's get started. Here's how you can create a password-protected folder on Windows:

1. Create a new folder wherever you want to keep your protected files.

2. Right-click on the folder and select "Properties". 

3. In the Properties window, select the "General" tab and click on the "Advanced" button. 

4. In the Advanced Attributes window, check the box that says "Encrypt contents to secure data" and click "OK". 

5. The previous step will lead you to the Confirm Attribute Changes, where you'll need to select one of the following:
    
    a. Apply changes to this folder only
    b. Apply changes to this folder, subfolders, and files

    Select the option as per your requirement and click on "OK". 

6. You will now be asked to back up your encryption key. Select the "Back up your file encryption key" option and follow the prompts to save your key. 

7. Click "OK" on all open windows to complete the process.

Congratulations! You've successfully created a password-protected folder without any software. Now, whenever you access the folder, you'll need to enter a password to view its contents. 

It's worth noting that this process only works if you're using a PC that supports BitLocker encryption. If your PC doesn't support BitLocker, you'll need to use third-party software to encrypt your folder. 

In conclusion, protecting your files is essential, and creating a password-protected folder is a great way to do it. With the steps above, you can quickly and easily create an encrypted folder and secure your sensitive data. So, try it out and safeguard your files from prying eyes.

{{< youtube RlG307IyztA >}} 



This post will help you a lot. We always want our files safe and private. As we have to share our laptops and PC with our friends at that time, it is important to secure and protect some of our private data which we won’t want to share with them. There are various methods available that help to create a password-protected folder. However, some of them need third party apps to do the job. Therefore, we are going to share a method that will help you protect a folder with a password without any software.

 
## Steps to Create a Password Protected Folder Without any Software


Step 1. Click Start and Open Notepad. Copy the below code and paste it into the notepad.

cls @ECHO OFF title Folder Private if EXIST “TechViral Locker” goto UNLOCK if NOT EXIST Private goto MDLOCKER :CONFIRM echo Are you sure you want to lock the folder(Y/N) set/p “cho=>” if %cho%==Y goto LOCK if %cho%==y goto LOCK if %cho%==n goto END if %cho%==N goto END echo Invalid choice. goto CONFIRM :LOCK ren Private “TechViral Locker” attrib +h +s “TechViral Locker” echo Folder locked goto End :UNLOCK echo Enter password to unlock folder set/p “pass=>” if NOT %pass%== techviral goto FAIL attrib -h -s “TechViral Locker” ren “TechViral Locker” Private echo Folder Unlocked successfully goto End :FAIL echo Invalid password goto end :MDLOCKER md Private echo Private created successfully goto End :End
Note: You can change the password with your desired one you just need to edit this line “if NOT %pass%== techviral goto FAIL”. You can replace “techviral” with your password.
Step 2. Now save it as Folderlock.bat.

Step 3. Now run the FolderLock.bat at the saved location now a folder named “Private” will be created in that directory.

Step 4. Now place your files which you want to protect in the “Private” folder. Now again double click the Flock file and it will ask you “do you want to lock (Y/N)”.

Step 5. Type Y and then press enter, Folder “Private” will then get hidden.

Step 6. Now again click on the FolderLock.bat file and it will ask you the unlock password and the password is techviral.

That’s it! Your folder is now secured with the password every time you want to secure your files run the FolderLock.bat and place your files in the “Private” folder and again run FolderLock.bat file which will hide the folder “Private“.

By this, your content will be safe and password protected and will be not visible to anyone else and can’t be accessed by any unauthorized access. And it is a very simple and easy method to secure your data as there is no requirement of any software in it only just a batch code to protect your data.
I suggest you to not to save this file on the desktop or on the drive where your operating system has been installed because if you did so, then whenever your operating system corrupts, all your protected data will be deleted, so save this file in any other drive as it will remain as such in that drive either your windows get corrupted.
Hope you like the post. Don’t forget to share. Leave a comment if you face any problem at any step.




