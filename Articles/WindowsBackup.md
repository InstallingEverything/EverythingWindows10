# Windows Backup

Windows 10 September 2023 Update (KB5030211) started shipping on September 12 with many changes, including a new “Windows Backup” feature.

The new app allows backupo and full restore of your system.

Some poeple may not want this installed on your system and here is the instructions on how to remove the app.

Open Start Menu or Windows Search.

Search for PowerShell and Right click and run with administrative rights.

In PowerShell, run the following command:

Remove-WindowsPackage -Online -PackageName “Microsoft-Windows-UserExperience-Desktop-Package~31bf3856ad364e35~amd64~~10.0.19041.3393”

Reboot your system.

KB5030211 has now been uninsalled.

