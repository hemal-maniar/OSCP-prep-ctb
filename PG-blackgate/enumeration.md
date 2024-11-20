**sudo nmap \-sS \-sV \-\-script=default 192\.168\.201\.176**
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.3p1 Ubuntu 1ubuntu0\.1 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 37:21:14:3e:23:e5:13:40:20:05:f9:79:e0:82:0b:09 \(RSA\)
|   256 b9:8d:bd:90:55:7c:84:cc:a0:7f:a8:b4:d3:55:06:a7 \(ECDSA\)
|\_  256 07:07:29:7a:4c:7c:f2:b0:1f:3c:3f:2b:a1:56:9e:0a \(ED25519\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**nmap \-sV \-p\- 192\.168\.201\.176 \-v
**PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 8\.3p1 Ubuntu 1ubuntu0\.1 \(Ubuntu Linux; protocol 2\.0\)
6379/tcp open  redis   Redis key\-value store 4\.0\.14

