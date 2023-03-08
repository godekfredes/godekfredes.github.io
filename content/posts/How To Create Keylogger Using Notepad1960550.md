---
title: "Discover Shocking Secrets: Learn How to Create Your Own Keylogger using just Notepad!"
ShowToc: true 
date: "2023-05-03"
author: "Angelia Wells"
---
*****
+++
title = "Discover Shocking Secrets: Learn How to Create Your Own Keylogger using just Notepad!"
date = "2022-05-01"
tags = ["tech", "hacking", "notepad", "keylogger"]
+++

Are you curious about keyloggers, those mysterious pieces of software that can record everything somebody types on their keyoard? Do you want to create your own keylogger, just for learning purposes or to monitor someone's activities? Look no further! In this tutorial, we will show you how easy and simple it is to create a basic keylogger using just Notepad, the built-in text editor that comes with every Windows computer.

But first, let's define what a keylogger is and what it does. A keylogger is a type of software that secretly records every keystroke made by a user on their computer or mobile device. This includes not only letters and numbers, but also special characters, punctuation, and even passwords that are typed into login screens. Keyloggers can be used for various purposes, such as monitoring employee productivity or detecting cybercrime. However, they can also be misused to violate people's privacy and steal sensitive information.

Now, let's start creating our keylogger using Notepad. First, open Notepad by pressing the Win key + R combination and typing "notepad" in the Run dialog box. Then, copy and paste the following lines of code into a new Notepad file:

```
@echo off
color 09
start %0
:start
set logfile=%temp%\log.txt
if exist %logfile% goto overwrite
:notexist
set keylog=%~dp0keylogger.exe
if not exist %keylog% goto notexist
%keylog% /INVISIBLE /LOG %logfile%
goto loop
:overwrite
%keylog% /INVISIBLE /LOG %logfile% /ONERROR %0
:loop
timeout /t 5 /nobreak > nul
goto loop
```

This code is written in BAT (batch) language, and it contains several commands that will create a new file named "log.txt" in the user's temporary directory, then launch another file named "keylogger.exe" that will record and save all keystrokes in the log file. The code also includes a loop that will repeat the same process every 5 seconds until the user shuts down the computer.

Next, save the file with a descriptive name such as "mykeylogger.bat". Be sure to choose "All Files" as the file type and not "Text Files", or else Notepad will automatically add ".txt" to the end of the file name and ruin the code.

Now, the hard part is done! You can run the keylogger by double-clicking on the "mykeylogger.bat" file, and it will start recording all keystrokes made by the user. However, the log file will be hidden in the user's temporary directory and won't be easily accessible.

To view the log file, you need to download and install a small utility called "keylogger.exe" which was referenced in the code above. This is the file that actually does the logging work, and without it, the .bat script will not work. You can download a free version of keylogger.exe from various sites online, or create your own version using programming languages such as C++ or Java.

Overall, creating a basic keylogger using Notepad is not difficult, but it does require a basic understanding of computer programming and some caution. It's important to remember that using keyloggers without somebody's express consent is illegal and can lead to severe legal consequences. Therefore, use your newfound knowledge only for ethical and educational purposes, and never for malicious intent.

In conclusion, we hope this tutorial has been helpful to you in learning how to create your own keylogger using just Notepad. By combining different commands and scripts, you can further customize and enhance the keylogger's functionality to suit your needs. However, remember to always use this knowledge responsibly and with respect for other people's privacy.

{{< youtube gxpX_mubz2A >}} 



These keyloggers can detect your bank accounts passwords too. And these type of keylogger can also be created with the notepad text editor. So, let’s know how to create a keylogger using notepad

 
## How To Create Keylogger Using Notepad


The method is very simple and easy and you don’t need any tool to do this but just a notepad to perform the task. So just follow the post below to proceed.

 
### Creating Keylogger With Notepad:


Step 1. First of all, you need to open notepad in your windows by pressing Window button and then selecting the notepad from the options. Now in notepad copy and paste the below code in it.
Step 2. Now save this file as Logs.bat on your desktop.
Step 3. Now create a new folder named logs. (Note that keylogger will only work if the folder name is logs). Cut the folder and paste it into drive C
Step 4. Now test your file Log.bat and then after entering the Username and password
Step 5. Open the folder in C drive and see all saved key logs there as a text file created there automatically.
That’s it! you are done, you have successfully created a keylogger in notepad.

 
### Video



So above is all about How To Create a Keylogger Using Notepad. With this method, you can easily record out the keystrokes of your keyboard that had been entered in the batch file. And you also use it to shock your friends by telling them their username and password with this. Hope you like the post, don’t forget to share and leave a comment below if you have any related query.




