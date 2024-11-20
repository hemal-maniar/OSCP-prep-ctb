**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.0\.30 **
PORT   STATE SERVICE VERSION
80/tcp open  http    Apache httpd 2\.2\.22 \(\(Debian\)\)
| http\-enum: 
|\_  /robots\.txt: Robots file
| http\-robots\.txt: 1 disallowed entry 
|\_/textpattern/textpattern
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
| vulners: 
|   cpe:/a:apache:http\_server:2\.2\.22: 
|       SSV:60905       4\.3     [https://vulners.com/seebug/SSV:60905](#https://vulners.com/seebug/SSV:60905)
\*EXPLOIT\*
|\_      CVE\-2013\-1896   4\.3     [https://vulners.com/cve/CVE-2013-1896](#https://vulners.com/cve/CVE-2013-1896)

|\_http\-title: driftingblues
|\_http\-server\-header: Apache/2\.2\.22 \(Debian\)
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
MAC Address: 00:0C:29:4B:9B:09 \(VMware\)

**nikto \-url 192\.168\.0\.30      **
\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.0\.30
\+ Target Hostname:    192\.168\.0\.30
\+ Target Port:        80
\+ Start Time:         2023\-11\-26 22:10:01 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.2\.22 \(Debian\)
\+ /: Server may leak inodes via ETags, header found with file /, inode: 14067, size: 750, mtime: Mon Mar 15 09:36:18 2021\. See: [http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-1418](#http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-1418)

\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ /textpattern/textpattern/: Retrieved x\-powered\-by header: PHP/5\.5\.38\-1~dotdeb\+7\.1\.
\+ /textpattern/textpattern/: Cookie txp\_test\_cookie created without the httponly flag\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

\+ /robots\.txt: Entry '/textpattern/textpattern/' is returned a non\-forbidden or redirect HTTP code \(200\)\. See: [https://portswigger.net/kb/issues/00600600_robots-txt-file](#https://portswigger.net/kb/issues/00600600_robots-txt-file)

\+ /robots\.txt: contains 1 entry which should be manually viewed\. See: [https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt](#https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt)

\+ Apache/2\.2\.22 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ /index: Uncommon header 'tcn' found, with contents: list\.
\+ /index: Apache mod\_negotiation is enabled with MultiViews, which allows attackers to easily brute force file names\. The following alternatives for 'index' were found: index\.html\. See: [http://www.wisec.it/sectou.php?id=4698ebdc59d15,https://exchange.xforce.ibmcloud.com/vulnerabilities/8275](#http://www.wisec.it/sectou.php?id=4698ebdc59d15,https://exchange.xforce.ibmcloud.com/vulnerabilities/8275)

\+ OPTIONS: Allowed HTTP Methods: GET, HEAD, POST, OPTIONS \.
\+ /icons/README: Apache default file found\. See: [https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/](#https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/)

\+ /#wp\-config\.php#: #wp\-config\.php# file found\. This file contains the credentials\.
\+ 8910 requests: 0 error\(s\) and 13 item\(s\) reported on remote host
\+ End Time:           2023\-11\-26 22:10:14 \(GMT\-5\) \(13 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested

**gobuster dir \-u **[**http://192.168.0.30**](#http://192.168.0.30)
**\-w /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt \-t 100
**===============================================================
Gobuster v3\.6
by OJ Reeves \(@TheColonial\) \& Christian Mehlmauer \(@firefart\)
===============================================================
\[\+\] Url:                     [http://192.168.0.30](#http://192.168.0.30)

\[\+\] Method:                  GET
\[\+\] Threads:                 100
\[\+\] Wordlist:                /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt
\[\+\] Negative Status codes:   404
\[\+\] User Agent:              gobuster/3\.6
\[\+\] Timeout:                 10s
===============================================================
Starting gobuster in directory enumeration mode
===============================================================
/db                   \(Status: 200\) \[Size: 53656\]
/robots               \(Status: 200\) \[Size: 110\]
/index                \(Status: 200\) \[Size: 750\]
/spammer              \(Status: 200\) \[Size: 179\]
/server\-status        \(Status: 403\) \[Size: 293\]
Progress: 220560 / 220561 \(100\.00%\)
