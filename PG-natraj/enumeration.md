**sudo nmap \-sS \-sV \-\-script=default 192\.168\.201\.80
**PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 7\.6p1 Ubuntu 4ubuntu0\.3 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   2048 d9:9f:da:f4:2e:67:01:92:d5:da:7f:70:d0:06:b3:92 \(RSA\)
|   256 bc:ea:f1:3b:fa:7c:05:0c:92:95:92:e9:e7:d2:07:71 \(ECDSA\)
|\_  256 f0:24:5b:7a:3b:d6:b7:94:c4:4b:fe:57:21:f8:00:61 \(ED25519\)
80/tcp open  http    Apache httpd 2\.4\.29 \(\(Ubuntu\)\)
|\_http\-title: HA:Natraj
|\_http\-server\-header: Apache/2\.4\.29 \(Ubuntu\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel
**
nmap \-sV \-p\- 192\.168\.201\.80 \-v **
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 7\.6p1 Ubuntu 4ubuntu0\.3 \(Ubuntu Linux; protocol 2\.0\)
80/tcp open  http    Apache httpd 2\.4\.29 \(\(Ubuntu\)\)

**gobuster dir \-u **[**http://192.168.201.80**](#http://192.168.201.80)
**\-w /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt \-t 100**
===============================================================
/images               \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.201.80/images/\]](#http://192.168.201.80/images/])

/console              \(Status: 301\) \[Size: 318\] \[\-\-\> [http://192.168.201.80/console/\]](#http://192.168.201.80/console/])


