# updateEverything for Windows
Script automatically checks for, downloads and installs all updates (and reboots if needed) on Windows OSes without your presence.
The script uses Windows Update Agent API. The script was tested on Windows 7 and Windows 8.1 only, but it should work on all versions from Windows XP on.
# Table of contents
- [Manual installation](https://github.com/kv1dr/updateEverything-for-Windows/blob/master/README.md#manual-installation)
- [Automatical installation](https://github.com/kv1dr/updateEverything-for-Windows/blob/master/README.md#automatical-installation)
- [Recommended actions before running script](https://github.com/kv1dr/updateEverything-for-Windows/blob/master/README.md#recommended-actions-before-running-script)

# Manual installation
1. Select "Donwload ZIP" button on the right side of this page
2. Extract content from the ZIP to any location
3. Right click on the "updateEverything.bat" file and choose "Create shortcut"
4. Right click on the newly created shortcut and choose "Properties"
5. Go to the "Shortcut" tab and select "Advanced..." button
6. Check "Run as Administrator"
7. Move the shortcut to "C:\Users\username\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup" where username is your username and C is the disk you have installed Windows on.
8. Run shortcut and leave computer alone to finish
9. You will be notified when Windows is fully updated.
10. When Windows is fully updated, temove the shortcut from the folder mentoined above, to prevent script from running again every boot.
# Automatical installation
WORK IN PROGRESS
# Recommended actions before running script:
- You must have only one account and this one account should NOT have any password for Windows to automatically login and rerun script after reboot. When Windows is fully updated, you can add other accounts and passwords if you want to.
- It's recommended to close all other programs and leave computer alone while this script is running.
- Turn off automatic sleeping of computer while this script is running. (How to do that: http://answers.microsoft.com/en-us/windows/forum/windows_7-performance/how-do-i-stop-my-computer-from-going-to-sleep/c24555c0-3d73-e011-8dfc-68b599b31bf5 ). You can turn it back on, when Windows is fully updated.
- This script is recommended for new installation of Windows(when you have a lot of updates avaliable for installation).
- It's recommended to turn off Windows Updates while script is running(Turn it back on, when script finishes)
