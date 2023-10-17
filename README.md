# QuicKitty

This is a quick script to set up and run HardeningKitty, a Windows hardening script. Check out their repository: https://github.com/scipag/HardeningKitty

Primarially made for script kiddies and beginners to quickly implement in competitions (everyone has to start somewhere!).

  
Just open powershell (not even as administrator) by using the Win+r shortcut, typing "powershell", and pressing enter. Now, you're good to go!

These standalone commands must be run before the script can be used. They powershell as admin and enable running unsigned scripts.

Copy-paste into Powershell:
```
Start-process powershell -Verb runAs
```
Now, copy-paste this command into the new poweshell window:
```
set-executionpolicy remotesigned -Force
```
