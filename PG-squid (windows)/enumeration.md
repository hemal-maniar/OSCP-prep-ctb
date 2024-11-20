**sudo nmap \-sS \-sV \-\-script=default 192\.168\.207\.189**
PORT     STATE SERVICE       VERSION
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
445/tcp  open  microsoft\-ds?
3128/tcp open  http\-proxy    Squid http proxy 4\.14
|\_http\-title: ERROR: The requested URL could not be retrieved
|\_http\-server\-header: squid/4\.14
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2\-time: 
|   date: 2024\-03\-22T02:27:38
|\_  start\_date: N/A
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled but not required

**nmap \-sV \-p\- \-v 192\.168\.207\.189**
PORT      STATE SERVICE       VERSION
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios\-ssn   Microsoft Windows netbios\-ssn
445/tcp   open  microsoft\-ds?
3128/tcp  open  http\-proxy    Squid http proxy 4\.14
49666/tcp open  msrpc         Microsoft Windows RPC
49667/tcp open  msrpc         Microsoft Windows RPC
