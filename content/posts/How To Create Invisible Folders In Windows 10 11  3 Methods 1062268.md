---
title: "You Won't Believe How Easy It Is to Make Invisible Folders in Windows 10 and 11 - 3 Surprising Methods Revealed!"
ShowToc: true 
date: "2023-03-28"
author: "Katie Wood"
---
*****
# You Won't Believe How Easy It Is to Make Invisible Folders in Windows 10 and 11 - 3 Surprising Methods Revealed!

If you are looking for a way to hide your folders and files from prying eyes, you might be surprised to know that creating invisible folders in Windows 10 and 11 is a lot easier than you thought. In this article, we will reveal three surprising methods that you can use to create invisible folders in Windows, without any special software or technical expertise.

# Method 1: Using the Command Prompt

The first method to make an invisible folder in Windows is by using the Command Prompt. Here are the steps you need to follow:

Step 1: Open the Command Prompt by pressing the Windows key + R, or by typing "cmd" in the Start menu search bar.

Step 2: Type "md \foldername" and hit Enter. This will create a folder with the given name on the C drive.

Step 3: To create an invisible folder, type "attrib +h +s \foldername" and hit Enter. This will hide the folder and make it invisible to other users.

To access the hidden folder, simply open the Command Prompt and type "cd \foldername" followed by "dir" to view the contents of the folder.

# Method 2: Using the Registry Editor

The second method to create an invisible folder in Windows is by using the Registry Editor. Here are the steps you need to follow:

Step 1: Press the Windows key + R and type "regedit" in the Run dialog box.

Step 2: Navigate to the following path: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced\Folder\Hidden\NOHIDDEN

Step 3: Right-click on the right pane, select New, and then click DWORD (32-bit) Value.

Step 4: Name the new value "CheckedValue" and ensure that the value data is set to "0" (zero).

Step 5: Create a new folder and name it with a period (.) at the beginning of the folder name. This will make the folder invisible to other users.

# Method 3: Using a Batch File

The third method to create an invisible folder in Windows is by using a batch file. Here are the steps you need to follow:

Step 1: Open Notepad and type the following code:

@echo off

md .{foldername}

attrib +h +s .{foldername}

Step 2: Replace "foldername" with the name you want to give to your invisible folder.

Step 3: Save the file with a .bat extension.

Step 4: Run the file and your invisible folder will be created automatically.

With these three methods, you can easily create invisible folders in Windows 10 and 11 without any special tools or technical expertise. Whether you want to hide personal files or keep sensitive information away from prying eyes, these methods will enable you to create invisible folders that can only be accessed by you. So why wait? Start securing your files today!

{{< youtube nnd7MQVN-bc >}} 



If we talk about customization, you can apply skins, change wallpapers, change icons, etc. Not many would know, but Windows also lets you create invisible folders. Invisible folders could be helpful if you want to hide your sensitive data.
We all have sensitive data on our computers that we want to hide from others. This is where the invisible folders come into use. You can store those sensitive data inside an invisible folder. No one could see the invisible Folder except you.

 
## Steps To Create Invisible Folders In Windows 10/11


So, in this article, we will share some of the best working methods to create an invisible folder on Windows 10/11 computers.
1. First, create a new folder in any drive where you want to make the invisible Folder.

2. Now, right-click on a folder and select properties, and under customize tab, choose the change icon and select a blank icon for your Folder.

3. Now rename the Folder, clear all the text already there, press the ALT button, and type 0160 of the numeric keyboard.

4. Now, the Folder will become invisible, and only you will know about that Folder, and you can only access that to save your files there.

 
### Creating The Folder And Hiding It Internally


In this method, you will not rename or change the file type. The feature is given in the windows initiating itself, Which is very much undiscovered to many. So follow this helpful method that will hide your Folder in no time.
1. Select the Folder you want to hide. Then, right-click on it and select the option of Properties which is located at the very last of the popup.

2. Now, you can see the Attributes option in the General tab of Properties. Unselect the Read-Only and select the option of Hidden And click on Apply and then Ok.

3. That’s it! The Folder will be Gone. It’s more than invisible; you will not see the Folder again until you bring it back. Let’s know how to bring it back.


 
### How to Bring Back the Hidden Folder?


1. Go to organize and then Click on Folder And Search Option.

2. You Can see the Folder Options There; you need to click on View Tab just beside The General Tab. You will see a Hidden Files and Folder Option there, now change the option to Show Hidden Files and folders, And click on Apply and then Ok.

3. Once you have saved the arrangements. You will see your hidden Folder Now; you can change the Attributes to Read-only.


 
### Using Free Hide Folder


If you don’t want to rely on the manual option, you need to use Free Hide folder software. It’s a free tool to hide files and folders on Windows 10 operating system.
1. You need to download the Free Hide folder on your computer and install it.

2. Once installed, open the software, and you will see the screen like below.

3. Now, you have to click on Add. Once you click on Add, you need to browse the Folder that you need to hide.

4. Now, simply click ok, and you will see your Folder will be hidden.

5. Now, If you need to unhide the folder, open the software, click on the Folder, and select Unhide.

That’s it! You are done! This is by far the easiest way to hide and unhide any folder on your pc.
So, this is how you can create invisible folders in Windows. I hope this article helped you! Please share it with your friends also. If you have any doubts about this, let us know in the comment box below.




