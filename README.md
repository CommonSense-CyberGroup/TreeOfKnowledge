# TreeOfKnowledge

PowerShell Script for information gathering


The initial purpose/thought behind this script was to be used with as a USB PenTest simulation with something like the P4wnp1 ALOA where this will run as soon as the device is plugged into the machine. It is meant to be quick and upload the data to an online FTP share (or save it locally to the USB device). This script needs to be run while the PC is unlocked and a user is logged in. We do not yet have the functionality built in to unlock a Windows PC. 


The user is able to comment/uncomment functions that they wish to run against the machine. Some are dependant on one another and others require admin elevation so read the comments carefully!


------

Legal Disclaimer:
    The use of code contained in this repository, either in part or in its totality, for engaging targets without prior mutual consent is illegal. 
    It is the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible 
    for misuses or damages caused by any code contained in this repository in any event that, accidentally or otherwise, it comes to be utilized 
    by a threat agent or unauthorized entity as a means to compromise the security, privacy, confidentiality, integrity, and/or availability of 
    systems and their associated resources. In this context the term "compromise" is henceforth understood as the leverage of exploitation of known or 
    unknown vulnerabilities present in said systems, including, but not limited to, the implementation of security controls, human- or electronically-enabled.

    The use of this code is only endorsed by the developers in those circumstances directly related to educational environments or authorized 
    penetration testing engagements whose declared purpose is that of finding and mitigating vulnerabilities in systems, limiting their exposure 
    to compromises and exploits employed by malicious agents as defined in their respective threat models.
    
------


## To Do:
- Add SCP capability for uploading files securely to an available host (https://mcpmag.com/articles/2018/07/19/transfer-files-via-scp-with-powershell.aspx)
