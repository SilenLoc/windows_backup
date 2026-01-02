# windows_backup

### key backup

wmic path softwarelicensingservice get OA3xOriginalProductKey

Another simple method to find your Windows 11 product key is through the Windows Registry:

Press in + R, type regedit, and hit Enter.
Navigate to: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\SoftwareProtectionPlatform
Look for the "BackupProductKeyDefault" entry.


### Copy commands

xcopy [source] [destination] [options].
