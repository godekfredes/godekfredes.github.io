---
title: "Unlock the Hidden Secrets of Windows 10 UAC Configuration in Just a Few Simple Steps!"
ShowToc: true 
date: "2023-01-13"
author: "Gary Furbee"
---
*****
Title: Unlock the Hidden Secrets of Windows 10 UAC Configuration in Just a Few Simple Steps!

Introduction:
Windows 10 is one of the most widely used operating systems in the world. With its plethora of features, it is essential for users to learn about its various functionalities to optimize their computing experience. One such feature is the User Account Control (UAC), which is responsible for safeguarding the system from unwanted changes. In this article, we will walk you through the process of configuring the UAC, so you can unlock its hidden secrets and take control of your privacy.

Step 1: Understanding User Account Control
The UAC is a security feature in Windows 10 that alerts users when an application tries to make significant changes to the system. It helps prevent unauthorized access to the system and enhances the security of your computer. The UAC is based on the principle of least privilege, which means that it only grants access to applications when required.

Step 2: Configuring User Account Control
To configure the UAC in Windows 10, follow the steps mentioned below:

1. Press the Windows key + R to open the Run dialog box.
2. Type in Control Panel and press Enter.
3. Click on User Accounts, followed by Change User Account Control Settings.
4. Move the slider to select the desired setting, based on the level of restriction you prefer. The options include:

- Always notify: This option gives the maximum level of protection, wherein every time an application tries to make changes, you will be prompted for permission.
- Notify me only when apps try to make changes to my PC: This option is the default setting. It provides a balance between security and usability, wherein you will only be notified when an app tries to make significant changes to the system.
- Notify me only when apps try to make changes to my PC (do not dim my desktop): This option is similar to the previous one. The only difference is that it does not dim the desktop when a UAC prompt appears.
- Never notify: This option is not recommended as it turns off the feature entirely.

5. Click on OK to save changes.

Step 3: Additional Tips and Tricks
Here are a few additional tips and tricks to further configure the UAC and enhance your Windows 10 experience:

1. To quickly access the UAC settings, use the search bar on the bottom left of your Windows 10 desktop and type in UAC. Click on Change User Account Control settings to get to the UAC settings page.
2. You can also customize the UAC for individual applications. Right-click on the application, select Properties, click on the Compatibility tab, and then select the checkbox next to Run this program as an administrator.
3. If you want to turn off the UAC temporarily, you can do so by opening the Run dialog box and typing in msconfig. Click on the Boot tab, select Safe boot, and then click on OK. Make sure to restart your computer after the changes are made.

Conclusion:
In conclusion, the UAC is an essential feature in Windows 10 that helps safeguard the system from unwanted changes. By following the steps mentioned above, you can configure the UAC to your needs and enhance your Windows 10 experience. It is vital to keep the UAC turned on to ensure the security of your system. So, unlock the hidden secrets of the UAC in just a few simple steps, and take control of your privacy today!

{{< youtube kDwKlnIH9Ks >}} 



Just like Windows Firewall, however, UAC (User Account Control) has had a massive impact on the security of Windows workstation endpoints, increasing the relative security of these systems for the better.
What may surprise most users though is that this feature actually started with Unix, Linux and Mac’s OS X: running a typical user session in a low privilege state, then asking the user to temporarily authorize a specific task.
UAC began its life with Windows Vista. Honestly, this version was massively overtuned, repeatedly prompting users more than it had to. With Windows 7, they started to reduce the criteria that would trigger a UAC prompt while still keeping critical settings secured. They also introduced a slider value for how much a user wanted UAC to intervene, with four distinct levels of prompts. They have continued to use this feature with current versions of Windows.

 
## Configuring User Account Control


To view this slider, you’ll want to go to the Control Panel and select “User Accounts.”
Once here, you will see a number of options available. The one you’ll be looking for is “Change User Account Control Settings.”
After you have clicked on this option, you will be presented with Windows 10’s version of the Slider option values. These are as follows:

 

High — Always Notify

Always notify me when apps try to install software or make changes to my computer
When I make changes to Windows Settings

Purpose: Microsoft recommends this setting if you install new programs consistently and go to potentially unsafe websites 




Medium High (default)

Notify me only when apps try to make changes to my computer
Don’t notify me when I make changes to Windows settings

Purpose: Microsoft recommends this setting if you have a specific list of applications that you run and websites that you visit regularly




Medium Low

Notify me only when apps try to make changes to my computer (do not dim my desktop)
Don’t notify me when I make changes to Windows settings

Purpose: Microsoft doesn’t recommend using this setting unless you have specific graphic limitations or software restrictions that would affect the dimming of the desktop




Low — Never Notify (Disable UAC)

Never notify me when apps try to install software or make changes to my computer
Never notify me when I make changes to Windows settings

Purpose: This function sets UAC as low as it will go. While this effectively disables UAC, there may still be certain protections active. Microsoft does not recommend this setting if at all possible







Please keep in mind that whenever you are modifying UAC levels, you will need to restart the system before the changes will take effect.
UAC has several tricks beneath the surface that you wouldn’t expect — such as dynamically redirecting certain applications that would normally go to secure locations like Program Files (and thus require administrator access) towards their own “virtual store” location without the application being aware of it.
It’s important to remember that programs running in user sessions aren’t the only ones affected by UAC policies. Scheduled Tasks are particularly vulnerable to UAC prompts because they do not interact with users unless otherwise specified. 
Thankfully, there is a one-click fix for this that’s very easy to get to. To get to Scheduled Tasks, right-click on Start and select “Computer Management.”
Once in Computer Management, you will want to drill down through “Task Scheduler” and click on “Task Scheduler Library.” Here you will see your most common Scheduled Tasks. To adjust a Scheduled Task, simply double-click on it to bring up an editing screen.
The checkbox we are looking for is near the bottom — “Run with highest privileges.” Once this box is checked, any applicable UAC prompts will be bypassed for the duration of the task.
UAC honestly is a bit smarter than most users give it credit for. In addition to the basic functionality put in by Microsoft, it also interacts with anti-malware applications through the Antimalware Scan Interface (AMSI). If a piece of malware asks for UAC permissions and is detected, it will immediately be blocked. 
In addition, most of the issues surrounding UAC pop up around installation time rather than during daily use. If at all possible, it is recommended to keep UAC active at least at a minimal level.
Sometimes, however, we have no choice but to try disabling UAC to resolve problems. For starters, not all programs play nicely with UAC. Certain ones, in fact, not only prompt users every time they do something, but they still do not work properly even if you authorize it. 
Some of these can be gotten around if you use the option “Run as Administrator” — which for the most part will prompt you once while the program is open and then run the application in an elevated state until it is shut down. Keep in mind that this particular issue tends to happen more with legacy applications than it does modern ones. If you are moving users up from XP but keeping their programs the same, you may have some complications.

 
## Conclusion


When it comes to protecting users, Windows 10 certainly is far more advanced out of the box than previous versions have been. The enhancements to UAC have certainly made it easier to deal with, as well as tune to your individual requirements. 
While Microsoft definitely recommends that UAC be left active if at all possible, they also recognize that sometimes this isn’t an option and give easy to use controls to adjust its activity level.

 
### Sources



