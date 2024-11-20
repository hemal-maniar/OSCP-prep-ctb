**sudo nmap \-sS \-sV \-\-script=default 192\.168\.246\.31**
PORT     STATE SERVICE       VERSION
21/tcp   open  ftp
| fingerprint\-strings: 
|   GenericLines, Help, NULL, SMBProgNeg, SSLSessionReq: 
|\_    220 Welcome to Simple FTP Server NG
53/tcp   open  domain        Simple DNS Plus
88/tcp   open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-04 23:11:16Z\)
111/tcp  open  rpcbind       2\-4 \(RPC #100000\)
| rpcinfo: 
|   program version    port/proto  service
|   100000  2,3,4        111/tcp   rpcbind
|   100000  2,3,4        111/tcp6  rpcbind
|   100000  2,3,4        111/udp   rpcbind
|   100000  2,3,4        111/udp6  rpcbind
|   100003  2,3         2049/udp   nfs
|   100003  2,3         2049/udp6  nfs
|   100003  2,3,4       2049/tcp   nfs
|   100003  2,3,4       2049/tcp6  nfs
|   100005  1,2,3       2049/tcp   mountd
|   100005  1,2,3       2049/tcp6  mountd
|   100005  1,2,3       2049/udp   mountd
|   100005  1,2,3       2049/udp6  mountd
|   100021  1,2,3,4     2049/tcp   nlockmgr
|   100021  1,2,3,4     2049/tcp6  nlockmgr
|   100021  1,2,3,4     2049/udp   nlockmgr
|   100021  1,2,3,4     2049/udp6  nlockmgr
|   100024  1           2049/tcp   status
|   100024  1           2049/tcp6  status
|   100024  1           2049/udp   status
|\_  100024  1           2049/udp6  status
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: Kyotosoft\.com0\., Site: Default\-First\-Site\-Name\)
445/tcp  open  microsoft\-ds?
464/tcp  open  kpasswd5?
593/tcp  open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp  open  tcpwrapped
2049/tcp open  nlockmgr      1\-4 \(RPC #100021\)
3268/tcp open  ldap          Microsoft Windows Active Directory LDAP \(Domain: Kyotosoft\.com0\., Site: Default\-First\-Site\-Name\)
3269/tcp open  tcpwrapped
3389/tcp open  ms\-wbt\-server Microsoft Terminal Services
| rdp\-ntlm\-info: 
|   Target\_Name: KYOTOSOFT
|   NetBIOS\_Domain\_Name: KYOTOSOFT
|   NetBIOS\_Computer\_Name: KYOTO
|   DNS\_Domain\_Name: Kyotosoft\.com
|   DNS\_Computer\_Name: kyoto\.Kyotosoft\.com
|   DNS\_Tree\_Name: Kyotosoft\.com
|   Product\_Version: 10\.0\.20348
|\_  System\_Time: 2024\-04\-04T23:11:58\+00:00
|\_ssl\-date: 2024\-04\-04T23:12:38\+00:00; \+4s from scanner time\.
| ssl\-cert: Subject: commonName=kyoto\.Kyotosoft\.com
| Not valid before: 2024\-04\-03T22:46:40
|\_Not valid after:  2024\-10\-03T22:46:40
1 service unrecognized despite returning data\. If you know the service/version, please submit the following fingerprint at [https://nmap.org/cgi-bin/submit.cgi?new-service](#https://nmap.org/cgi-bin/submit.cgi?new-service)
:
SF\-Port21\-TCP:V=7\.94SVN%I=7%D=4/4%Time=660F3390%P=x86\_64\-pc\-linux\-gnu%r\(NU
SF:LL,25,"220\\x20Welcome\\x20to\\x20Simple\\x20FTP\\x20Server\\x20NG\\r\\n"\)%r\(Ge
SF:nericLines,27,"220\\x20Welcome\\x20to\\x20Simple\\x20FTP\\x20Server\\x20NG\\r\\
SF:n\\r\\n"\)%r\(Help,27,"220\\x20Welcome\\x20to\\x20Simple\\x20FTP\\x20Server\\x20N
SF:G\\r\\n\\r\\n"\)%r\(SSLSessionReq,27,"220\\x20Welcome\\x20to\\x20Simple\\x20FTP\\x
SF:20Server\\x20NG\\r\\n\\r\\n"\)%r\(SMBProgNeg,27,"220\\x20Welcome\\x20to\\x20Simpl
SF:e\\x20FTP\\x20Server\\x20NG\\r\\n\\r\\n"\);
Service Info: Hosts: Simple, KYOTO; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2\-time: 
|   date: 2024\-04\-04T23:12:00
|\_  start\_date: N/A
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled and required
|\_clock\-skew: mean: 3s, deviation: 0s, median: 3s

**nmap \-sV \-Pn \-p\- \-v 192\.168\.246\.31**
PORT      STATE SERVICE       VERSION
21/tcp    open  ftp
53/tcp    open  domain        Simple DNS Plus
88/tcp    open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-04 23:13:01Z\)
111/tcp   open  rpcbind       2\-4 \(RPC #100000\)
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp   open  ldap          Microsoft Windows Active Directory LDAP \(Domain: Kyotosoft\.com0\., Site: Default\-First\-Site\-Name\)
445/tcp   open  microsoft\-ds?
464/tcp   open  kpasswd5?
593/tcp   open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp   open  tcpwrapped
2049/tcp  open  nlockmgr      1\-4 \(RPC #100021\)
3268/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: Kyotosoft\.com0\., Site: Default\-First\-Site\-Name\)
3269/tcp  open  tcpwrapped
3389/tcp  open  ms\-wbt\-server Microsoft Terminal Services
5985/tcp  open  http          Microsoft HTTPAPI httpd 2\.0 \(SSDP/UPnP\)
9389/tcp  open  mc\-nmf        \.NET Message Framing
47001/tcp open  http          Microsoft HTTPAPI httpd 2\.0 \(SSDP/UPnP\)
49664/tcp open  msrpc         Microsoft Windows RPC
49665/tcp open  msrpc         Microsoft Windows RPC
49666/tcp open  msrpc         Microsoft Windows RPC
49667/tcp open  msrpc         Microsoft Windows RPC
49669/tcp open  msrpc         Microsoft Windows RPC
49670/tcp open  msrpc         Microsoft Windows RPC
49732/tcp open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
49733/tcp open  msrpc         Microsoft Windows RPC
49748/tcp open  msrpc         Microsoft Windows RPC
49755/tcp open  msrpc         Microsoft Windows RPC
49760/tcp open  msrpc         Microsoft Windows RPC
49778/tcp open  msrpc         Microsoft Windows RPC
1 service unrecognized despite returning data\. If you know the service/version, please submit the following fingerprint at [https://nmap.org/cgi-bin/submit.cgi?new-service](#https://nmap.org/cgi-bin/submit.cgi?new-service)
:
SF\-Port21\-TCP:V=7\.94SVN%I=7%D=4/4%Time=660F33F9%P=x86\_64\-pc\-linux\-gnu%r\(NU
SF:LL,25,"220\\x20Welcome\\x20to\\x20Simple\\x20FTP\\x20Server\\x20NG\\r\\n"\)%r\(Ge
SF:nericLines,27,"220\\x20Welcome\\x20to\\x20Simple\\x20FTP\\x20Server\\x20NG\\r\\
SF:n\\r\\n"\)%r\(SSLSessionReq,27,"220\\x20Welcome\\x20to\\x20Simple\\x20FTP\\x20Se
SF:rver\\x20NG\\r\\n\\r\\n"\)%r\(SMBProgNeg,27,"220\\x20Welcome\\x20to\\x20Simple\\x2
SF:0FTP\\x20Server\\x20NG\\r\\n\\r\\n"\);
Service Info: Hosts: Simple, KYOTO; OS: Windows; CPE: cpe:/o:microsoft:windows

-  smbclient \-N \-L \\\\192\.168\.246\.31 

Sharename       Type      Comment
\-\-\-\-\-\-\-\-\-       \-\-\-\-      \-\-\-\-\-\-\-
ADMIN$          Disk      Remote Admin
C$              Disk      Default share
dev             Disk      development \& debugging share
IPC$            IPC       Remote IPC
NETLOGON        Disk      Logon server share 
SYSVOL          Disk      Logon server share

-  smbclient \-N \\\\\\\\192\.168\.246\.31\\\\dev 
Try "help" to get a list of possible commands\.
smb: \\\> ls
\.                                   D        0  Tue Aug  8 16:39:28 2023
\.\.                                DHS        0  Thu Apr  4 18:46:42 2024
\.git                                D        0  Tue Aug  8 16:39:26 2023
DEVLOG\.txt                          A      155  Tue Aug  8 16:37:16 2023
ftp\.exe                             A   155648  Tue Aug  8 15:08:10 2023

-  strings ftp\.exe
admin:SafariDozeDust17

