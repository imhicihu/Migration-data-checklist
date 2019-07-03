# Procedures (for internal use)
* Foresee the *worst* scenario as possible (main & target computer)
* Verify technical status of every device that will be part of the backup process: hard disk, blu-ray recorder, dvd recorder, pen-drive.
* Check the [speed of the hard disk](https://hdd.userbenchmark.com/Software): append time at discretion along the process, so verify time schedule between both parties
* Attach every involved device in the procedure to a [UPS](https://en.wikipedia.org/wiki/Uninterruptible_power_supply), to prevent power failure
* Verify (and fix) any erroneous computer's date & time
* Verify status of internal batteries (main & target computer)
* Verify if the computer is _under_ password. The same goes for _internal_ Windows session(s) (main & target computer)
* Turn off the access to internet: 
     - turn off wifi connection 
     - detach LAN access 
* Verify the health of the disk drive, then defrag it. Both actions can be done with [Defragler](https://www.ccleaner.com/defraggler)
* Verify the health of the external hard disk, then defrag it. Both actions can be done with [Defragler](https://www.ccleaner.com/defraggler)
* Verify the health of the pen drive, then defrag it. Both actions can be done with [Defragler](https://www.ccleaner.com/defraggler)
* Update to the latest definitions of the antivirus resident on the (primary) computer
* Do a full scan with the antivirus on the operating system, files, _etc_. The same goes for the hard disk or pen drive
    - If there are _virus_: notify it!
* Turn `off` `File sharing` during diagnostic, defrag or copy/move of files between devices
* Turn `off` Microsoft Windows's built-in `Firewall` during diagnostic, defrag or copy/move of files between devices
* Turn `off` Microsoft Windows's built-in `Notifications` during diagnostic, defrag or copy/move of files between devices
* Turn `off` Microsoft Windows's built-in `Printer sharing` during diagnostic, defrag or copy/move of files between devices
* Turn `off` Microsoft Windows's built-in `Remote login` during diagnostic, defrag or copy/move of files between devices
* Turn `off` Microsoft Windows's built-in `Screen sharing` during diagnostic, defrag or copy/move of files between devices
* For every browser installed and to enable the backup of bookmarks, passwords, custom settings:
    - create an account, _ie._ Mozilla Firefox offers this [portal](https://www.mozilla.org/en-US/firefox/accounts/) to sign-in, then you will can collect all the browsing's history, passwords, tabs opened in multiple devices, etc. Actually, every major browser in the market offers this feature: [Vivaldi](https://login.vivaldi.net/profile/), [Google Chrome](https://chrome.google.com/sync), [Opera](https://auth.opera.com/account/login), etc. In case of Safari the official method can be found [here](https://support.apple.com/en-us/HT203519#windows).  
* Close all the software in memory or actually running during the procedure of copy/move files between devices
* Verify backup's software compatibility between operating systems 
* Install backup software to migrate between both operating systems or computers
* Verify software compatibility between different operating systems, with a _focus_ between 32 vs 64 bits systems. So, Some older software demands only 32 bits environments. So, an option is create a custom [Docker image](https://www.howtoforge.com/tutorial/building-and-publishing-custom-docker-images/) or some kind of _sandboxed_ virtual environment: [VirtualBox](https://www.virtualbox.org/), [Vagrant](https://www.vagrantup.com/), [Windows XP Mode](https://www.microsoft.com/en-us/download/details.aspx?id=8002), etc.
* Verify compatibility between file structure acording operating systems's
* Verify hard drive format status: `NTFS` or `FAT`
* Create `.ISO` images for folders that is *mandatory* to maintain the framework of folders (ie. folders nested inside another folders). In a nutsell, create full _mirror_ images of folders and files (even with _hidden_ attributes)
* Along the process of making iso images in Windows environments, some warns will be shown:
    - maximum filename length in NTFS formatted hard drives (Windows XP and Windows Vista): 260 characters as it fullest. See this [Microsoft Report](https://docs.microsoft.com/en-us/dotnet/api/system.io.pathtoolongexception?redirectedfrom=MSDN&view=netframework-4.8).
    - In Windows 10, the maximum filename length can be overriden it offers an option to ignore the `MAX_PATH` issue by overriding a group policy entry enabling NTFS long paths under `Computer Configuration` -> `Admin Templates` -> `System` -> `FileSystem:`
    - maximum path length limitation on Windows is [260 characters](https://docs.microsoft.com/en-us/windows/desktop/FileIO/naming-a-file)
    - ![nested_folders.png](https://bitbucket.org/repo/jgXpxpx/images/2171080336-nested_folders.png)
* Backup to a "healthy" external disk drive, pendrives, dvd or blu-ray discs
* Backup custom settings (if it it possible) for those software that is *mandatory* to run in the target computer

# Legal:
* All other trademarks are the property of their respective owners.
* Windows. Windows 10, Windows XP, Windows Vista are registered trademark of Microsoft Corporation in the United States and/or other countries.