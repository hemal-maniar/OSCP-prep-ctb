**sudo nmap \-sS \-sV \-\-script=default 192\.168\.201\.212**
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
| ssh\-hostkey: 
|   2048 44:95:50:0b:e4:73:a1:85:11:ca:10:ec:1c:cb:d4:26 \(RSA\)
|   256 27:db:6a:c7:3a:9c:5a:0e:47:ba:8d:81:eb:d6:d6:3c \(ECDSA\)
|\_  256 e3:07:56:a9:25:63:d4:ce:39:01:c1:9a:d9:fe:de:64 \(ED25519\)
80/tcp open  http    Apache httpd 2\.4\.38 \(\(Debian\)\)
|\_http\-title: Apache2 Debian Default Page: It works
|\_http\-server\-header: Apache/2\.4\.38 \(Debian\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**nmap \-sV \-p\- 192\.168\.201\.212 \-v**
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
80/tcp open  http    Apache httpd 2\.4\.38 \(\(Debian\)\)

**nikto \-url **[**http://192.168.201.212**](#http://192.168.201.212)

\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.201\.212
\+ Target Hostname:    192\.168\.201\.212
\+ Target Port:        80
\+ Start Time:         2024\-02\-23 13:34:58 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.4\.38 \(Debian\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /: Server may leak inodes via ETags, header found with file /, inode: 29cd, size: 5c9a9bb4d712e, mtime: gzip\. See: [http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-1418](#http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-1418)

\+ Apache/2\.4\.38 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ OPTIONS: Allowed HTTP Methods: GET, POST, OPTIONS, HEAD \.
\+ /secret/: This might be interesting\.
\+ /icons/README: Apache default file found\. See: [https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/](#https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/)

\+ 8102 requests: 0 error\(s\) and 7 item\(s\) reported on remote host
\+ End Time:           2024\-02\-23 13:39:19 \(GMT\-5\) \(261 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

dirbuster \-\> /secret/evil\.php
