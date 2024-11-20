**sudo nmap \-sS \-sV \-\-script=default 192\.168\.201\.98   
**PORT     STATE SERVICE     VERSION**
**22/tcp   open  ssh         OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
| ssh\-hostkey: 
|   2048 a8:e1:60:68:be:f5:8e:70:70:54:b4:27:ee:9a:7e:7f \(RSA\)
|   256 bb:99:9a:45:3f:35:0b:b3:49:e6:cf:11:49:87:8d:94 \(ECDSA\)
|\_  256 f2:eb:fc:45:d7:e9:80:77:66:a3:93:53:de:00:57:9c \(ED25519\)
139/tcp  open  netbios\-ssn Samba smbd 3\.X \- 4\.X \(workgroup: WORKGROUP\)
445/tcp  open  netbios\-ssn Samba smbd 4\.9\.5\-Debian \(workgroup: WORKGROUP\)
631/tcp  open  ipp         CUPS 2\.2
| http\-methods: 
|\_  Potentially risky methods: PUT
|\_http\-title: Forbidden \- CUPS v2\.2\.10
|\_http\-server\-header: CUPS/2\.2 IPP/2\.1
2222/tcp open  ssh         OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
| ssh\-hostkey: 
|   2048 a8:e1:60:68:be:f5:8e:70:70:54:b4:27:ee:9a:7e:7f \(RSA\)
|   256 bb:99:9a:45:3f:35:0b:b3:49:e6:cf:11:49:87:8d:94 \(ECDSA\)
|\_  256 f2:eb:fc:45:d7:e9:80:77:66:a3:93:53:de:00:57:9c \(ED25519\)
8080/tcp open  http        Jetty 1\.0
|\_http\-title: Error 404 Not Found
|\_http\-server\-header: Jetty\(1\.0\)
8081/tcp open  http        nginx 1\.14\.2
|\_http\-title: Did not follow redirect to [http://192.168.201.98:8080/exhibitor/v1/ui/index.html](#http://192.168.201.98:8080/exhibitor/v1/ui/index.html)

|\_http\-server\-header: nginx/1\.14\.2
Service Info: Host: PELICAN; OS: Linux; CPE: cpe:/o:linux:linux\_kernel

Host script results:
| smb\-security\-mode: 
|   account\_used: guest
|   authentication\_level: user
|   challenge\_response: supported
|\_  message\_signing: disabled \(dangerous, but default\)
|\_clock\-skew: mean: 1h40m03s, deviation: 2h53m14s, median: 2s
| smb\-os\-discovery: 
|   OS: Windows 6\.1 \(Samba 4\.9\.5\-Debian\)
|   Computer name: pelican
|   NetBIOS computer name: PELICAN\\x00
|   Domain name: \\x00
|   FQDN: pelican
|\_  System time: 2024\-02\-24T18:04:24\-05:00
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled but not required
| smb2\-time: 
|   date: 2024\-02\-24T23:04:22
|\_  start\_date: N/A**


nmap \-sV \-p\- 192\.168\.201\.98 \-v 
**PORT      STATE SERVICE     VERSION
22/tcp    open  ssh         OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
139/tcp   open  netbios\-ssn Samba smbd 3\.X \- 4\.X \(workgroup: WORKGROUP\)
445/tcp   open  netbios\-ssn Samba smbd 3\.X \- 4\.X \(workgroup: WORKGROUP\)
631/tcp   open  ipp         CUPS 2\.2
2181/tcp  open  zookeeper   Zookeeper 3\.4\.6\-1569965 \(Built on 02/20/2014\)
2222/tcp  open  ssh         OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
8080/tcp  open  http        Jetty 1\.0
8081/tcp  open  http        nginx 1\.14\.2
37753/tcp open  java\-rmi    Java RMI

