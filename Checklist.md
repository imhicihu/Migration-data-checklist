* Attach every involved device in the procedure to a [UPS](https://en.wikipedia.org/wiki/Uninterruptible_power_supply), to prevent power failure
* Verify (and fix) any erroneous computer's date & time
* Verify status of internal battery
* Verify if the computer is _under_ password. The same goes for _inner_ Windows session(s)
* Turn off the access to internet: 
     - turn off wifi connection 
     - detach LAN access 
* Verify the health of the disk drive, then defrag it. Both actions can be done with [Defragler](https://www.ccleaner.com/defraggler)
* Verify the health of the external hard disk, then defrag it. Both actions can be done with [Defragler](https://www.ccleaner.com/defraggler)
* Verify the health of the pen drive, then defrag it. Both actions can be done with [Defragler](https://www.ccleaner.com/defraggler)
* Update to the latest definitions of the antivirus resident on the (primary) computer
* Do a full scan with the antivirus on the operating system, files, _etc_. The same goes for the hard disk or pen drive
    - If there are _virus_: notify it!
* File sharing: `off` during diagnostic, defrag or copy/move of files between devices
* Notifications: `off` during diagnostic, defrag or copy/move of files between devices
* Close all the software in memory or actually running during the procedure of copy/move files between devices
* Install backup software to migrate between both operating systems or computers. 
* Create `.ISO` images for folders that is mandatory to maintain the framework of folders (ie. folders nested inside another folders). In a nutsell, create full _mirror_ images of folders and files (even with _hidden_ attributes)
* Along the process of making iso images in Windows environments, some warns will be shown:
    - maximum filename length in NTFS formatted hard drives (Windows XP and Windows Vista): 260 characters as it fullest. See this [Microsoft Report](https://docs.microsoft.com/en-us/dotnet/api/system.io.pathtoolongexception?redirectedfrom=MSDN&view=netframework-4.8).
    - In Windows 10, the maximum filename length can be overriden it offers an option to ignore the `MAX_PATH` issue by overriding a group policy entry enabling NTFS long paths under `Computer Configuration` -> `Admin Templates` -> `System` -> `FileSystem:` –
    
* Backup to a "healthy" external disk drive, pendrives, dvd or blu-ray discs