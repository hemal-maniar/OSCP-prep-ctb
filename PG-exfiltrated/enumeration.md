**sudo nmap \-sS \-sV \-\-script=default 192\.168\.201\.163
**PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.2 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 c1:99:4b:95:22:25:ed:0f:85:20:d3:63:b4:48:bb:cf \(RSA\)
|   256 0f:44:8b:ad:ad:95:b8:22:6a:f0:36:ac:19:d0:0e:f3 \(ECDSA\)
|\_  256 32:e1:2a:6c:cc:7c:e6:3e:23:f4:80:8d:33:ce:9b:3a \(ED25519\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
|\_http\-server\-header: Apache/2\.4\.41 \(Ubuntu\)
|\_http\-title: Did not follow redirect to [http://exfiltrated.offsec/](#http://exfiltrated.offsec/)

| http\-robots\.txt: 7 disallowed entries 
| /backup/ /cron/? /front/ /install/ /panel/ /tmp/ 
|\_/updates/
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**nmap \-sV \-p\- 192\.168\.201\.163 \-v**
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.2 \(Ubuntu Linux; protocol 2\.0\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)

-  [http://exfiltrated.offsec/robots.txt](#http://exfiltrated.offsec/robots.txt)

User\-agent: \*
Disallow: /backup/
Disallow: /cron/?
Disallow: /front/
Disallow: /install/
Disallow: /panel/ \-\> login panel Subrion CMS 4\.2\.1
Disallow: /tmp/
Disallow: /updates/