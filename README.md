# TreeOfKnowledge

PowerShell Script for information gathering


The initial purpose/thought behind this script was to be used with as a USB PenTest simulation with something like the P4wnp1 ALOA where this will run as soon as the device is plugged into the machine. It is meant to be quick and upload the data to an online FTP share (or save it locally to the USB device). This script needs to be run while the PC is unlocked and a user is logged in. We do not yet have the functionality built in to unlock a Windows PC. 


The user is able to comment/uncomment functions that they wish to run against the machine. Some are dependant on one another and others require admin elevation so read the comments carefully!


This is strictly meant for testing and education purposes!


## To Do:
- Add SCP capability for uploading files securely to an available host (https://mcpmag.com/articles/2018/07/19/transfer-files-via-scp-with-powershell.aspx)
