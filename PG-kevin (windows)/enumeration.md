**sudo nmap \-sS \-sV \-\-script=default 192\.168\.199\.45
**PORT      STATE SERVICE      VERSION
80/tcp    open  http         GoAhead WebServer
|\_http\-server\-header: GoAhead\-Webs
| http\-title: HP Power Manager
|\_Requested resource was [http://192.168.199.45/index.asp](#http://192.168.199.45/index.asp)

135/tcp   open  msrpc        Microsoft Windows RPC
139/tcp   open  netbios\-ssn  Microsoft Windows netbios\-ssn
445/tcp   open  microsoft\-ds Windows 7 Ultimate N 7600 microsoft\-ds \(workgroup: WORKGROUP\)
3389/tcp  open  tcpwrapped
|\_ssl\-date: 2024\-03\-26T23:38:43\+00:00; \+1s from scanner time\.
| ssl\-cert: Subject: commonName=kevin
| Not valid before: 2024\-03\-25T23:36:13
|\_Not valid after:  2024\-09\-24T23:36:13
| rdp\-ntlm\-info: 
|   Target\_Name: KEVIN
|   NetBIOS\_Domain\_Name: KEVIN
|   NetBIOS\_Computer\_Name: KEVIN
|   DNS\_Domain\_Name: kevin
|   DNS\_Computer\_Name: kevin
|   Product\_Version: 6\.1\.7600
|\_  System\_Time: 2024\-03\-26T23:38:28\+00:00
49152/tcp open  msrpc        Microsoft Windows RPC
49153/tcp open  msrpc        Microsoft Windows RPC
49154/tcp open  msrpc        Microsoft Windows RPC
49155/tcp open  msrpc        Microsoft Windows RPC
49158/tcp open  msrpc        Microsoft Windows RPC
49159/tcp open  msrpc        Microsoft Windows RPC
Service Info: Host: KEVIN; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb\-os\-discovery: 
|   OS: Windows 7 Ultimate N 7600 \(Windows 7 Ultimate N 6\.1\)
|   OS CPE: cpe:/o:microsoft:windows\_7::\-
|   Computer name: kevin
|   NetBIOS computer name: KEVIN\\x00
|   Workgroup: WORKGROUP\\x00
|\_  System time: 2024\-03\-26T16:38:28\-07:00
| smb2\-time: 
|   date: 2024\-03\-26T23:38:28
|\_  start\_date: 2024\-03\-26T23:37:00
|\_nbstat: NetBIOS name: KEVIN, NetBIOS user: \<unknown\>, NetBIOS MAC: 00:50:56:bf:1d:a3 \(VMware\)
| smb\-security\-mode: 
|   account\_used: guest
|   authentication\_level: user
|   challenge\_response: supported
|\_  message\_signing: disabled \(dangerous, but default\)
| smb2\-security\-mode: 
|   2:1:0: 
|\_    Message signing enabled but not required
|\_clock\-skew: mean: 1h24m01s, deviation: 3h07m50s, median: 0s
**
nmap \-sV \-Pn \-p\- \-v 192\.168\.199\.45**
PORT      STATE SERVICE      VERSION
80/tcp    open  http         GoAhead WebServer
135/tcp   open  msrpc        Microsoft Windows RPC
139/tcp   open  netbios\-ssn  Microsoft Windows netbios\-ssn
445/tcp   open  microsoft\-ds Microsoft Windows 7 \- 10 microsoft\-ds \(workgroup: WORKGROUP\)
3573/tcp  open  tag\-ups\-1?
49152/tcp open  msrpc        Microsoft Windows RPC
49153/tcp open  msrpc        Microsoft Windows RPC
49154/tcp open  msrpc        Microsoft Windows RPC
49155/tcp open  msrpc        Microsoft Windows RPC
49158/tcp open  msrpc        Microsoft Windows RPC
49159/tcp open  msrpc        Microsoft Windows RPC

**sudo nmap \-sVCS \-\-script=smb\-vuln\-\* \-p 139,445 192\.168\.199\.45**
PORT    STATE SERVICE      VERSION
139/tcp open  netbios\-ssn  Microsoft Windows netbios\-ssn
445/tcp open  microsoft\-ds Microsoft Windows 7 \- 10 microsoft\-ds \(workgroup: WORKGROUP\)
Service Info: Host: KEVIN; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
|\_smb\-vuln\-ms10\-061: NT\_STATUS\_ACCESS\_DENIED
| **smb\-vuln\-ms17\-010: **
|   VULNERABLE:
|   Remote Code Execution vulnerability in Microsoft SMBv1 servers \(ms17\-010\)
|     State: VULNERABLE
|     IDs:  CVE:CVE\-2017\-0143
|     Risk factor: HIGH
|       A critical remote code execution vulnerability exists in Microsoft SMBv1
|        servers \(ms17\-010\)\.
|           
|     Disclosure date: 2017\-03\-14
|     References:
|       [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-0143](#https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-0143)

|       [https://blogs.technet.microsoft.com/msrc/2017/05/12/customer-guidance-for-wannacrypt-attacks/](#https://blogs.technet.microsoft.com/msrc/2017/05/12/customer-guidance-for-wannacrypt-attacks/)

|\_      [https://technet.microsoft.com/en-us/library/security/ms17-010.aspx](#https://technet.microsoft.com/en-us/library/security/ms17-010.aspx)

|\_smb\-vuln\-ms10\-054: false