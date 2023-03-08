---
title: "Windows 11 Users Beware! Learn how to Secure Your PC with this Simple Hack to Block Access to Settings App!"
ShowToc: true 
date: "2022-11-12"
author: "Debra Scott"
---
*****
# Windows 11 Users Beware! Learn how to Secure Your PC with this Simple Hack to Block Access to Settings App!

If you are a Windows 11 user, you must be aware of the sensitive information stored on your PC. To secure your PC and prevent unauthorized access to your system, it is essential to take measures. One of the most vital steps in securing your PC is limiting access to the Settings app. The Settings app is an essential tool for making system changes and checking the status of critical applications. However, if a hacker gains access to the Settings app, they can easily manipulate your system settings and compromise your device's security.

In this article, we will discuss how to block access to the Settings app on your Windows 11 PC to prevent unauthorized changes and keep your system secure.

## Why Should You Block Access to the Settings App?

Blocking access to the Settings app will prevent unauthorized users from making critical changes to your device. For example, someone with malicious intent could use the Settings app to change your device's account password, disable your antivirus, change your internet settings, or install potentially harmful third-party software. If you limit access to the Settings app, these security risks can be avoided.

## How to Block Access to the Settings App on Windows 11

Windows 11 provides several ways to block access to the Settings app. Here, I will introduce two simple methods:

### Method 1: Use Group Policy Editor

The Group Policy Editor is a powerful tool that is used to manage many different aspects of your Windows 11 PC. To block access to the Settings app using the Group Policy Editor, follow these steps:

1. Press the "Windows key + R" to open the Run dialog box.
2. Type "gpedit.msc" and press "Enter" to open the Group Policy Editor.
3. In the left-hand pane, navigate to "User Configuration > Administrative Templates > Control Panel."
4. Locate the "Prohibit access to Control Panel and PC settings" policy.
5. Double-click on the policy to open its properties.
6. Check the "Enabled" option and click "Apply" and "OK."

After completing these steps, the Settings app will be disabled, and any attempt to access it will be blocked.

### Method 2: Use Registry Editor

The Registry Editor is another powerful tool that is often used to edit the system registry. To block access to the Settings app using the Registry Editor, follow these steps:

1. Press the "Windows key + R" to open the Run dialog box.
2. Type "regedit" and press "Enter" to open the Registry Editor.
3. In the left-hand pane, navigate to "HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer."
4. Right-click on "Explorer" and select "New > DWORD (32-bit) Value."
5. Name the new value "NoControlPanel."
6. Double-click on the "NoControlPanel" value and set the value data to "1."
7. Click "OK."

After completing these steps, the Settings app will be disabled, and any attempt to access it will be blocked.

## Conclusion

In conclusion, securing your PC and preventing access to the Settings app is a crucial step to ensure the safety of your system. By limiting access to the Settings app, you can prevent unauthorized access and changes to your device's settings, ensuring that your data stays safe and secure. The two methods outlined in this article can help you easily block access to the Settings app on your Windows 11 PC.

{{< youtube aJ37b2-OhH8 >}} 



Suppose you block access to the Settings app on Windows 11. In that case, you won’t have to worry about anyone making unnecessary changes to your computer or messing with your network settings without your permission.
On Windows 11, you can block settings access for specific users, but you need to edit the Registry file or change the Local Group Policy. Hence, if you are interested in blocking Settings access on Windows 11, you might find this article very helpful.

 
## Steps to Block Access to the Settings App in Windows 11


This article will list the two best methods to block settings access on Windows 11. Since the methods require Registry editing, make sure to follow the steps carefully, or else you could end up inviting problems to your PC.

 
### 1) Block Access to Settings on Windows 11 via Registry


In this method, we will use the Registry Editor to block Settings access on Windows 11. Follow some of the simple steps we have shared below.
1. First, click on the Windows 11 Search and type in Regedit. Next, open the Registry Editor from the list of options.

2. On the Registry Editor, navigate to the path:
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer

3. Now, right-click on the Explorer folder and select New > DWORD (32-Bit) Value.

4. Name the new key NoControlPanel and hit the Enter button.

5. Once done, double click on the NoControlPanel DWORD key and enter 1 on the Value Data field. Next, click on the Ok button.

6. Once done, close the Registry Editor and open the Settings app. You will see an error prompt like this.

7. If you wish to enable the Settings app, set 0 on the Value data field in Step 5.

That’s it! You are done. This is how you can block access to the Settings app on Windows 11.

 
### 2) Disable Windows 11 Settings App via Local Group Policy


We will use the Local Group Policy Editor to disable the Windows 11 Settings access in this method. Follow some of the simple steps we have shared below.
1. First, click on the Windows 11 Search and type in Local Group Policy. Next, open the Local Group Policy Editor from the list.

2. On the Local Group Policy Editor, navigate to the:
User Configuration > Administrative Templates > Control Panel

3. Double click on the Prohibit access to Control Panel and PC Settings on the right pane.

4. Select Enabled and click on the Ok button on the Window that appears.

5. Now, nothing will happen if anyone tries to access the Settings app. This will also block access to the Control Panel.
6. If you wish to revert the changes, select ‘Not Configured’ in Step 4.

That’s it! You are done. This is how you can block users from accessing Settings in Windows 11 via Local Group Policy Editor.
So, these are the two best ways to block users from accessing the Settings app on Windows 11. If you are the admin of a Windows 11 PC, you can follow these methods to prevent other user accounts from accessing the Settings.




