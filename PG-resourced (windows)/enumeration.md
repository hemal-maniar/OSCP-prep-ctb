**sudo nmap \-sS \-sV \-\-script=default \-Pn 192\.168\.239\.175
**PORT     STATE SERVICE       VERSION
53/tcp   open  domain        Simple DNS Plus
88/tcp   open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-05 19:46:13Z\)
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: resourced\.local0\., Site: Default\-First\-Site\-Name\)
445/tcp  open  microsoft\-ds?
464/tcp  open  kpasswd5?
593/tcp  open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp  open  tcpwrapped
3268/tcp open  ldap          Microsoft Windows Active Directory LDAP \(Domain: resourced\.local0\., Site: Default\-First\-Site\-Name\)
3269/tcp open  tcpwrapped
3389/tcp open  ms\-wbt\-server Microsoft Terminal Services
|\_ssl\-date: 2024\-04\-05T19:46:55\+00:00; \+1s from scanner time\.
| ssl\-cert: Subject: commonName=ResourceDC\.resourced\.local
| Not valid before: 2024\-04\-04T19:45:16
|\_Not valid after:  2024\-10\-04T19:45:16
| rdp\-ntlm\-info: 
|   Target\_Name: resourced
|   NetBIOS\_Domain\_Name: resourced
|   NetBIOS\_Computer\_Name: RESOURCEDC
|   DNS\_Domain\_Name: resourced\.local
|   DNS\_Computer\_Name: ResourceDC\.resourced\.local
|   DNS\_Tree\_Name: resourced\.local
|   Product\_Version: 10\.0\.17763
|\_  System\_Time: 2024\-04\-05T19:46:15\+00:00
Service Info: Host: RESOURCEDC; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2\-time: 
|   date: 2024\-04\-05T19:46:16
|\_  start\_date: N/A
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled and required
**
nmap \-sV \-Pn \-p\- \-v 192\.168\.239\.175**
PORT      STATE SERVICE       VERSION
53/tcp    open  domain        Simple DNS Plus
88/tcp    open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-05 19:48:35Z\)
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp   open  ldap          Microsoft Windows Active Directory LDAP \(Domain: resourced\.local0\., Site: Default\-First\-Site\-Name\)
445/tcp   open  microsoft\-ds?
464/tcp   open  kpasswd5?
593/tcp   open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp   open  tcpwrapped
3268/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: resourced\.local0\., Site: Default\-First\-Site\-Name\)
3269/tcp  open  tcpwrapped
3389/tcp  open  ms\-wbt\-server Microsoft Terminal Services
5985/tcp  open  http          Microsoft HTTPAPI httpd 2\.0 \(SSDP/UPnP\)
9389/tcp  open  mc\-nmf        \.NET Message Framing
49666/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49674/tcp open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
49675/tcp open  msrpc         Microsoft Windows RPC
49695/tcp open  msrpc         Microsoft Windows RPC
49711/tcp open  msrpc         Microsoft Windows RPC

-  enum4linux \-a 192\.168\.239\.175 \> enum\.txt
-  extracted users
index: 0xf6e RID: 0x453 acb: 0x00000210 Account: V\.Ventz	Name: \(null\)	Desc: New\-hired, reminder: HotelCalifornia194\!

-  smbclient \-U 'V\.Ventz' \-L \\\\\\\\192\.168\.239\.175\\\\ADMIN$
Password for \[WORKGROUP\\V\.Ventz\]: HotelCalifornia194\!

Sharename       Type      Comment
\-\-\-\-\-\-\-\-\-       \-\-\-\-      \-\-\-\-\-\-\-
ADMIN$          Disk      Remote Admin
C$              Disk      Default share
IPC$            IPC       Remote IPC
NETLOGON        Disk      Logon server share 
Password Audit  Disk      
SYSVOL          Disk      Logon server share