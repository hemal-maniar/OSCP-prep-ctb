**sudo nmap \-sS \-sV \-\-script=default 192\.168\.199\.40**
PORT      STATE SERVICE            VERSION
53/tcp    open  domain             Microsoft DNS 6\.0\.6001 \(17714650\) \(Windows Server 2008 SP1\)
| dns\-nsid: 
|\_  bind\.version: Microsoft DNS 6\.0\.6001 \(17714650\)
135/tcp   open  msrpc              Microsoft Windows RPC
139/tcp   open  netbios\-ssn        Microsoft Windows netbios\-ssn
445/tcp   open  microsoft\-ds       Windows Server \(R\) 2008 Standard 6001 Service Pack 1 microsoft\-ds \(workgroup: WORKGROUP\)
3389/tcp  open  ssl/ms\-wbt\-server?
| rdp\-ntlm\-info: 
|   Target\_Name: INTERNAL
|   NetBIOS\_Domain\_Name: INTERNAL
|   NetBIOS\_Computer\_Name: INTERNAL
|   DNS\_Domain\_Name: internal
|   DNS\_Computer\_Name: internal
|   Product\_Version: 6\.0\.6001
|\_  System\_Time: 2024\-03\-27T18:17:08\+00:00
| ssl\-cert: Subject: commonName=internal
| Not valid before: 2023\-01\-22T17:37:15
|\_Not valid after:  2023\-07\-24T17:37:15
|\_ssl\-date: 2024\-03\-27T18:17:16\+00:00; \+1s from scanner time\.
5357/tcp  open  http               Microsoft HTTPAPI httpd 2\.0 \(SSDP/UPnP\)
|\_http\-server\-header: Microsoft\-HTTPAPI/2\.0
|\_http\-title: Service Unavailable
49152/tcp open  msrpc              Microsoft Windows RPC
49153/tcp open  msrpc              Microsoft Windows RPC
49154/tcp open  msrpc              Microsoft Windows RPC
49155/tcp open  msrpc              Microsoft Windows RPC
49156/tcp open  msrpc              Microsoft Windows RPC
49157/tcp open  msrpc              Microsoft Windows RPC
49158/tcp open  msrpc              Microsoft Windows RPC
Service Info: Host: INTERNAL; OS: Windows; CPE: cpe:/o:microsoft:windows\_server\_2008::sp1, cpe:/o:microsoft:windows, cpe:/o:microsoft:windows\_server\_2008:r2

Host script results:
| smb2\-time: 
|   date: 2024\-03\-27T18:17:08
|\_  start\_date: 2023\-01\-23T17:37:08
| smb\-os\-discovery: 
|   OS: Windows Server \(R\) 2008 Standard 6001 Service Pack 1 \(Windows Server \(R\) 2008 Standard 6\.0\)
|   OS CPE: cpe:/o:microsoft:windows\_server\_2008::sp1
|   Computer name: internal
|   NetBIOS computer name: INTERNAL\\x00
|   Workgroup: WORKGROUP\\x00
|\_  System time: 2024\-03\-27T11:17:08\-07:00
|\_nbstat: NetBIOS name: INTERNAL, NetBIOS user: \<unknown\>, NetBIOS MAC: 00:50:56:bf:1f:ce \(VMware\)
|\_clock\-skew: mean: 1h24m01s, deviation: 3h07m50s, median: 0s
| smb\-security\-mode: 
|   account\_used: guest
|   authentication\_level: user
|   challenge\_response: supported
|\_  message\_signing: disabled \(dangerous, but default\)
| smb2\-security\-mode: 
|   2:0:2: 
|\_    Message signing enabled but not required


**nmap \-sV \-Pn \-p\- \-v 192\.168\.199\.40**
PORT      STATE SERVICE            VERSION
53/tcp    open  domain             Microsoft DNS 6\.0\.6001 \(17714650\) \(Windows Server 2008 SP1\)
135/tcp   open  msrpc              Microsoft Windows RPC
139/tcp   open  netbios\-ssn        Microsoft Windows netbios\-ssn
445/tcp   open  microsoft\-ds       Microsoft Windows Server 2008 R2 microsoft\-ds \(workgroup: WORKGROUP\)
3389/tcp  open  ssl/ms\-wbt\-server?
5357/tcp  open  http               Microsoft HTTPAPI httpd 2\.0 \(SSDP/UPnP\)
49152/tcp open  msrpc              Microsoft Windows RPC
49153/tcp open  msrpc              Microsoft Windows RPC
49154/tcp open  msrpc              Microsoft Windows RPC
49155/tcp open  msrpc              Microsoft Windows RPC
49156/tcp open  msrpc              Microsoft Windows RPC
49157/tcp open  msrpc              Microsoft Windows RPC
49158/tcp open  msrpc              Microsoft Windows RPC
Service Info: Host: INTERNAL; OS: Windows; CPE: cpe:/o:microsoft:windows\_server\_2008::sp1, cpe:/o:microsoft:windows, cpe:/o:microsoft:windows\_server\_2008:r2
burp