# AdminToolBox
This is the place where I keep the code for my AdminToolBox PowerShell module.

Module contains bunch of functions that are helping with everyday taks. Functions are saved in individual folders and they are fetched inside psm1 file.


## Functions:

#### Get-ModuleHelp
This function was written to simplify using this module.
It loads all commands in module and shows them with numbers. Then you can enter function number and it will show you full help for that command.

This function can be used with any module.

#### Get-DiskSpace
Collect basic disk information from local and remote computers and export it to CSV.

#### New-DNSRecord
Create new A DNS record in AD integrated DNS zone using dnscmd tool.

#### Get-LocalAdmins
Get list of users and groups with local admin rights on local or remote computer. Export to CSV if needed.

#### Get-ADServersInfo
Collect basic information about specified servers or all servers found in Active Directory. Collected information is useful for having basic overview of where they are, what systems are they running and what are they used for.

#### StampFile
Add date and time stamp to end of file name. You can use it to rename existing file or copy file with date and time added to the end of original name.
