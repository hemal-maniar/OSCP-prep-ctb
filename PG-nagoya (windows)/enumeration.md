**sudo nmap \-sS \-sV \-\-script=default \-Pn 192\.168\.160\.21
**PORT     STATE SERVICE           VERSION
53/tcp   open  domain            Simple DNS Plus
80/tcp   open  http              Microsoft IIS httpd 10\.0
|\_http\-server\-header: Microsoft\-IIS/10\.0
|\_http\-title: Nagoya Industries \- Nagoya
88/tcp   open  kerberos\-sec      Microsoft Windows Kerberos \(server time: 2024\-04\-13 18:43:43Z\)
135/tcp  open  msrpc             Microsoft Windows RPC
139/tcp  open  netbios\-ssn       Microsoft Windows netbios\-ssn
389/tcp  open  ldap              Microsoft Windows Active Directory LDAP \(Domain: nagoya\-industries\.com0\., Site: Default\-First\-Site\-Name\)
445/tcp  open  microsoft\-ds?
464/tcp  open  kpasswd5?
593/tcp  open  ncacn\_http        Microsoft Windows RPC over HTTP 1\.0
636/tcp  open  ldapssl?
3268/tcp open  ldap              Microsoft Windows Active Directory LDAP \(Domain: nagoya\-industries\.com0\., Site: Default\-First\-Site\-Name\)
3269/tcp open  globalcatLDAPssl?
3389/tcp open  ms\-wbt\-server     Microsoft Terminal Services
| rdp\-ntlm\-info: 
|   Target\_Name: NAGOYA\-IND
|   NetBIOS\_Domain\_Name: NAGOYA\-IND
|   NetBIOS\_Computer\_Name: NAGOYA
|   DNS\_Domain\_Name: nagoya\-industries\.com
|   DNS\_Computer\_Name: nagoya\.nagoya\-industries\.com
|   DNS\_Tree\_Name: nagoya\-industries\.com
|   Product\_Version: 10\.0\.17763
|\_  System\_Time: 2024\-04\-13T18:43:55\+00:00
|\_ssl\-date: 2024\-04\-13T18:44:35\+00:00; \+3s from scanner time\.
| ssl\-cert: Subject: commonName=nagoya\.nagoya\-industries\.com
| Not valid before: 2024\-04\-12T18:43:18
|\_Not valid after:  2024\-10\-12T18:43:18
Service Info: Host: NAGOYA; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2\-time: 
|   date: 2024\-04\-13T18:44:00
|\_  start\_date: N/A
|\_clock\-skew: mean: 2s, deviation: 0s, median: 2s
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled and required

**nmap \-sV \-Pn \-p\- \-v 192\.168\.160\.21
**PORT      STATE SERVICE       VERSION
53/tcp    open  domain        Simple DNS Plus
80/tcp    open  http          Microsoft IIS httpd 10\.0
88/tcp    open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-13 18:45:35Z\)
389/tcp   open  ldap          Microsoft Windows Active Directory LDAP \(Domain: nagoya\-industries\.com0\., Site: Default\-First\-Site\-Name\)
445/tcp   open  microsoft\-ds?
464/tcp   open  kpasswd5?
593/tcp   open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp   open  tcpwrapped
3268/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: nagoya\-industries\.com0\., Site: Default\-First\-Site\-Name\)
3269/tcp  open  tcpwrapped
5985/tcp  open  http          Microsoft HTTPAPI httpd 2\.0 \(SSDP/UPnP\)
9389/tcp  open  mc\-nmf        \.NET Message Framing
49666/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49669/tcp open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
49670/tcp open  msrpc         Microsoft Windows RPC
49673/tcp open  msrpc         Microsoft Windows RPC
49683/tcp open  msrpc         Microsoft Windows RPC
49690/tcp open  msrpc         Microsoft Windows RPC
49709/tcp open  msrpc         Microsoft Windows RPC
Service Info: Host: NAGOYA; OS: Windows; CPE: cpe:/o:microsoft:windows