**sudo nmap \-sS \-sV \-\-script=default 192\.168\.196\.16
**PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.5 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 98:4e:5d:e1:e6:97:29:6f:d9:e0:d4:82:a8:f6:4f:3f \(RSA\)
|   256 57:23:57:1f:fd:77:06:be:25:66:61:14:6d:ae:5e:98 \(ECDSA\)
|\_  256 c7:9b:aa:d5:a6:33:35:91:34:1e:ef:cf:61:a8:30:1c \(ED25519\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
|\_http\-server\-header: Apache/2\.4\.41 \(Ubuntu\)**

nmap \-sV \-p\- 192\.168\.196\.16 \-v**
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.5 \(Ubuntu Linux; protocol 2\.0\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

/wp\-content           \(Status: 301\) \[Size: 321\] \[\-\-\> [http://192.168.196.16/wp-content/\]](#http://192.168.196.16/wp-content/])

/wordpress            \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.16/wordpress/\]](#http://192.168.196.16/wordpress/])

/license\.txt          \(Status: 200\) \[Size: 19915\]
/wp\-includes          \(Status: 301\) \[Size: 322\] \[\-\-\> [http://192.168.196.16/wp-includes/\]](#http://192.168.196.16/wp-includes/])

/wp\-admin             \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.16/wp-admin/\]](#http://192.168.196.16/wp-admin/])

/filemanager          \(Status: 301\) \[Size: 322\] \[\-\-\> [http://192.168.196.16/filemanager/\]](#http://192.168.196.16/filemanager/])
