---
title: "Secret Tricks Revealed: How to Easily Get Around Windows 11 TPM Restrictions in Two Simple Steps!"
ShowToc: true 
date: "2023-04-20"
author: "Stephen Finch"
---
*****
Secret Tricks Revealed: How to Easily Get Around Windows 11 TPM Restrictions in Two Simple Steps!

Microsoft's recent release of Windows 11 has generated a lot of excitement among users, but it has also caused some concerns. One of the most significant issues is the TPM (Trusted Platform Module) requirements that the new operating system needs. Not all computers meet the requirements, which makes it hard for some users to upgrade to Windows 11.

However, there are some secret tricks that you can use to get around the TPM requirements in just two simple steps. Read on to find out how.

Step 1: Edit the Registry

The first step is to edit the registry keys. Here is how to do it:

1. Press the "Windows key + R" to launch the Run dialog box.

2. Type "regedit" and press "Enter" to open the Registry Editor.

3. Navigate to the "HKEY_LOCAL_MACHINE\SYSTEM\Setup" folder.

4. Right-click on the "LabConfig" folder, and select "New > DWORD (32-bit) Value."

5. Name the new value "BypassTPMCheck."

6. Double-click on the new value, and change the value data to "1."

7. Press "OK" to save the changes.

Step 2: Install Windows 11

Now that you have edited the registry keys, it is time to install Windows 11. Here is how to do it:

1. Download the Windows 11 installation files from the Microsoft website.

2. Launch the installer, and follow the instructions until you reach the "System check" stage.

3. On the "System check" page, click on the "I don’t have a TPM" option.

4. Continue with the installation as usual.

And that’s it! You have successfully bypassed the TPM requirements and installed Windows 11 on your computer.

Conclusion

The TPM requirements for Windows 11 have caused a lot of frustration among users, but with these two simple steps, you can easily get around them. By editing the registry keys and selecting the "I don’t have a TPM" option during the installation process, you can upgrade to Windows 11 on your existing computer. Just make sure to backup your important files and data before making any changes to your computer's registry.

{{< youtube qeCOcxwLzvs >}} 



However, Microsoft has made some changes in the system requirements to Windows 11. So, if you are planning to install Windows 11, make sure that your PC meets the minimum requirements to run Windows 11.
Even if your PC meets the minimum requirement, your motherboard needs a TPM chip to run Windows 11. You can follow our guide to know whether your motherboard has a TMP chip or not.

 
## 2 Best Methods to Bypass Windows 11’s TPM Requirements


If your PC doesn’t have a TPM chip, you need to bypass Windows 11’s TPM requirements to upgrade from Windows 10. So, if you are interested in bypassing Windows 11’s TPM requirement, you are reading the right article.
Below, we have shared the two best methods to bypass Windows 11’s TPM requirement on Windows 10. Let’s check out.

 
### Create a Windows 11’s TPM Bypass Script


In this method, we will create a simple script that will allow you to upgrade to Windows 11, even if your motherboard doesn’t have TPM. But, first, follow the steps shared below.
Step 1. First of all, open a web browser and open this Github page. Now scroll down to the Skip_TPM_Check_on_Dynamic_Update.cmd

Step 2. Now you need to copy all the code to create a script file.
Step 3. On your Windows 10 computer, open a Notepad and paste the code you have copied.

Step 4. Now save the file as disable-tpm-check.cmd on your desktop.

Step 5. Double click on the file you have created and click on the Yes button on the UAC dialog box.
Step 6. Now a PowerShell window will open.

That’s it! This will bypass the TMP check on your system. You can now install Windows 11 Preview builds through Windows updates.

 
#### How to Install Windows 11 after bypassing TPM Check?


Well, the above script will bypass the TPM check on your computer. Once done, you need to follow our guide to install Windows 11 operating system on your PC.

 
### Bypass TMP check via MediaCreationTool


If you prefer to clean install Windows 11 rather than an upgrade, you need to rely on AveYo’s Universal MediaCreationTool. Here’s what you need to do.
Step 1. First of all, open your web browser and navigate to this Github page.
Step 2. Now scroll down and download the MediaCreationTool.zip file.

Step 3. Now extract the zip file that you have downloaded and copy the MediaCreationTool.bat on a safe folder.

Step 4. Now you need to run the MediaCreationTool.bat file on your system.
Step 5. Now you will be asked to select the MCT Version. Here you need to select 11 as the MCT version.

Step 6. In the next window, you will be asked to select either Create USB or Create ISO. If you wish to create a bootable USB device, click on Create USB option.

Step 7. Now you will see the Windows 10 setup wizard. Here you need to select the USB Flash drive option.

Step 8. On the next Window, select the Removable drive and click on the Next button.

Step 9. Now the Media Creation tool will download Windows 11 from Microsoft’s servers. It will say ‘Downloading Windows 10’, but it will be downloading Windows 11.
That’s it! You are done. This is how you can bypass Windows 11 TPM requirement by using a modified MediaCreation tool.
So, this guide is all about how to bypass Windows 11 TPM requirements in few easy steps. I hope this article helped you! Please share it with your friends also. If you have any doubts related to this, let us know in the comment box below.




