**sudo nmap \-sS \-sV \-\-script=default 192\.168\.207\.43**
PORT     STATE SERVICE       VERSION
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
445/tcp  open  microsoft\-ds  Windows Server \(R\) 2008 Standard 6001 Service Pack 1 microsoft\-ds \(workgroup: WORKGROUP\)
3389/tcp open  ms\-wbt\-server Microsoft Terminal Service
8080/tcp open  http          Apache Tomcat/Coyote JSP engine 1\.1
| http\-cookie\-flags: 
|   /: 
|     JSESSIONID: 
|\_      httponly flag not set
|\_http\-title: ManageEngine ServiceDesk Plus
|\_http\-server\-header: Apache\-Coyote/1\.1
Service Info: Host: HELPDESK; OS: Windows; CPE: cpe:/o:microsoft:windows, cpe:/o:microsoft:windows\_server\_2008:r2

Host script results:
|\_nbstat: NetBIOS name: HELPDESK, NetBIOS user: \<unknown\>, NetBIOS MAC: 00:50:56:bf:00:82 \(VMware\)
| smb2\-time: 
|   date: 2024\-03\-21T23:35:45                                                                                       
|\_  start\_date: 2024\-03\-21T23:34:45                                                                                 
|\_clock\-skew: mean: 2h20m00s, deviation: 4h02m29s, median: 0s                                                       
| smb\-os\-discovery:                                                                                                 
|   OS: Windows Server \(R\) 2008 Standard 6001 Service Pack 1 \(Windows Server \(R\) 2008 Standard 6\.0\)                 
|   OS CPE: cpe:/o:microsoft:windows\_server\_2008::sp1
|   Computer name: HELPDESK
|   NetBIOS computer name: HELPDESK\\x00
|   Workgroup: WORKGROUP\\x00
|\_  System time: 2024\-03\-21T16:35:45\-07:00
| smb\-security\-mode: 
|   account\_used: guest
|   authentication\_level: user
|   challenge\_response: supported
|\_  message\_signing: disabled \(dangerous, but default\)
| smb2\-security\-mode: 
|   2:0:2: 
|\_    Message signing enabled but not required

nmap \-sV \-p\- 192\.168\.207\.43 \-Pn \-v
PORT     STATE SERVICE       VERSION
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
445/tcp  open  microsoft\-ds  Microsoft Windows Server 2008 R2 microsoft\-ds \(workgroup: WORKGROUP\)
3389/tcp open  ms\-wbt\-server Microsoft Terminal Service
8080/tcp open  http          Apache Tomcat/Coyote JSP engine 1\.1

**nikto \-url **[**https://192.168.207.43:8080**](#https://192.168.207.43:8080)
