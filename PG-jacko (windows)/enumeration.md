**sudo nmap \-sS \-sV \-\-script=default 192\.168\.190\.66**
PORT     STATE SERVICE       VERSION
80/tcp   open  http          Microsoft IIS httpd 10\.0
|\_http\-title: H2 Database Engine \(redirect\)
|\_http\-server\-header: Microsoft\-IIS/10\.0
| http\-methods: 
|\_  Potentially risky methods: TRACE
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
445/tcp  open  microsoft\-ds?
8082/tcp open  http          H2 database http console
|\_http\-title: H2 Console
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled but not required
| smb2\-time: 
|   date: 2024\-04\-03T22:38:49
|\_  start\_date: N/A

**nmap \-sV \-Pn \-p\- \-v 192\.168\.190\.66**
PORT     STATE SERVICE       VERSION
80/tcp   open  http          Microsoft IIS httpd 10\.0
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
445/tcp  open  microsoft\-ds?
7680/tcp open  pando\-pub?
8082/tcp open  http          H2 database http console
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

gobuster dir \-u [http://192.168.190.66](#http://192.168.190.66)
\-w /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt \-t 100 \-x php,asp,txt