**sudo nmap \-sS \-sV \-\-script=default 192\.168\.196\.13**
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.5 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 98:4e:5d:e1:e6:97:29:6f:d9:e0:d4:82:a8:f6:4f:3f \(RSA\)
|   256 57:23:57:1f:fd:77:06:be:25:66:61:14:6d:ae:5e:98 \(ECDSA\)
|\_  256 c7:9b:aa:d5:a6:33:35:91:34:1e:ef:cf:61:a8:30:1c \(ED25519\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
|\_http\-title: Wisdom Elementary School
|\_http\-server\-header: Apache/2\.4\.41 \(Ubuntu\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**nmap \-sV \-p\- 192\.168\.196\.13 \-v **
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.5 \(Ubuntu Linux; protocol 2\.0\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**nikto \-url **[**http://192.168.196.13**](#http://192.168.196.13)

nikto \-url [http://192.168.196.13](#http://192.168.196.13)

\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.196\.13
\+ Target Hostname:    192\.168\.196\.13
\+ Target Port:        80
\+ Start Time:         2024\-02\-27 18:43:21 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.4\.41 \(Ubuntu\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /: Server may leak inodes via ETags, header found with file /, inode: 5c92, size: 5f82d8cb86119, mtime: gzip\. See: [http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-1418](#http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-1418)

\+ Apache/2\.4\.41 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ OPTIONS: Allowed HTTP Methods: GET, POST, OPTIONS, HEAD \.
\+ 8102 requests: 0 error\(s\) and 5 item\(s\) reported on remote host
\+ End Time:           2024\-02\-27 18:49:53 \(GMT\-5\) \(392 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

Starting gobuster in directory enumeration mode
===============================================================
/assets               \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.196.13/assets/\]](#http://192.168.196.13/assets/])

/index\.html           \(Status: 200\) \[Size: 23698\]
/management           \(Status: 301\) \[Size: 321\] \[\-\-\> [http://192.168.196.13/management/\]](#http://192.168.196.13/management/])

/vendor               \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.196.13/vendor/\]](#http://192.168.196.13/vendor/])

/\.                    \(Status: 200\) \[Size: 23698\]

[http://192.168.196.13/management/installation/sql/](#http://192.168.196.13/management/installation/sql/)


-  database\.sql
INSERT INTO \`admin\` \(\`admin\_id\`, \`name\`, \`email\`, \`phone\`, \`password\`, \`level\`, \`login\_status\`\) VALUES
\(1, 'Administrator', 'admin@admin\.com', '07133445656', '7110eda4d09e062aa5e4a390b0a572ac0d2c0220', '1', '0'\),
\(9, 'Udemy Instructor', 'udemy@udemy\.com', '\+1564783934', '7110eda4d09e062aa5e4a390b0a572ac0d2c0220', '2', '0'\);

