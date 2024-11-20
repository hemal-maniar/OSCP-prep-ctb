**sudo nmap \-sS \-sV \-\-script=default 192\.168\.201\.62**
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 7\.4 \(protocol 2\.0\)
| ssh\-hostkey: 
|   2048 44:7d:1a:56:9b:68:ae:f5:3b:f6:38:17:73:16:5d:75 \(RSA\)
|   256 1c:78:9d:83:81:52:f4:b0:1d:8e:32:03:cb:a6:18:93 \(ECDSA\)
|\_  256 08:c9:12:d9:7b:98:98:c8:b3:99:7a:19:82:2e:a3:ea \(ED25519\)
53/tcp   open  domain  NLnet Labs NSD
80/tcp   open  http    nginx 1\.16\.1
|\_http\-server\-header: nginx/1\.16\.1
|\_http\-title: Home | Mezzanine
8000/tcp open  http    nginx 1\.16\.1
|\_http\-title: Site doesn't have a title \(application/json\)\.
|\_http\-server\-header: nginx/1\.16\.1
|\_http\-open\-proxy: Proxy might be redirecting requests
**
nmap \-sV \-p\- 192\.168\.201\.62 \-v **
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 7\.4 \(protocol 2\.0\)
53/tcp   open  domain  NLnet Labs NSD
80/tcp   open  http    nginx 1\.16\.1
4505/tcp open  zmtp    ZeroMQ ZMTP 2\.0
4506/tcp open  zmtp    ZeroMQ ZMTP 2\.0
8000/tcp open  http    nginx 1\.16\.1

**nikto \-url **[**http://192.168.201.62**](#http://192.168.201.62)
****
\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.201\.62
\+ Target Hostname:    192\.168\.201\.62
\+ Target Port:        80
\+ Start Time:         2024\-02\-24 13:17:49 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: nginx/1\.16\.1
\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /sitemap\.xml: This gives a nice listing of the site content\.
\+ /#wp\-config\.php#: #wp\-config\.php# file found\. This file contains the credentials\.
\+ 8103 requests: 0 error\(s\) and 3 item\(s\) reported on remote host
\+ End Time:           2024\-02\-24 13:23:09 \(GMT\-5\) \(320 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested

**nikto \-url **[**http://192.168.201.62:8000**](#http://192.168.201.62:8000)
****
\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.201\.62
\+ Target Hostname:    192\.168\.201\.62
\+ Target Port:        8000
\+ Start Time:         2024\-02\-24 13:21:38 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: nginx/1\.16\.1
\+ /: Retrieved access\-control\-allow\-origin header: \*\.
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: Uncommon header 'x\-upstream' found, with contents: salt\-api/3000\-1\.
\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /: Cookie session\_id created without the httponly flag\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

\+ OPTIONS: Allowed HTTP Methods: GET, HEAD, POST \.
\+ /login/: This might be interesting\.
\+ 8102 requests: 0 error\(s\) and 7 item\(s\) reported on remote host
\+ End Time:           2024\-02\-24 13:26:08 \(GMT\-5\) \(270 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested
