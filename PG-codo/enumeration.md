**sudo nmap \-sS \-sV \-\-script=default 192\.168\.246\.23**
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.7 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 62:36:1a:5c:d3:e3:7b:e1:70:f8:a3:b3:1c:4c:24:38 \(RSA\)
|   256 ee:25:fc:23:66:05:c0:c1:ec:47:c6:bb:00:c7:4f:53 \(ECDSA\)
|\_  256 83:5c:51:ac:32:e5:3a:21:7c:f6:c2:cd:93:68:58:d8 \(ED25519\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
|\_http\-title: All topics | CODOLOGIC
| http\-cookie\-flags: 
|   /: 
|     PHPSESSID: 
|\_      httponly flag not set
|\_http\-server\-header: Apache/2\.4\.41 \(Ubuntu\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**nmap \-sV \-p\- 192\.168\.246\.23 \-v**
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.7 \(Ubuntu Linux; protocol 2\.0\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel