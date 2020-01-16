# Win10, Server, VM Initial Configuration PowerShell
 Config everything automatically and saves hours of time

Simply select the ps1 files most related to what you're doing and then execute it after initial Windows install completes.

# How to run script: Easy Mode
1) Open PowerShell as Administrator
2) Browse to: https://github.com/DranKof/Windows-OneConfig  *or use thumbdrive with ps1 file
3) Copy, paste, wait, skim results, done

Optionally, if it's a fresh install of Windows 10:

4) Run the Fresh Install script, too

# How to customize it?
It's super easy! No functions, no questions, just comment-uncomment.
Also, here is a link for more, probably much more frequently updated code:
<br>(THE SOURCE) https://github.com/Disassembler0/Win10-Initial-Setup-Script/blob/master/Win10.psm1

# Why is there a separate "Fresh Install" script?
To unpin everything and uninstall OneDrive. You only want to do this at the very beginning.

1) The script unpins everything in the start menu and taskbar. You don't want to do that on a machine that you're in the middle of using, but you do want to do it when you have 20 bloatware links in your fresh Windows 10 installation.

2) You also want to uninstall OneDrive only once at the very beginning. If you use it, when you reinstall you can move the share folder where you actually want it. If you don't use OneDrive, then you just saved time uninstalling it.

# Why not directly execute the ps1 (powershell) script?
You'd either have to reduce computer security and/or too many mouse clicks.

If you're interested, there's a nice explanation of how to use a fully-featured txtfile customizable version here:
https://github.com/alirobe/Reclaim-Windows10

# Windows Server 2016 or 2019?
As far as I know, both?

# Future plans?
  - Unpin Documents and Pictures from Quick Access (it should have Desktop/Downloads only)
  - Forever testing.
  ? Maybe set "Downloads" system folder location to "C:\Downloads"
  ? Maybe add shortcut to desktop that goes straight to "Control Panel\Network and Internet\Network Connections" named "Adapters"

# Special Thanks to:

Disassembler0 for original script and many, many updates:
<br>https://github.com/Disassembler0/Win10-Initial-Setup-Script/blob/master/Win10.psm1
 - Finding all this stuff out is torture. Really good job.

alirobe for Reclaim Windows 10 version, otherwise I would never have heard about it:
<br>https://github.com/alirobe/Reclaim-Windows10/blob/master/Reclaim-Windows10/Reclaim-Windows10.psm1
 - Great second take on best practices.
