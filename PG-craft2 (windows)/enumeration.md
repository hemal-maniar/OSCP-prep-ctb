**sudo nmap \-sS \-sV \-\-script=default \-Pn 192\.168\.209\.188**
PORT    STATE SERVICE       VERSION
80/tcp  open  http          Apache httpd 2\.4\.48 \(\(Win64\) OpenSSL/1\.1\.1k PHP/8\.0\.7\)
|\_http\-server\-header: Apache/2\.4\.48 \(Win64\) OpenSSL/1\.1\.1k PHP/8\.0\.7
|\_http\-title: Craft
135/tcp open  msrpc         Microsoft Windows RPC
445/tcp open  microsoft\-ds?
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled but not required
| smb2\-time: 
|   date: 2024\-04\-12T21:19:16
|\_  start\_date: N/A

**nmap \-sV \-Pn \-p\- \-v 192\.168\.209\.188**
PORT      STATE SERVICE       VERSION
80/tcp    open  http          Apache httpd 2\.4\.48 \(\(Win64\) OpenSSL/1\.1\.1k PHP/8\.0\.7\)
135/tcp   open  msrpc         Microsoft Windows RPC
445/tcp   open  microsoft\-ds?
49666/tcp open  msrpc         Microsoft Windows RPC


