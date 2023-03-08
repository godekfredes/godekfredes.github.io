---
title: "You won't believe how easy it is to protect your files on Mac: Master file permissions with this simple guide!"
ShowToc: true 
date: "2023-04-13"
author: "Maria Nielson"
---
*****
Title: You Won't Believe How Easy it is to Protect Your Files on Mac: Master File Permissions with this Simple Guide!

If you're concerned about the safety of your files on Mac, you're not alone. With so many security issues cropping up day after day, you're right to be worried. But what if we told you that protecting your files on Mac is easier than you think? Thanks to file permissions, you can choose who can access, modify, or delete files on your Mac. In this guide, we'll teach you how to master file permissions and safeguard your files from prying eyes.

But first things first. What are file permissions and why do you need them? Put simply, file permissions are a way of controlling who can access your files and what they can do with them. By assigning specific permissions to each file, you can restrict access to certain users, groups, or applications. This not only protects your files from unauthorized changes or deletions, but it also ensures that only the right people have access to sensitive data.

Now that you know what file permissions are, let's dive into the nitty-gritty of how to set them up. Follow these simple steps to master file permissions on your Mac:

Step 1: Open the Finder

Go to your Mac's desktop and click on the Finder icon (the smiley face in the dock). This will open the Finder, which is where you can access all your files and applications.

Step 2: Choose the File

Navigate to the file or folder that you want to set permissions for. Right-click on the file and select "Get Info" from the dropdown menu.

Step 3: Set Permissions

In the Info window that pops up, you'll see a section labeled "Sharing & Permissions." This is where you can set permissions for the file. By default, the Owner and group have read and write access, while everyone else has no access. To change these permissions, click on the lock icon in the bottom right corner and enter your admin password. Then, click on the "+" icon to add a new user or group.

Step 4: Choose a User or Group

Choose the user or group that you want to set permissions for. You can select from a list of existing users and groups, or you can manually enter a new one. Once you've selected the user or group, you can set their permissions by clicking on the dropdown menu next to their name. You can choose from read-only, write-only, or read/write access.

Step 5: Save the Changes

Once you're happy with the permissions you've set, click on the "Apply to enclosed items" button to apply these changes to all the files and folders within the directory. Then, click on the "Lock" icon again to save your changes.

Congratulations! You've just mastered file permissions on your Mac. Now that you know how to set permissions for your files, you can rest easy knowing that your data is safe from prying eyes. By taking a little time to set up permissions now, you'll save yourself from a lot of headaches later on. So go ahead, protect your files and enjoy peace of mind!

{{< youtube TfhcJXdNSdI >}} 



In Summary


Most file systems provide attributes for files and directories to help you determine which users on your computer can read, modify, or execute its contents.
macOS uses the Apple File System (APFS), which supports the traditional Unix permissions that allow you to change permissions for files and directories on your Mac for different users and groups.
Depending on whether you’re comfortable with the GUI or the CLI, you can either use Finder or Terminal to change file permissions on Mac and control access to its files and directories.







Most operating systems either use the traditional Unix permissions or the ACL (Access Controls Lists) permissions for controlling file and directory access.
Talking about macOS, the operating system uses the Apple File System (APFS) on version 10.3 and later. Since APFS supports the traditional Unix permissions, it gives you the ability to change permissions for files and directories on your Mac for different users and groups.
So if you want to change permissions for users on your Mac to limit their access to system files and directories, this guide should see you through.

 
## Understanding macOS File Permissions


To begin with, let’s first take a look at the file and directory permissions offered by macOS. Having been derived from the Unix operating system, macOS supports the Unix permissions set, which includes the following permissions:

 

Read: Grants the ability to read a file. When used with directories, this permission provides the ability to view a directory’s name; but not its content.
Write: Grants the ability to modify a file. For directories, it works by offering the ability to modify entries in a directory to allow creating, renaming, and deleting files.
Execute: Grants the ability to execute a (program) file. When set for directories, it enables access to a directory’s content (subdirectories and files) and provides the search functionality to access a file’s content — granted the file also has the read permission.



macOS allows you to manage these permissions for three classes on your Mac, namely user, group, and others. Of these, the user class is the creator/owner of a file, whereas the group represents a set of different users on a system that share the same privileges, and the others refers to users that are neither the owner nor a member of any group.
Now, depending on whether you prefer the GUI (Graphical User Interface) or the CLI (Command Line Interface), you can either use Finder or Terminal to change file permissions on Mac.

 
## Change File Permissions on Mac Using Finder


Finder offers one of the easiest ways to change file and directory permissions (or folder permissions) on Mac. So if you’re new to macOS and aren’t comfortable using the Terminal, you can modify permissions with Finder.
Here’s a breakdown of the different file and directory permissions on Mac and how they work in Finder:

 

Read & Write: Allows a user to open a file or directory and modify it.
Read only: Allows a user to open a file or directory but not make any changes to it.
Write only (Drop Box): Allows a user to only save items to the Drop Box, which is a folder inside the Public folder.
No access: Blocks complete access to the file or directory.



Now, once you have an idea about these permissions, you can proceed with the steps below to set file permissions on Mac using Finder. Do note, however, that you need to be the system administrator to be able to change the file permissions for different users on your system.

 

Open Finder and navigate to the file or directory whose permission you want to modify.
Right-click on a file/directory and select the Get Info option from the context menu to get a list of all the accounts and user groups on your Mac with their privilege category.
In the Info window, scroll down to the bottom to the Sharing & Permissions section to see who has what privileges.

Tap on the padlock icon in the bottom right and enter the admin password to unlock access to permission modifications.
Depending on which class’ privileges you want to modify, select it under Name, tap on the arrow button adjacent to it in the Privilege tab, and select a permission type from the pop-up menu.




If you want to set permissions for a new user on your Mac that’s not listed under Sharing & Permissions, click the plus button and tap on New Person. In the next dialog box, give a username and password, and tap Create Account. Once added, select it from the user menu and click the Select button. Hereafter, you can set permission settings by following the above steps.
As soon as you’re done setting permissions, click on the lock icon again to lock permission modification, and close the Info window.
If you’ve accidentally messed up some permissions, you can undo them by clicking on the action pop-up menu (or three-dot menu) button and hitting Revert changes.

 
## Change File Permissions on Mac Using Terminal


Unlike Finder, using the Terminal to change file and directory permissions is a little complex. It requires familiarity with Terminal commands and an understanding of the alphabetic and numeric representation (or octal permission notations) of file permissions to be used effectively.
However, once you’re familiar with it, you can take advantage of the granular control over permissions that it offers to change permissions of files and directories efficiently.
Here’s a primer to get you familiar with alphabetic and numeric permission representations.
In Unix file permissions, the permission set comprises eleven characters. Among these, the very first character identifies whether the item is a file or directory; the following nine characters identify the permissions; the final character indicates whether the item carries extended attributes.
Talking about their representation, the first character is always either a hyphen (–) or letter (d), where the hyphen represents a file while d signifies a directory.
The next nine characters in the set are split into three groups/classes: user, group, and others. Each of these groups comprises three characters that are occupied by any of these following characters: – (no permission), r (read), w (write), and x (execute).
When put together, these characters form the following permissions:

 

— represents no read, write, execute permissions.
r– shows only read permission.
rw- means that the file can only be read and written.
rwx signifies that the file can be read, written, and executed.
r-x means that the file can only be read and executed.



On the other hand, the numeric representation of permissions replaces the above characters with numbers. It involves using a total of eight numbers, and here’s what they represent:

 

0 – no permissions
1 – execute
2 – write
3 – execute and write
4 – read
5 – read and execute
6 – read and write
7 – read, write, and execute



Finally, the last (eleventh) character in the permission notation is @. It’s called an extended attribute and is unique to specific files and directories on macOS.
With the basics out of the way, you can set file or directory permissions in Terminal with the help of the following steps:
Open the Terminal app — either via the Spotlight Search (command + space) or Finder > Applications > Terminal.app.
Navigate to the directory or file whose permission you want to modify. To do this, run the ls command to list items (files and directories) and cd to go into them.
Once you’re in the desired directory, use the following syntaxes to run your command:
First, let’s identify the current permissions for a file or directory by running:
ls -al file_name

To change read, write, execute permissions for all classes (user, group, and others) such that the user has all three privileges, the group has read and write permissions, and the others only get read permissions, you need to use the chmod command. The following are the different syntaxes on how to use it:
chmod ugo+rwxrw-r-- file_name
In octal permission notations, you’d run:
chmod 764 file_name
If you’re facing problems converting permissions from alphabetic representation to numeric representation, you can take the help of a chmod calculator for quick conversion.
For when you want to provide read and write access to all classes:
chmod a+rw file_name
or
chmod 666 file_name
When you want to remove execute permissions for group and others, run the following command in the Terminal window:
chmod ug-x file_name
or
chmod 766 file_name
To enable read and write privileges on multiple files (of the same kind) in a directory for all classes:
chmod a+rw *.txt
…where the flag a is used to target user permissions for all three classes: user, group, and others.
or
chmod 666 *.txt
Of course, these are just a few use-cases where you can use the Terminal to change file permissions on Mac, and there are a host of other scenarios where it can come in handy. And, the examples above should help you understand and set permissions for your files and directories in such cases much efficiently.

 
## Successfully Changing File Permissions on Mac


If you’ve followed the guide closely, you should have an understanding of the various file and directory permissions on macOS. And subsequently, depending on what you prefer — command-based or graphical interface — you should be able to pick a method accordingly to change file permissions on your Mac.




