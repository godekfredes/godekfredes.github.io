---
title: "Revolutionize Your Windows Experience - Step By Step Guide To Crafting The Ultimate Windows 11 Virtual Machine!"
ShowToc: true 
date: "2023-02-15"
author: "Latoya Mack"
---
*****
Revolutionize Your Windows Experience - Step By Step Guide To Crafting The Ultimate Windows 11 Virtual Machine!

Are you looking to upgrade your Windows experience? Do you want to make the most of the new Windows 11 features? Look no further than crafting your own Windows 11 virtual machine! In this step by step guide, we will show you how to create the ultimate Windows 11 virtual machine and revolutionize your Windows experience!

Step 1 - Choose The Right Virtual Machine Software
There are many virtual machine software options available, but not all of them support Windows 11. For our guide, we recommend using Oracle VirtualBox. It is free, open-source, and supports Windows 11.

Step 2 - Download Windows 11 ISO
You will need the Windows 11 ISO file to install it on your virtual machine. You can download it directly from the Microsoft website.

Step 3 - Create A New Virtual Machine
Open Oracle VirtualBox and click on the 'New' button to create a new virtual machine. Choose a name for your virtual machine and select 'Microsoft Windows' as the type. Make sure to select 'Windows 10 (64-bit)' as the version.

Step 4 - Customize Your Virtual Machine Settings
Before you start your virtual machine, customize its settings to ensure optimal performance. Increase the memory size to at least 4GB (4096 MB) and allocate at least 60GB of storage. You can also enable 3D acceleration, and set the graphics controller to 'VMSVGA'.

Step 5 - Install Windows 11 On Your Virtual Machine
Start your virtual machine and follow the Windows 11 installation process. Make sure to select 'Custom: Install Windows Only' when prompted, and choose the virtual hard drive you created in Step 3 as the installation location.

Step 6 - Install Guest Additions
Guest Additions are additional software components that enhance the performance of your virtual machine. To install Guest Additions, click on the 'Devices' tab on the VirtualBox menu and select 'Insert Guest Additions CD image'. Follow the installation instructions to complete the process.

Step 7 - Install Windows 11 Updates
After installing guest additions, make sure to update your virtual machine with the latest Windows 11 updates to ensure optimal performance.

Step 8 - Customize Your Windows 11 Experience
Now that your virtual machine is up and running, it's time to customize your Windows 11 experience. Install your favorite software, customize your desktop, and set up your preferred settings.

Congratulations! You have successfully created the ultimate Windows 11 virtual machine! By following this step by step guide, you can revolutionize your Windows experience and take advantage of all the features that Windows 11 has to offer. Happy computing!

{{< youtube WYrTajuYhCk >}} 



Creating a new virtual PC is easy, assuming your PC satisfies the requirements. You must be running a 64-bit business edition of Windows Pro or Enterprise edition; the Home edition does not include Hyper-V support. In addition, your CPU and associated hardware must meet specific requirements. (For this walkthrough, I assume you are running Windows on a PC with a supported Intel or AMD CPU; the rules for Arm-based CPUs are different.)  Most modern CPUs pass this test with ease. (For full details, see "Windows 10 tip: Find out if your PC can run Hyper-V.")
You also need enough physical hardware resources to devote to your virtual machine. I recommend at least 8 GB of memory, along with enough unused local storage to hold a full installation of Windows, apps, and checkpoints (32 GB should be sufficient).
Finally, you need a copy of the Windows 11 installation files in ISO format. You can get that file from Microsoft's Download Windows 11 page by choosing the Download Windows 11 Disk Image (ISO) option.
With those preliminaries out of the way, you're ready to get started. Note that all of the steps below work exactly the same on Windows 10 and Windows 11.
1. Click Start and type Hyper-V in the search box. If Hyper-V is already enabled, open the Hyper-V Manager utility and skip to the next step. If you see the Turn Windows features on or off option, click to open the Windows Features dialog box, choose the Hyper-V option, and restart your PC to continue.
2. In Hyper-V Manager, make sure your PC's name is selected in the center pane and then, in the Actions pane on the right, click New > Virtual Machine.
3. In the New Virtual Machine wizard, use the following settings:

 
Specify Name and Location – Enter a descriptive name here. This name will appear in the Hyper-V Manager window.Specify Generation – Choose Generation 2 here. (You won't be able to install Windows 11 on a Generation 1 VM, which is strictly for legacy operating systems.)Assign Memory – You can use the default settings here. If you have at least 16 GB of RAM on the host PC, I recommend entering 4096 MB in the Startup Memory box.
 
Configure Networking – Choose Default Switch from the drop-down menu.Connect Virtual Hard Disk – Use the default option, Create A Virtual Hard Disk. You can safely leave its size at 127 GB. Hyper-V creates a dynamically expanding virtual hard disk that uses only a fraction of that space.
 
Installation Options – Choose the second option, as shown here; then click Browse and choose the Windows 11 ISO from your Downloads folder.


4. Click Finish to create the virtual machine, but don't connect to the VM just yet. Instead, from Hyper-V Manager, right-click the VM you just created, click Settings, and make the following tweaks to avoid having Windows 11 complain later that your VM doesn't meet its hardware requirements:

 
In the Hardware pane on the left, select Security. Then, in the pane on the right, click Enable Trusted Platform Module.
 
Select Processor in the Hardware pane and change the setting for Number Of Virtual Processors to 2.
 
Click OK to save your changes.


5. Double-click the VM and click Start to connect to the virtual machine. Be prepared to click in the Virtual Machine Connection and tap any key to boot from the virtual DVD you created using your Windows 11 ISO. That should open the Windows Setup screen shown here.
6. Click next to begin the installation. When you're asked to enter a product key, click the small "I don't have a product key"  link at the bottom of the dialog box, and then select Windows 11 Pro from the list of available editions. Follow the prompts to complete setup.
If you configured Windows to use a Microsoft account, you'll need to do one last tweak before you can sign on in an enhanced session and use your VM in full-screen mode: Go to Settings > Accounts > Sign-in Options and turn the Require Windows Hello Sign-in For Microsoft Accounts switch to the Off position.
If you forget to make this adjustment and try to sign in using an enhanced session, you'll find yourself stuck at the Windows sign-in screen with only the background image visible. The fix is simple: From the Virtual Machine Connection window, choose View, then click Enhanced Session to clear the checkbox and switch to a basic session.
Sign in and make the change to your account settings and then use the View menu to switch back to an enhanced session.




