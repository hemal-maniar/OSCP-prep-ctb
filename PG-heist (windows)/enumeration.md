**sudo nmap \-sS \-sV \-\-script=default \-Pn 192\.168\.190\.165**
PORT     STATE SERVICE       VERSION
53/tcp   open  domain        Simple DNS Plus
88/tcp   open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-09 17:48:12Z\)
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: heist\.offsec0\., Site: Default\-First\-Site\-Name\)
445/tcp  open  microsoft\-ds?
464/tcp  open  kpasswd5?
593/tcp  open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp  open  tcpwrapped
3268/tcp open  ldap          Microsoft Windows Active Directory LDAP \(Domain: heist\.offsec0\., Site: Default\-First\-Site\-Name\)
3269/tcp open  tcpwrapped
3389/tcp open  ms\-wbt\-server Microsoft Terminal Services
| ssl\-cert: Subject: commonName=DC01\.heist\.offsec
| Not valid before: 2023\-11\-14T04:56:57
|\_Not valid after:  2024\-05\-15T04:56:57
| rdp\-ntlm\-info: 
|   Target\_Name: HEIST
|   NetBIOS\_Domain\_Name: HEIST
|   NetBIOS\_Computer\_Name: DC01
|   DNS\_Domain\_Name: heist\.offsec
|   DNS\_Computer\_Name: DC01\.heist\.offsec
|   DNS\_Tree\_Name: heist\.offsec
|   Product\_Version: 10\.0\.17763
|\_  System\_Time: 2024\-04\-09T17:48:14\+00:00
|\_ssl\-date: 2024\-04\-09T17:48:54\+00:00; \+1s from scanner time\.
8080/tcp open  http          Werkzeug httpd 2\.0\.1 \(Python 3\.9\.0\)
|\_http\-server\-header: Werkzeug/2\.0\.1 Python/3\.9\.0
|\_http\-title: Super Secure Web Browser
Service Info: Host: DC01; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled and required
| smb2\-time: 
|   date: 2024\-04\-09T17:48:16
|\_  start\_date: N/A

**nmap \-sV \-Pn \-p\- \-v 192\.168\.190\.165**
PORT      STATE SERVICE       VERSION
53/tcp    open  domain        Simple DNS Plus
88/tcp    open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-09 17:50:33Z\)
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp   open  ldap          Microsoft Windows Active Directory LDAP \(Domain: heist\.offsec0\., Site: Default\-First\-Site\-Name\)
445/tcp   open  microsoft\-ds?
464/tcp   open  kpasswd5?
593/tcp   open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp   open  tcpwrapped
3268/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: heist\.offsec0\., Site: Default\-First\-Site\-Name\)
3269/tcp  open  tcpwrapped
3389/tcp  open  ms\-wbt\-server Microsoft Terminal Services
5985/tcp  open  http          Microsoft HTTPAPI httpd 2\.0 \(SSDP/UPnP\)
8080/tcp  open  http          Werkzeug httpd 2\.0\.1 \(Python 3\.9\.0\)
9389/tcp  open  mc\-nmf        \.NET Message Framing
49666/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49673/tcp open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
49674/tcp open  msrpc         Microsoft Windows RPC
49677/tcp open  msrpc         Microsoft Windows RPC
49705/tcp open  msrpc         Microsoft Windows RPC

-  [http://192.168.190.165:8080/?url=](#http://192.168.190.165:8080/?url=)

SSRF vulnerability\. can connect to attacker machine

