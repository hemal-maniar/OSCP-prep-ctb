**sudo nmap \-sS \-sV \-\-script=default 192\.168\.196\.25
**PORT     STATE SERVICE  VERSION
22/tcp   open  ssh      OpenSSH 8\.4p1 Debian 5\+deb11u1 \(protocol 2\.0\)
| ssh\-hostkey: 
|   3072 c9:c3:da:15:28:3b:f1:f8:9a:36:df:4d:36:6b:a7:44 \(RSA\)
|   256 26:03:2b:f6:da:90:1d:1b:ec:8d:8f:8d:1e:7e:3d:6b \(ECDSA\)
|\_  256 fb:43:b2:b0:19:2f:d3:f6:bc:aa:60:67:ab:c1:af:37 \(ED25519\)
80/tcp   open  http     nginx 1\.18\.0
|\_http\-title: 403 Forbidden
|\_http\-server\-header: nginx/1\.18\.0
8082/tcp open  http     Barracuda Embedded Web Server
| http\-webdav\-scan: 
|   Server Type: BarracudaServer\.com \(Posix\)
|   Allowed Methods: OPTIONS, GET, HEAD, PROPFIND, PATCH, POST, PUT, COPY, DELETE, MOVE, MKCOL, PROPFIND, PROPPATCH, LOCK, UNLOCK
|   Server Date: Wed, 28 Feb 2024 18:49:47 GMT
|\_  WebDAV type: Unknown
| http\-methods: 
|\_  Potentially risky methods: PROPFIND PATCH PUT COPY DELETE MOVE MKCOL PROPPATCH LOCK UNLOCK
|\_http\-title: Home
|\_http\-server\-header: BarracudaServer\.com \(Posix\)
9999/tcp open  ssl/http Barracuda Embedded Web Server
|\_http\-server\-header: BarracudaServer\.com \(Posix\)
|\_http\-title: Home
| http\-webdav\-scan: 
|   Server Type: BarracudaServer\.com \(Posix\)
|   Allowed Methods: OPTIONS, GET, HEAD, PROPFIND, PATCH, POST, PUT, COPY, DELETE, MOVE, MKCOL, PROPFIND, PROPPATCH, LOCK, UNLOCK
|   Server Date: Wed, 28 Feb 2024 18:49:47 GMT
|\_  WebDAV type: Unknown
| ssl\-cert: Subject: commonName=FuguHub/stateOrProvinceName=California/countryName=US
| Subject Alternative Name: DNS:FuguHub, DNS:FuguHub\.local, DNS:localhost
| Not valid before: 2019\-07\-16T19:15:09
|\_Not valid after:  2074\-04\-18T19:15:09
| http\-methods: 
|\_  Potentially risky methods: PROPFIND PATCH PUT COPY DELETE MOVE MKCOL PROPPATCH LOCK UNLOCK
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel


**nmap \-sV \-p\- 192\.168\.196\.25 \-v 
**PORT     STATE SERVICE  VERSION
22/tcp   open  ssh      OpenSSH 8\.4p1 Debian 5\+deb11u1 \(protocol 2\.0\)
80/tcp   open  http     nginx 1\.18\.0
8082/tcp open  http     Barracuda Embedded Web Server
9999/tcp open  ssl/http Barracuda Embedded Web Server
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

nikto \-url [http://192.168.196.25:8082](#http://192.168.196.25:8082)

\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.196\.25
\+ Target Hostname:    192\.168\.196\.25
\+ Target Port:        8082
\+ Start Time:         2024\-02\-28 13:50:28 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: BarracudaServer\.com \(Posix\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ OPTIONS: Allowed HTTP Methods: OPTIONS, GET, HEAD, PROPFIND, PATCH, POST, PUT, COPY, DELETE, MOVE,  MKCOL, PROPPATCH, LOCK, UNLOCK,  MKCOL \.
\+ HTTP method: 'PATCH' may allow client to issue patch commands to server\. See RFC\-5789\.
\+ HTTP method \('Allow' Header\): 'PUT' method could allow clients to save files on the web server\.
\+ HTTP method \('Allow' Header\): 'DELETE' may allow clients to remove files on the web server\.
\+ HTTP method \('Allow' Header\): 'MOVE' may allow clients to change file locations on the web server\.
\+ OPTIONS: WebDAV enabled \(COPY UNLOCK LOCK PROPFIND PROPPATCH MKCOL listed as allowed\)\.
\+ ERROR: Error limit \(20\) reached for host, giving up\. Last error: 
\+ Scan terminated: 3 error\(s\) and 8 item\(s\) reported on remote host
\+ End Time:           2024\-02\-28 13:51:48 \(GMT\-5\) \(80 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested
