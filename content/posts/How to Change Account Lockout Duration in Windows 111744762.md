---
title: "Unlock the Secret to Longer Login Times on Windows 11 - Learn How to Change Account Lockout Duration!"
ShowToc: true 
date: "2022-11-21"
author: "Nina Webster"
---
*****
Title: Unlock the Secret to Longer Login Times on Windows 11 - Learn How to Change Account Lockout Duration!

Introduction:
In today's digital age, almost everything is automated, including login processes. Windows 11 introduced new security features to protect user accounts from unauthorized access. One such security feature is the account lockout duration, which dictates how long an account remains locked after multiple login failures. However, default lockout durations can be a nuisance for users, leading to frequent lockouts and subsequently longer login times. Fortunately, Windows 11 users can change account lockout duration to suit their preferences. In this article, we will explore how to adjust an account's lockout duration to unlock the secret to longer login times.

Step 1: Access Account Lockout Duration Settings
To access account lockout duration settings in Windows 11, you must first open the Local Security Policy menu. To access the Local Security Policy, follow these steps:
1. Press the Windows key + R on your keyboard
2. In the Run dialogue box, type “secpol.msc” and click OK.
3. The Local Security Policy Editor window should appear.

Step 2: Locate Account Lockout Duration Settings
After opening the Local Security Policy Editor window, you must navigate to the account lockout duration settings. To achieve this, follow these steps:
1. In the left pane of the Local Security Policy Editor window, navigate to Account Policies and select Account Lockout Policy.
2. A list of account lockout policies should appear on the right screen. To change an account's lockout duration, select the policy titled “Account lockout duration."
3. Click Edit.

Step 3: Change Account Lockout Duration
Once you've accessed the individual account lockout duration policy, it's time to change the lockout duration. To change the account lockout duration, follow these steps:
1. In the “Account lockout duration” window, select the radio button next to the “Define this policy setting” option.
2. Enter the desired lockout duration in minutes (between 1 and 99999) in the minutes box.
3. Click OK to save and apply the changes.

Conclusion:
Frequent lockouts can be frustrating and time-consuming, especially when you're in a hurry. Luckily, Windows 11 users can easily adjust account lockout duration to reduce the occurrence of unnecessary lockouts and unlock the secret to longer login times. By following the steps outlined above, you can customize your account lockout duration and enjoy faster and more convenient login processes.

{{< youtube hw4ZUnm4kuM >}} 



When Account Lockout policies were set on Windows 11, the operating system prevents others from entering the password after several wrong login attempts and blocks the user account for 10 minutes.
After 10 minutes of lockout, the counter was automatically reset, giving users another 10 chances to enter the password or PIN. You can modify that 10 minutes of duration in easy steps.
Also Read: How to Password Protect Folders in Windows 11

 
## Best Methods to Change Account Lockout Duration in Windows 11


While it’s not recommended to change the Account Lockout duration in Windows 11, you may still want to increase or decrease the duration for specific reasons. Hence, below, we have shared a step-by-step guide on changing account lockout duration in Windows 11. Let’s check out.

 
### 1) Change Account Lockout Duration via Local Group Policy


This method will show you how to change account lockout duration via Local Group Policy Editor. Follow some of the simple steps we have shared below.
1. First, click on the Windows 11 search and type in Local Group Policy. Next, open the Group Policy Editor from the list of matching results.

2. On the Local Group Policy Editor, navigate to the following path:
Computer Configuration > Windows Settings > Security Settings > Account Policies > Account Lockout Policy

3. You will find a few policies in the Account Lockout Policy folder. You need to double-click the Account lockout duration policy on the right.

4. On the Account lockout duration properties, switch to the Local Security Setting tab.

5. Now, set the time (in minutes) for the account lockout. Once done, click on the Apply button and then on Ok.

That’s it! This is how you can change the account lockout duration in your Windows 11 computer.

 
### 2) Change the Account Lockout Duration via Command Prompt


You can even use the Command Prompt utility to change the account lockout duration. For that, follow some of the simple steps we have shared below.
1. Click on the Windows 11 search and type in Command Prompt. Next, open the Command Prompt utility from the list of matching results.

2. On the Command Prompt, type in net accounts and hit the Enter button.

3. This will reveal the Account Lockout policy. You need to check the Lockout duration (minutes): to check the current account lockout time.

4. Now, if you want to increase or decrease the Account Lockout duration, enter the following command:

Important: Make sure to replace<number> with the time you want to set. You can set the time between 0 and 99999 minutes. Setting it to 0 will disable the account lockout.
That’s it! You can change the account lockout duration in Windows 11 via the Command Prompt.
Also Read: How to Format a Hard Drive or SSD in Windows 11
So, that’s all about changing the account lockout duration in Windows 11. You can follow these two methods to modify the time limit for account lock. If you need more help with the Account lockout duration policy, let us know in the comments below.




