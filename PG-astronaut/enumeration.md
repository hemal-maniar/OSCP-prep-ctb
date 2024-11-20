**sudo nmap \-sS \-sV \-\-script=default 192\.168\.201\.12 **
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.5 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 98:4e:5d:e1:e6:97:29:6f:d9:e0:d4:82:a8:f6:4f:3f \(RSA\)
|   256 57:23:57:1f:fd:77:06:be:25:66:61:14:6d:ae:5e:98 \(ECDSA\)
|\_  256 c7:9b:aa:d5:a6:33:35:91:34:1e:ef:cf:61:a8:30:1c \(ED25519\)
80/tcp open  http    Apache httpd 2\.4\.41
|\_http\-title: Index of /
|\_http\-server\-header: Apache/2\.4\.41 \(Ubuntu\)
| http\-ls: Volume /
| SIZE  TIME              FILENAME
| \-     2021\-03\-17 17:46  grav\-admin/

**nmap \-sV \-p\- 192\.168\.201\.12 \-v **
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.5 \(Ubuntu Linux; protocol 2\.0\)
80/tcp open  http    Apache httpd 2\.4\.41

User\-agent: \*
Disallow: /backup/
Disallow: /bin/
Disallow: /cache/
Disallow: /grav/
Disallow: /logs/
Disallow: /system/
Disallow: /vendor/
Disallow: /user/
Allow: /user/pages/
Allow: /user/themes/
Allow: /user/images/
Allow: /
Allow: \*\.css$
Allow: \*\.js$
Allow: /system/\*\.js$