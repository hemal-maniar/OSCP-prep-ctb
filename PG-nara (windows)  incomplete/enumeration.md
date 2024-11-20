**sudo nmap \-sS \-sV \-\-script=default 192\.168\.246\.30**
PORT     STATE SERVICE       VERSION
53/tcp   open  domain        Simple DNS Plus
88/tcp   open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-05 01:00:37Z\)
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: nara\-security\.com0\., Site: Default\-First\-Site\-Name\)
|\_ssl\-date: TLS randomness does not represent time
| ssl\-cert: Subject: commonName=Nara\.nara\-security\.com
| Subject Alternative Name: othername: 1\.3\.6\.1\.4\.1\.311\.25\.1::\<unsupported\>, DNS:Nara\.nara\-security\.com
| Not valid before: 2023\-07\-30T14:09:26
|\_Not valid after:  2024\-07\-29T14:09:26
445/tcp  open  microsoft\-ds?
464/tcp  open  kpasswd5?
593/tcp  open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp  open  ssl/ldap      Microsoft Windows Active Directory LDAP \(Domain: nara\-security\.com0\., Site: Default\-First\-Site\-Name\)
| ssl\-cert: Subject: commonName=Nara\.nara\-security\.com
| Subject Alternative Name: othername: 1\.3\.6\.1\.4\.1\.311\.25\.1::\<unsupported\>, DNS:Nara\.nara\-security\.com
| Not valid before: 2023\-07\-30T14:09:26
|\_Not valid after:  2024\-07\-29T14:09:26
|\_ssl\-date: TLS randomness does not represent time
3268/tcp open  ldap          Microsoft Windows Active Directory LDAP \(Domain: nara\-security\.com0\., Site: Default\-First\-Site\-Name\)
| ssl\-cert: Subject: commonName=Nara\.nara\-security\.com
| Subject Alternative Name: othername: 1\.3\.6\.1\.4\.1\.311\.25\.1::\<unsupported\>, DNS:Nara\.nara\-security\.com
| Not valid before: 2023\-07\-30T14:09:26
|\_Not valid after:  2024\-07\-29T14:09:26
|\_ssl\-date: TLS randomness does not represent time
3269/tcp open  ssl/ldap      Microsoft Windows Active Directory LDAP \(Domain: nara\-security\.com0\., Site: Default\-First\-Site\-Name\)
| ssl\-cert: Subject: commonName=Nara\.nara\-security\.com
| Subject Alternative Name: othername: 1\.3\.6\.1\.4\.1\.311\.25\.1::\<unsupported\>, DNS:Nara\.nara\-security\.com
| Not valid before: 2023\-07\-30T14:09:26
|\_Not valid after:  2024\-07\-29T14:09:26
|\_ssl\-date: TLS randomness does not represent time
3389/tcp open  ms\-wbt\-server Microsoft Terminal Services
| ssl\-cert: Subject: commonName=Nara\.nara\-security\.com
| Not valid before: 2024\-04\-04T00:59:50
|\_Not valid after:  2024\-10\-04T00:59:50
| rdp\-ntlm\-info: 
|   Target\_Name: NARASEC
|   NetBIOS\_Domain\_Name: NARASEC
|   NetBIOS\_Computer\_Name: NARA
|   DNS\_Domain\_Name: nara\-security\.com
|   DNS\_Computer\_Name: Nara\.nara\-security\.com
|   DNS\_Tree\_Name: nara\-security\.com
|   Product\_Version: 10\.0\.20348
|\_  System\_Time: 2024\-04\-05T01:01:16\+00:00
|\_ssl\-date: 2024\-04\-05T01:01:56\+00:00; \+4s from scanner time\.
Service Info: Host: NARA; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
|\_clock\-skew: mean: 3s, deviation: 0s, median: 3s
| smb2\-time: 
|   date: 2024\-04\-05T01:01:18
|\_  start\_date: N/A
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled and required


**nmap \-sV \-Pn \-p\- \-v 192\.168\.246\.30**
PORT      STATE SERVICE       VERSION
53/tcp    open  domain        Simple DNS Plus
88/tcp    open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-05 01:01:56Z\)
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp   open  ldap          Microsoft Windows Active Directory LDAP \(Domain: nara\-security\.com0\., Site: Default\-First\-Site\-Name\)
445/tcp   open  microsoft\-ds?
464/tcp   open  kpasswd5?
593/tcp   open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp   open  ssl/ldap      Microsoft Windows Active Directory LDAP \(Domain: nara\-security\.com0\., Site: Default\-First\-Site\-Name\)
3268/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: nara\-security\.com0\., Site: Default\-First\-Site\-Name\)
3269/tcp  open  ssl/ldap      Microsoft Windows Active Directory LDAP \(Domain: nara\-security\.com0\., Site: Default\-First\-Site\-Name\)
3389/tcp  open  ms\-wbt\-server Microsoft Terminal Services
5985/tcp  open  http          Microsoft HTTPAPI httpd 2\.0 \(SSDP/UPnP\)
9389/tcp  open  mc\-nmf        \.NET Message Framing
49664/tcp open  msrpc         Microsoft Windows RPC
49667/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49682/tcp open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
49683/tcp open  msrpc         Microsoft Windows RPC
49690/tcp open  msrpc         Microsoft Windows RPC
49694/tcp open  msrpc         Microsoft Windows RPC
49708/tcp open  msrpc         Microsoft Windows RPC
49722/tcp open  msrpc         Microsoft Windows RPC

-  smbclient \-N \-L \\\\192\.168\.246\.30                              

Sharename       Type      Comment
\-\-\-\-\-\-\-\-\-       \-\-\-\-      \-\-\-\-\-\-\-
ADMIN$          Disk      Remote Admin
C$              Disk      Default share
IPC$            IPC       Remote IPC
nara            Disk      company share
NETLOGON        Disk      Logon server share 
SYSVOL          Disk      Logon server share

-  /kerbrute userenum /usr/share/seclists/Usernames/xato\-net\-10\-million\-usernames\.txt \-\-domain nara\-security\.com \-\-dc 192\.168\.246\.30 
-  2024/04/04 21:16:34 \>  \[\+\] VALID USERNAME:       nara@nara\-security\.com

-  tried everything but nothing worked
-  