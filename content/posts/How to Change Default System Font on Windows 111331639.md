---
title: "Revamp Your Windows 11 Aesthetics: Learn the Secret to Changing Your System Font!"
ShowToc: true 
date: "2023-05-26"
author: "Patricia Mceachin"
---
*****
Revamp Your Windows 11 Aesthetics: Learn the Secret to Changing Your System Font!

Are you bored with the default Windows 11 system font? Do you want to give your computer a new look and feel? Well, you're in luck! In this article, we will guide you through the simple process of changing your system font.

First, you need to choose a font that suits your style and preferences. There are tons of websites where you can download free fonts, such as DaFont, FontSpace, and Google Fonts. Once you've found the font you like, click on the download button and save it to your computer.

Next, you need to install the font on your computer. To do this, open the folder where you saved the font file, right-click on the file, and select "Install." If you're prompted to provide administrator permission, click on "Yes."

Now that you've installed the font, it's time to change the system font. Here's how you can do it:

Step 1: Open the Settings app by pressing Windows + I or by clicking on the Start menu and selecting "Settings."

Step 2: Click on the "Personalization" option, which is the fourth option from the top.

Step 3: On the left-side panel, click on "Fonts."

Step 4: Scroll down until you see the "Change font size" option. Click on the "Font settings" link right below it.

Step 5: Under "Font settings," you'll see a list of font categories. Find the category you want to change (e.g., "Menu," "Title bar," "Message box") and click on the font name next to it.

Step 6: A new window will pop up, showing you a preview of the font. Click on the font you want to use, then click on "OK."

Step 7: Repeat steps 5 and 6 for each category you want to change.

Step 8: Once you've made all the changes you want, click on "Apply" to save your changes.

That's it! You've successfully changed your Windows 11 system font. Now sit back, relax, and enjoy your new computer aesthetic.

In conclusion, changing your Windows 11 system font is a simple and easy way to revamp the look of your computer. With just a few clicks, you can give your computer a fresh new feel that suits your style and preferences. So, go ahead and try it out for yourself!

{{< youtube fAmPNhuZrh0 >}} 



If you have already used all customization options and looking for ways to have more, you can change the default system fonts. You can change your default system font to freshen up your Windows 11 PC’s look. And in this article, we will learn how to change the default system font on Windows 11.

 
## Steps to Change Default System Font on Windows 11


To change the font on Windows 11, you need to modify the registry settings. Hence, it’s recommended to safely backup the Registry file before following the steps. So, let’s check out how to change the default system font on the latest Windows 11 operating system.

 
### 1. Pick the Font from the Font Menu on Windows 11


First, you need to know the font’s name that you want to use as a default system font. You can only set pre-installed fonts as a default system font on Windows 11. Here are some of the simple steps you need to follow.
1. First, click on the Windows 11 Search and type in Font Settings. Next, open the Font Settings option from the search results.

2. On the Fonts Page, scroll down and find the font you want to use as default. Next, note down the font name.

3. You can also add your own fonts on Windows 11 by following this method.

 
### 2. Change Default System Font on Windows 11


Once you know the font name, you can set it as a default system font. However, you need to create a registry file to change the system font. Here’s what you need to do.
1. First of all, open Notepad on your Windows 11 computer.

2. On the Notepad, paste the following code:
Windows Registry Editor Version 5.00
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts] "Segoe UI (TrueType)"="" "Segoe UI Bold (TrueType)"="" "Segoe UI Bold Italic (TrueType)"="" "Segoe UI Italic (TrueType)"="" "Segoe UI Light (TrueType)"="" "Segoe UI Semibold (TrueType)"="" "Segoe UI Symbol (TrueType)"=""
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\FontSubstitutes]
"Segoe UI"="FONT-NAME"
Important: Replace the FONT-NAME with the actual name of the font you want to set as default. For example, if you want to use Adobe Arabic as the default system font, the code would look like:
Windows Registry Editor Version 5.00
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts] "Segoe UI (TrueType)"="" "Segoe UI Bold (TrueType)"="" "Segoe UI Bold Italic (TrueType)"="" "Segoe UI Italic (TrueType)"="" "Segoe UI Light (TrueType)"="" "Segoe UI Semibold (TrueType)"="" "Segoe UI Symbol (TrueType)"=""
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\FontSubstitutes]
"Segoe UI"="Adobe Arabic"
3. Once done, click on the File menu and select Save as.

4. On the Save as window, select ‘All files’ on the Save as type. Next, type in a name for the file followed by the .reg extension. For example – New System font.reg

5. Once done, click on the Save button on the Save As window. Next, right-click on the Registry file you have created and select Open.

6. Now, you will see a confirmation dialog box. Click on the Yes button to apply the new font.

That’s it! This will switch your default system font on Windows 11 PC.

 
### 3. How to Restore Default System Font on Windows 11


If you want to revert the font change, you need to create another registry file. Follow some of the simple steps we have shared below.
1. First of all, open Notepad on your Windows 11 PC and paste the following code into it
Windows Registry Editor Version 5.00
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts] "Segoe UI (TrueType)"="segoeui.ttf" "Segoe UI Black (TrueType)"="seguibl.ttf" "Segoe UI Black Italic (TrueType)"="seguibli.ttf" "Segoe UI Bold (TrueType)"="segoeuib.ttf" "Segoe UI Bold Italic (TrueType)"="segoeuiz.ttf" "Segoe UI Emoji (TrueType)"="seguiemj.ttf" "Segoe UI Historic (TrueType)"="seguihis.ttf" "Segoe UI Italic (TrueType)"="segoeuii.ttf" "Segoe UI Light (TrueType)"="segoeuil.ttf" "Segoe UI Light Italic (TrueType)"="seguili.ttf" "Segoe UI Semibold (TrueType)"="seguisb.ttf" "Segoe UI Semibold Italic (TrueType)"="seguisbi.ttf" "Segoe UI Semilight (TrueType)"="segoeuisl.ttf" "Segoe UI Semilight Italic (TrueType)"="seguisli.ttf" "Segoe UI Symbol (TrueType)"="seguisym.ttf" "Segoe MDL2 Assets (TrueType)"="segmdl2.ttf" "Segoe Print (TrueType)"="segoepr.ttf" "Segoe Print Bold (TrueType)"="segoeprb.ttf" "Segoe Script (TrueType)"="segoesc.ttf" "Segoe Script Bold (TrueType)"="segoescb.ttf"
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\FontSubstitutes]
"Segoe UI"=-

2. Once done, click on the File menu and select Save as.

3. On the Save as window, select ‘All files’ on the Save as type. Next, type in a name for the file followed by the .reg extension. For example – Default font.reg

4. Next, click on the Save button to save the registry file. Once saved, right-click on the Registry file and select Open.

5. On the confirmation prompt, click on the Yes button.

That’s it! This will restore the default font on your Windows 11 PC.
So, that’s all about changing the default system font on Windows 11 PC. If you want more customization options, you can use third-party apps to customize Windows 11. Third-party customization apps will enable live wallpapers, Start menu & Taskbar customization on your Windows 11 PC.




