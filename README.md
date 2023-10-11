# QuicKitty

This is a quick script to set up and run HardeningKitty, a Windows hardening script. 
Specifically made for fast implementation in competitions, specifically for script kiddies.
Just open powershell (not even as administrator) and you're good to go!

These standalone commands must be run before the script can be used. They powershell as admin and enable running unsigned scripts.
Copy-paste into Powershell:

# Start-process powershell -Verb runAs
# set-executionpolicy remotesigned
