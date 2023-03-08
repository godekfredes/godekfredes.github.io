---
title: "Windows 10 Users: Don't Panic! Here's How To Determine If Your Disk Drive Is GPT Or MBR In Just 3 Easy Steps!"
ShowToc: true 
date: "2023-02-22"
author: "Larissa Ames"
---
*****
# Windows 10 Users: Don't Panic! Here's How To Determine If Your Disk Drive Is GPT Or MBR In Just 3 Easy Steps!

If you're a Windows 10 user, you may be wondering if your disk drive is using the GPT or MBR partitioning scheme. GPT stands for the GUID Partition Table, while MBR stands for the Master Boot Record. Knowing which partitioning scheme your disk drive is using can be important when it comes to working with large capacity drives or utilizing advanced features, like UEFI boot mode. In this article, we'll show you how to determine if your disk drive is using GPT or MBR in just three easy steps.

## Step 1: Open the Disk Management Tool

The first step in determining if your disk drive is using GPT or MBR is to open the Disk Management tool. This tool is built into Windows 10 and provides a graphical representation of your hard drive and its partitions. You can open the Disk Management tool by pressing the Windows key + X and selecting "Disk Management" from the menu that appears.

## Step 2: Locate Your Disk Drive

Once the Disk Management tool is open, you should see a list of all the physical drives connected to your computer. Locate the disk drive you want to check and look at the partition layout. If the disk only has three partitions with one of them being labeled as "System Reserved," then the drive is using the MBR partitioning scheme. If the disk has four or more partitions and there is no "System Reserved" partition, then it's using GPT.

## Step 3: Verify Using Command Prompt

If you want to verify the partitioning scheme of your disk drive using the Command Prompt, you can do so by following these steps:

1. Press the Windows key + X and select "Command Prompt (Admin)".
2. Type "diskpart" and press Enter.
3. Type "list disk" and press Enter.
4. Locate the disk you want to check and note its number.
5. Type "select disk [disk number]" (replace [disk number] with the actual number of your disk) and press Enter.
6. Type "list partition" and press Enter.
7. Look at the Type column. If it says "EFI" or "Recovery," then the drive is using GPT. If it says "Primary" or "Extended," then it's using MBR.

With these three easy steps, you can determine if your disk drive is using GPT or MBR. Knowing this information can help you troubleshoot issues, understand compatibility limitations of your computer, and more. Don't panic if you're unsure what partitioning scheme your drive is using - just follow these steps and you'll be sure in no time!

{{< youtube AzojtcgEsbI >}} 



It will ask you to convert your disk to GPT because the bootable USB prepared for an MBR partition scheme can’t be used to install Windows 10 on a GPT-style disk.
You don’t need to know which partition scheme your hard disk uses in most cases. However, you might be asked to select between MPR and GPT partition if you have just assembled a new PC. Also, a few software needs to specify the partition scheme before the installation process.
If you are wondering about the difference between the two, GPT is a modern partition scheme required if you are booting the Windows operating system in UEFI mode. On the other hand, MBR is needed for booting older Windows versions in BIOS mode. If you want to install the latest Windows 10, you might need to use the GPT partition scheme.
Also Read: 10 Best Tools To Check & Repair Hard Disk Errors

 
## Steps to Check If a Disk Drive is GPT or MBR in Windows 10


You need to know the disk partition scheme before preparing a bootable USB drive to ensure an error-free installation of Windows 10. So, it’s always best to know if a Disk drive uses GPT or MBR on Windows 10 pc.

 
### 1. Through Disk Management


Well, you can use the built-in Disk Management utility of Windows 10 to know if a disk is GPT or MBR. Follow some of the simple steps given below.
Step 1. First of all, right-click on the Start button and select ‘Disk Management.’

Step 2. This will open the Disk Management tool.
Step 3. Right-click on the disk whose partition scheme you want to know and select ‘Properties.’

Step 4. On the next Window, select the ‘Volumes‘ tab.

Step 5. Now check the Partition style. The partition style section will tell you about the partition style used on the disk.

That’s it! You are done. This is how you can check if a disk drive is GPT or MBR in Windows 10.

 
### 2. Using Command Prompt


Well, the Command Prompt method might not be the easiest, but it’s still pretty effective. Follow some of the simple steps below to check if a disk uses GPT or MBR partition style.
Step 1. First of all, click on the Windows search and search for CMD. Right-click on the CMD and select ‘Run as administrator.’

Step 2. On the Command Prompt Window, enter ‘disk part and hit the Enter button.

Step 3. Next, enter ‘list disk’ on the Command prompt and hit the enter button.

Step 4. If a disk is GPT, it will have an asterisk(*) character under the GPT column. If the asterisk character is missing from the GPT column, it’s an MBR disk.

That’s it! This is how you can use the command prompt to check if a drive uses GPT or MBR partition style.

 
### 3. Using Powershell


Like the Command prompt, you can utilize the Windows Powershell to determine whether the disk drive uses GPT or MBR partition style.
Step 1. First of all, search for Powershell on Windows search. Now right click on the Powershell and select ‘Run as Administrator.’

Step 2. On the Powershell Window, type in ‘Get-Disk‘ and hit the Enter button.

Step 3. Now, look at the ‘Partition Style’ column. The column will list if a disk drive uses a GPT or MBR scheme.

That’s it! You are done. This is how you can check if a drive uses GPT or MBR partition style on Windows 10.
This article is all about checking if a drive uses GPT or MBR partition style on Windows 10. I hope this article helped you! Please share it with your friends also. If you have any doubts about this, let us know in the comment box below.




