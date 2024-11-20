**sudo nmap \-sS \-sV \-\-script=default 192\.168\.199\.187**
PORT     STATE SERVICE       VERSION
53/tcp   open  domain        Simple DNS Plus
80/tcp   open  http          Apache httpd 2\.4\.48 \(\(Win64\) OpenSSL/1\.1\.1k PHP/8\.0\.7\)
|\_http\-server\-header: Apache/2\.4\.48 \(Win64\) OpenSSL/1\.1\.1k PHP/8\.0\.7
|\_http\-title: Access The Event
| http\-methods: 
|\_  Potentially risky methods: TRACE
88/tcp   open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-03\-27 21:18:19Z\)
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: access\.offsec0\., Site: Default\-First\-Site\-Name\)
445/tcp  open  microsoft\-ds?
464/tcp  open  kpasswd5?
593/tcp  open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp  open  tcpwrapped
3268/tcp open  ldap          Microsoft Windows Active Directory LDAP \(Domain: access\.offsec0\., Site: Default\-First\-Site\-Name\)
3269/tcp open  tcpwrapped
Service Info: Host: SERVER; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled and required
| smb2\-time: 
|   date: 2024\-03\-27T21:18:24
|\_  start\_date: N/A

**nmap \-sV \-Pn \-p\- \-v 192\.168\.199\.187**
PORT      STATE SERVICE       VERSION
53/tcp    open  domain        Simple DNS Plus
80/tcp    open  http          Apache httpd 2\.4\.48 \(\(Win64\) OpenSSL/1\.1\.1k PHP/8\.0\.7\)
88/tcp    open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-03\-27 21:20:03Z\)
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp   open  ldap          Microsoft Windows Active Directory LDAP \(Domain: access\.offsec0\., Site: Default\-First\-Site\-Name\)
445/tcp   open  microsoft\-ds?
464/tcp   open  kpasswd5?
593/tcp   open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp   open  tcpwrapped
3268/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: access\.offsec0\., Site: Default\-First\-Site\-Name\)
3269/tcp  open  tcpwrapped
5985/tcp  open  http          Microsoft HTTPAPI httpd 2\.0 \(SSDP/UPnP\)
9389/tcp  open  mc\-nmf        \.NET Message Framing
49666/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49673/tcp open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
49674/tcp open  msrpc         Microsoft Windows RPC
49677/tcp open  msrpc         Microsoft Windows RPC
49706/tcp open  msrpc         Microsoft Windows RPC

sudo nmap \-n \-sV \-\-script "ldap\* and not brute" 192\.168\.199\.187