# Windows Backup
##

KB5030211 Patch Tuesday update added “Windows Backup” to Windows 10, a new app which cannot be uninstalled.


Windows 10 September 2023 Update (KB5030211) started shipping on September 12 with many changes, including a new “Windows Backup” feature. This new app lets you back up and restore your system, but there’s a twist – Microsoft is installing the unremovable app on enterprise systems.

Windows Backup is not a bad app or something you’d hate, as it’s helpful in many ways. Microsoft can back up your files, apps, system settings, login details, Edge settings, third-party browsers, and more. The backed-up data can be restored on a new device or fresh installation of the operating system. Everything is linked to Microsoft’s account.

If you do not care about losing some Windows features, here’s how to uninstall Windows Backup:

Open Start Menu or Windows Search.
Search for PowerShell and run it with administrative rights.
In PowerShell, run the following command:

Remove-WindowsPackage -Online -PackageName “Microsoft-Windows-UserExperience-Desktop-Package~31bf3856ad364e35~amd64~~10.0.19041.3393”

Reboot.