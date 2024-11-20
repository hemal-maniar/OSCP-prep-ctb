**sudo nmap \-sS \-sV \-\-script=default \-Pn 192\.168\.209\.122**
PORT     STATE SERVICE       VERSION
53/tcp   open  domain        Simple DNS Plus
80/tcp   open  http          Microsoft IIS httpd 10\.0
| http\-methods: 
|\_  Potentially risky methods: TRACE COPY PROPFIND DELETE MOVE PROPPATCH MKCOL LOCK UNLOCK PUT
| http\-webdav\-scan: 
|   Allowed Methods: OPTIONS, TRACE, GET, HEAD, POST, COPY, PROPFIND, DELETE, MOVE, PROPPATCH, MKCOL, LOCK, UNLOCK
|   Server Type: Microsoft\-IIS/10\.0
|   Public Options: OPTIONS, TRACE, GET, HEAD, POST, PROPFIND, PROPPATCH, MKCOL, PUT, DELETE, COPY, MOVE, LOCK, UNLOCK
|   WebDAV type: Unknown
|\_  Server Date: Fri, 12 Apr 2024 17:36:58 GMT
|\_http\-title: IIS Windows Server
|\_http\-server\-header: Microsoft\-IIS/10\.0
88/tcp   open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-12 17:36:56Z\)
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: hutch\.offsec0\., Site: Default\-First\-Site\-Name\)
445/tcp  open  microsoft\-ds?
464/tcp  open  kpasswd5?
593/tcp  open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp  open  tcpwrapped
3268/tcp open  ldap          Microsoft Windows Active Directory LDAP \(Domain: hutch\.offsec0\., Site: Default\-First\-Site\-Name\)
3269/tcp open  tcpwrapped
Service Info: Host: HUTCHDC; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2\-time: 
|   date: 2024\-04\-12T17:37:03
|\_  start\_date: N/A
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled and required

**nmap \-sV \-Pn \-p\- \-v 192\.168\.209\.122**
PORT      STATE SERVICE       VERSION
53/tcp    open  domain        Simple DNS Plus
80/tcp    open  http          Microsoft IIS httpd 10\.0
88/tcp    open  kerberos\-sec  Microsoft Windows Kerberos \(server time: 2024\-04\-12 17:38:40Z\)
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios\-ssn   Microsoft Windows netbios\-ssn
389/tcp   open  ldap          Microsoft Windows Active Directory LDAP \(Domain: hutch\.offsec0\., Site: Default\-First\-Site\-Name\)
445/tcp   open  microsoft\-ds?
464/tcp   open  kpasswd5?
593/tcp   open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
636/tcp   open  tcpwrapped
3268/tcp  open  ldap          Microsoft Windows Active Directory LDAP \(Domain: hutch\.offsec0\., Site: Default\-First\-Site\-Name\)
3269/tcp  open  tcpwrapped
5985/tcp  open  http          Microsoft HTTPAPI httpd 2\.0 \(SSDP/UPnP\)
9389/tcp  open  mc\-nmf        \.NET Message Framing
49666/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49673/tcp open  ncacn\_http    Microsoft Windows RPC over HTTP 1\.0
49674/tcp open  msrpc         Microsoft Windows RPC
49676/tcp open  msrpc         Microsoft Windows RPC
49692/tcp open  msrpc         Microsoft Windows RPC

-  ldapsearch \-x \-H ldap://192\.168\.209\.122 \-b 'DC=hutch,DC=offsec' \> ldap\.txt
-  users\.txt
-  description: Password set to CrabSharkJellyfish192 at user's request\. \(fmcsorley\)

-  SMB         192\.168\.209\.122 445    HUTCHDC          \[\+\] hutch\.offsec\\fmcsorley:CrabSharkJellyfish192

**nikto \-h **[**http://192.168.209.122**](#http://192.168.209.122)
**
**\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.209\.122
\+ Target Hostname:    192\.168\.209\.122
\+ Target Port:        80
\+ Start Time:         2024\-04\-12 15:29:03 \(GMT\-4\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Microsoft\-IIS/10\.0
\+ /: Retrieved x\-powered\-by header: ASP\.NET\.
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ /48Dj5IWh\.aspx: Retrieved x\-aspnet\-version header: 4\.0\.30319\.
\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ OPTIONS: Allowed HTTP Methods: OPTIONS, TRACE, GET, HEAD, POST, PROPFIND, PROPPATCH, MKCOL, PUT, DELETE, COPY, MOVE, LOCK, UNLOCK \.
\+ HTTP method \('Allow' Header\): 'PUT' method could allow clients to save files on the web server\.
\+ HTTP method \('Allow' Header\): 'DELETE' may allow clients to remove files on the web server\.
\+ HTTP method \('Allow' Header\): 'MOVE' may allow clients to change file locations on the web server\.
\+ OPTIONS: Public HTTP Methods: OPTIONS, TRACE, GET, HEAD, POST, PROPFIND, PROPPATCH, MKCOL, PUT, DELETE, COPY, MOVE, LOCK, UNLOCK \.
\+ HTTP method \('Public' Header\): 'PUT' method could allow clients to save files on the web server\.
\+ HTTP method \('Public' Header\): 'DELETE' may allow clients to remove files on the web server\.
\+ HTTP method \('Public' Header\): 'MOVE' may allow clients to change file locations on the web server\.
\+ OPTIONS: WebDAV enabled \(UNLOCK COPY LOCK PROPFIND MKCOL PROPPATCH listed as allowed\)\.
\+ 8254 requests: 0 error\(s\) and 13 item\(s\) reported on remote host
\+ End Time:           2024\-04\-12 15:34:22 \(GMT\-4\) \(319 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested
