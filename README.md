# Windows+R (Run box)

```secpol.msc```

![image](https://user-images.githubusercontent.com/58542375/223962949-a9626aaa-2848-438f-82c2-212d7783d005.png)

### User Rights Assignment

![image](https://user-images.githubusercontent.com/58542375/223963811-273d0d73-376e-4e85-ba10-30cbd869aec3.png)

```
Policy	Security Setting
Access Credential Manager as a trusted caller	
Access this computer from the network	Everyone,Administrators,Users,Backup Operators
Act as part of the operating system	
Add workstations to domain	
Adjust memory quotas for a process	LOCAL SERVICE,NETWORK SERVICE,Administrators
Allow log on locally	__vmware__,Guest,Administrators,Users,Backup Operators
Allow log on through Remote Desktop Services	Administrators,Remote Desktop Users
Back up files and directories	Administrators,Backup Operators
Bypass traverse checking	Everyone,LOCAL SERVICE,NETWORK SERVICE,Administrators,Users,Backup Operators
Change the system time	LOCAL SERVICE,Administrators
Change the time zone	LOCAL SERVICE,Administrators,Users
Create a pagefile	Administrators
Create a token object	
Create global objects	LOCAL SERVICE,NETWORK SERVICE,Administrators,SERVICE
Create permanent shared objects	
Create symbolic links	Administrators
Debug programs	Administrators
Deny access to this computer from the network	Guest
Deny log on as a batch job	
Deny log on as a service	
Deny log on locally	Guest
Deny log on through Remote Desktop Services	
Enable computer and user accounts to be trusted for delegation	
Force shutdown from a remote system	Administrators
Generate security audits	LOCAL SERVICE,NETWORK SERVICE
Impersonate a client after authentication	LOCAL SERVICE,NETWORK SERVICE,Administrators,SERVICE
Increase a process working set	Users
Increase scheduling priority	Administrators,Window Manager\Window Manager Group
Load and unload device drivers	Administrators
Lock pages in memory	
Log on as a batch job	Administrators,Backup Operators,Performance Log Users
Log on as a service	NT SERVICE\ALL SERVICES
Manage auditing and security log	Administrators
Modify an object label	
Modify firmware environment values	Administrators
Obtain an impersonation token for another user in the same session	Administrators
Perform volume maintenance tasks	Administrators
Profile single process	Administrators
Profile system performance	Administrators,NT SERVICE\WdiServiceHost
Remove computer from docking station	Administrators,Users
Replace a process level token	LOCAL SERVICE,NETWORK SERVICE
Restore files and directories	Administrators,Backup Operators
Shut down the system	Administrators,Users,Backup Operators
Synchronize directory service data	
Take ownership of files or other objects	Administrators
```

```compmgmt.msc```

![image](https://user-images.githubusercontent.com/58542375/223974098-e1d5f10f-5c6c-4e30-9eef-ce870fa665b2.png)

![image](https://user-images.githubusercontent.com/58542375/223974751-cdf6d782-545f-4914-843d-3fec4b48cb6c.png)

