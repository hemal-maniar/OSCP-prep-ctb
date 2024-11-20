**sudo nmap \-sS \-sV \-\-script=default 192\.168\.196\.146**
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
| ssh\-hostkey: 
|   2048 37:80:01:4a:43:86:30:c9:79:e7:fb:7f:3b:a4:1e:dd \(RSA\)
|   256 b6:18:a1:e1:98:fb:6c:c6:87:55:45:10:c6:d4:45:b9 \(ECDSA\)
|\_  256 ab:8f:2d:e8:a2:04:e7:b7:65:d3:fe:5e:93:1e:03:67 \(ED25519\)
80/tcp   open  http    Apache httpd 2\.4\.38 \(\(Debian\)\)
| http\-title: SuiteCRM
|\_Requested resource was index\.php?action=Login\&module=Users
| http\-cookie\-flags: 
|   /: 
|     PHPSESSID: 
|\_      httponly flag not set
|\_http\-server\-header: Apache/2\.4\.38 \(Debian\)
| http\-robots\.txt: 1 disallowed entry 
|\_/
3306/tcp open  mysql   MySQL \(unauthorized\)

**nmap \-sV \-p\- 192\.168\.196\.146 \-v**
PORT      STATE SERVICE VERSION
22/tcp    open  ssh     OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
80/tcp    open  http    Apache httpd 2\.4\.38 \(\(Debian\)\)
3306/tcp  open  mysql   MySQL \(unauthorized\)
33060/tcp open  mysqlx?

/themes               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.146/themes/\]](#http://192.168.196.146/themes/])

/pdf\.php              \(Status: 200\) \[Size: 23\]
/modules              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.146/modules/\]](#http://192.168.196.146/modules/])

/data                 \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.196.146/data/\]](#http://192.168.196.146/data/])

/upload               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.146/upload/\]](#http://192.168.196.146/upload/])

/service              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.146/service/\]](#http://192.168.196.146/service/])

/install              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.146/install/\]](#http://192.168.196.146/install/])

/install\.php          \(Status: 200\) \[Size: 2324\]
/lib                  \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.196.146/lib/\]](#http://192.168.196.146/lib/])

/custom               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.146/custom/\]](#http://192.168.196.146/custom/])

/cache                \(Status: 301\) \[Size: 318\] \[\-\-\> [http://192.168.196.146/cache/\]](#http://192.168.196.146/cache/])

/include              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.146/include/\]](#http://192.168.196.146/include/])

/export\.php           \(Status: 200\) \[Size: 23\]
/vendor               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.146/vendor/\]](#http://192.168.196.146/vendor/])

/config\.php           \(Status: 200\) \[Size: 0\]
/dictionary\.php       \(Status: 200\) \[Size: 23\]
/vCard\.php            \(Status: 200\) \[Size: 23\]
/Zend                 \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.196.146/Zend/\]](#http://192.168.196.146/Zend/])

/Api                  \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.196.146/Api/\]](#http://192.168.196.146/Api/])

/deprecated\.php       \(Status: 200\) \[Size: 0\]
/cache                \(Status: 301\) \[Size: 318\] \[\-\-\> [http://192.168.196.146/cache/\]](#http://192.168.196.146/cache/])

/config\.php           \(Status: 200\) \[Size: 0\]
/crossdomain\.xml      \(Status: 200\) \[Size: 2290\]
/cron\.php             \(Status: 500\) \[Size: 21\]
/custom               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.146/custom/\]](#http://192.168.196.146/custom/])

/data                 \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.196.146/data/\]](#http://192.168.196.146/data/])

/dictionary\.php       \(Status: 200\) \[Size: 23\]
/download\.php         \(Status: 200\) \[Size: 23\]
/export\.php           \(Status: 200\) \[Size: 23\]
/include              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.146/include/\]](#http://192.168.196.146/include/])

/index\.php            \(Status: 301\) \[Size: 0\] \[\-\-\> index\.php?action=Login\&module=Users\]
/index\.php            \(Status: 301\) \[Size: 0\] \[\-\-\> index\.php?action=Login\&module=Users\]
/install              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.146/install/\]](#http://192.168.196.146/install/])

/install\.php          \(Status: 200\) \[Size: 2324\]
/lib                  \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.196.146/lib/\]](#http://192.168.196.146/lib/])

/maintenance\.php      \(Status: 200\) \[Size: 47\]
/metadata             \(Status: 301\) \[Size: 321\] \[\-\-\> [http://192.168.196.146/metadata/\]](#http://192.168.196.146/metadata/])

/modules              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.146/modules/\]](#http://192.168.196.146/modules/])

/pdf\.php              \(Status: 200\) \[Size: 23\]
/robots\.txt           \(Status: 200\) \[Size: 73\]
/service              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.146/service/\]](#http://192.168.196.146/service/])

/server\-status        \(Status: 403\) \[Size: 280\]
/soap                 \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.196.146/soap/\]](#http://192.168.196.146/soap/])

/soap\.php             \(Status: 200\) \[Size: 76576\]
/themes               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.146/themes/\]](#http://192.168.196.146/themes/])

/upload               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.146/upload/\]](#http://192.168.196.146/upload/])

/vendor               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.146/vendor/\]](#http://192.168.196.146/vendor/])


**nikto \-url **[**http://192.168.196.146**](#http://192.168.196.146)

\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.196\.146
\+ Target Hostname:    192\.168\.196\.146
\+ Target Port:        80
\+ Start Time:         2024\-02\-27 13:31:58 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.4\.38 \(Debian\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ /: Cookie PHPSESSID created without the httponly flag\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

\+ Root page / redirects to: index\.php?action=Login\&module=Users
\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /ical\_server\.php: Uncommon header 'x\-webdav\-status' found, with contents: 401 not authorized\.
\+ /ical\_server\.php: Uncommon header 'x\-dav\-powered\-by' found, with contents: PHP class: HTTP\_WebDAV\_Server\_iCal\.
\+ /ical\_server\.php: Default account found for 'SugarCRM iCal' at \(ID 'admin', PW ''\)\. Generic account discovered\. See: CWE\-16
\+ /robots\.txt: Entry '/ical\_server\.php' is returned a non\-forbidden or redirect HTTP code \(200\)\. See: [https://portswigger.net/kb/issues/00600600_robots-txt-file](#https://portswigger.net/kb/issues/00600600_robots-txt-file)

\+ /robots\.txt: contains 2 entries which should be manually viewed\. See: [https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt](#https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt)

\+ Apache/2\.4\.38 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ /config\.php: PHP Config file may contain database IDs and passwords\.
\+ /data/: Directory indexing found\.
\+ /data/: This might be interesting\.
\+ /install/: Directory indexing found\.
\+ /install/: This might be interesting\.
\+ /lib/: Directory indexing found\.
\+ /lib/: This might be interesting\.
\+ /service/: Directory indexing found\.
\+ /service/: This might be interesting\.
\+ /install\.php: install\.php file found\.
\+ /LICENSE\.txt: License file found may identify site software\.
\+ /icons/README: Apache default file found\. See: [https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/](#https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/)

\+ /composer\.json: PHP Composer configuration file reveals configuration information\. See: [https://getcomposer.org/](#https://getcomposer.org/)

\+ /composer\.lock: PHP Composer configuration file reveals configuration information\. See: [https://getcomposer.org/](#https://getcomposer.org/)

\+ /README\.md: Readme Found\.
\+ 8123 requests: 0 error\(s\) and 24 item\(s\) reported on remote host
\+ End Time:           2024\-02\-27 13:39:27 \(GMT\-5\) \(449 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested
