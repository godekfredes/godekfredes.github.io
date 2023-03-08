---
title: "You Won't Believe How Easy It Is To Block Extension Installation In Microsoft Edge!"
ShowToc: true 
date: "2023-06-22"
author: "Mark Brown"
---
*****
# You Won't Believe How Easy It Is To Block Extension Installation In Microsoft Edge!

Are you tired of constantly seeing new extensions being installed in your Microsoft Edge browser? A cluttered browser is not only annoying, but it can also slow down your computer's performance. Fortunately, there's a simple solution to this problem - blocking extension installation!

Here's how to do it:

1. First, open Microsoft Edge and click on the three dots located in the top right corner of the browser. This will open the "Settings" menu.

2. Scroll down and click on "Extensions" in the left-hand sidebar. 

3. Next, toggle the switch next to "Allow extensions from other stores" to off. 

4. After that, you'll see a prompt asking you whether you want to turn off extension sideloading. Click on "Turn off."

5. That's it! Now, only extensions from the Microsoft Store will be allowed to be installed in your browser.

By blocking extension installation, you'll not only keep your browser free from unwanted clutter but also protect your computer from potentially harmful extensions. The Microsoft Store has strict guidelines for extensions, ensuring that they are safe and secure for users to download and use.

If you ever need to install an extension from a website that isn't the Microsoft Store, don't worry - you can easily re-enable extension installation by repeating the steps above and toggling the switch back on.

In conclusion, blocking extension installation in Microsoft Edge is incredibly easy and can go a long way in keeping your browser clean and secure. Give it a try today!

{{< youtube 09tm0-o4Vuo >}} 



Now, there could be various reasons why you would want to block extension installation on the Edge browser. Maybe you don’t want other users on your PC to install the extension or want to prevent unwanted extension installation by malicious apps & programs.
Also Read: How to Use Microsoft Edge Drop to Share Files Across Devices

 
## Steps to Block Extension Installation in Microsoft Edge


Whatever the reason, you can easily block extension installation in the Chrome browser. Below, we have shared a step-by-step guide on preventing installing extensions in the Microsoft Edge browser. Let’s check out.
1. First, click on the Windows 11 search bar and type in Registry Editor. Next, open Registry Editor from the list of matching results.

2. On the Registry Editor, navigate to the given path:
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge

3. If you don’t find the Edge folder, right-click on Microsoft and select New > Key. Name the new key Edge.
4. Now, right-click on the Edge key and select New > Key.

5. Name the new key as ExtensionInstallBlocklist

6. Now, right-click on the ExtensionInstallBlocklist and select New > String Value.

7. Name the new String (REG_SZ) key as 1.

8. Double click on the 1 String (REG_SZ) on the right pane, and on the value data field, enter *.

9. Once done, click the Ok button and close the Registry Editor.
10. Now, open the Edge browser and try to install an extension. You will see a message “Your admin has blocked <extension name>” prompt.

The above method will also disable all active extensions on your Edge browser. If you want to enable extension installation, delete the ExtensionInstallBlocklist you created in Step 5.

Just like the Edge browser, you can block extension installation on the Google Chrome browser as well. So, if you use the Google Chrome web browser, you need to check out our guide How to Block Extension Installation in Chrome Browser.
So, that’s all about preventing extension installation in the latest Microsoft Edge browser. You should block extension installation if you often leave your PC unattended. If you are stuck somewhere in the steps and need help, let us know in the comments.




