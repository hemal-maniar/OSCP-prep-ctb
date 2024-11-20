**sudo nmap \-sS \-sV \-\-script=default 192\.168\.0\.106**
Starting Nmap 7\.94SVN \( [https://nmap.org](#https://nmap.org)
\) at 2024\-02\-15 17:15 EST
Nmap scan report for 192\.168\.0\.106
Host is up \(0\.00046s latency\)\.
Not shown: 999 closed tcp ports \(reset\)
PORT   STATE SERVICE VERSION
80/tcp open  http    Apache httpd 2\.4\.18 \(\(Ubuntu\)\)
|\_http\-title: Home
|\_http\-server\-header: Apache/2\.4\.18 \(Ubuntu\)
|\_http\-generator: Joomla\! \- Open Source Content Management
MAC Address: 08:00:27:68:53:4F \(Oracle VirtualBox virtual NIC\)

nikto \-url [http://192.168.0.106](#http://192.168.0.106)

\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.0\.106
\+ Target Hostname:    192\.168\.0\.106
\+ Target Port:        80
\+ Start Time:         2024\-02\-15 17:25:32 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.4\.18 \(Ubuntu\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ /images: IP address found in the 'location' header\. The IP is "127\.0\.1\.1"\. See: [https://portswigger.net/kb/issues/00600300_private-ip-addresses-disclosed](#https://portswigger.net/kb/issues/00600300_private-ip-addresses-disclosed)

\+ /images: The web server may reveal its internal or real IP in the Location header via a request to with HTTP/1\.0\. The value is "127\.0\.1\.1"\. See: [http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2000-0649](#http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2000-0649)

\+ Apache/2\.4\.18 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ /: Web Server returns a valid response with junk HTTP methods which may cause false positives\.
\+ /: DEBUG HTTP verb may show server debugging information\. See: [https://docs.microsoft.com/en-us/visualstudio/debugger/how-to-enable-debugging-for-aspnet-applications?view=vs-2017](#https://docs.microsoft.com/en-us/visualstudio/debugger/how-to-enable-debugging-for-aspnet-applications?view=vs-2017)

\+ /index\.php?module=ew\_filemanager\&type=admin\&func=manager\&pathext=\.\./\.\./\.\./etc: EW FileManager for PostNuke allows arbitrary file retrieval\. See: [http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2004-2047](#http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2004-2047)

\+ /administrator/: This might be interesting\.
\+ /bin/: This might be interesting\.
\+ /includes/: This might be interesting\.
\+ /tmp/: This might be interesting\.
\+ /LICENSE\.txt: License file found may identify site software\.
\+ /icons/README: Apache default file found\. See: [https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/](#https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/)

\+ /htaccess\.txt: Default Joomla\! htaccess\.txt file found\. This should be removed or renamed\.
\+ /administrator/index\.php: Admin login page/section found\.
\+ 8910 requests: 0 error\(s\) and 16 item\(s\) reported on remote host
\+ End Time:           2024\-02\-15 17:25:59 \(GMT\-5\) \(27 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

**gobuster dir \-u **[**http://192.168.0.106**](#http://192.168.0.106)
**\-w /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt \-t 100**
===============================================================
Gobuster v3\.6
by OJ Reeves \(@TheColonial\) \& Christian Mehlmauer \(@firefart\)
===============================================================
\[\+\] Url:                     [http://192.168.0.106](#http://192.168.0.106)

\[\+\] Method:                  GET
\[\+\] Threads:                 100
\[\+\] Wordlist:                /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt
\[\+\] Negative Status codes:   404
\[\+\] User Agent:              gobuster/3\.6
\[\+\] Timeout:                 10s
===============================================================
Starting gobuster in directory enumeration mode
===============================================================
/modules              \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.0.106/modules/\]](#http://192.168.0.106/modules/])

/bin                  \(Status: 301\) \[Size: 312\] \[\-\-\> [http://192.168.0.106/bin/\]](#http://192.168.0.106/bin/])

/plugins              \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.0.106/plugins/\]](#http://192.168.0.106/plugins/])

/includes             \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.106/includes/\]](#http://192.168.0.106/includes/])

/language             \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.106/language/\]](#http://192.168.0.106/language/])

/components           \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.0.106/components/\]](#http://192.168.0.106/components/])

/cache                \(Status: 301\) \[Size: 314\] \[\-\-\> [http://192.168.0.106/cache/\]](#http://192.168.0.106/cache/])

/images               \(Status: 301\) \[Size: 315\] \[\-\-\> [http://192.168.0.106/images/\]](#http://192.168.0.106/images/])

/libraries            \(Status: 301\) \[Size: 318\] \[\-\-\> [http://192.168.0.106/libraries/\]](#http://192.168.0.106/libraries/])

/tmp                  \(Status: 301\) \[Size: 312\] \[\-\-\> [http://192.168.0.106/tmp/\]](#http://192.168.0.106/tmp/])

/templates            \(Status: 301\) \[Size: 318\] \[\-\-\> [http://192.168.0.106/templates/\]](#http://192.168.0.106/templates/])

/layouts              \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.0.106/layouts/\]](#http://192.168.0.106/layouts/])

/media                \(Status: 301\) \[Size: 314\] \[\-\-\> [http://192.168.0.106/media/\]](#http://192.168.0.106/media/])

/administrator        \(Status: 301\) \[Size: 322\] \[\-\-\> [http://192.168.0.106/administrator/\]](#http://192.168.0.106/administrator/])

/cli                  \(Status: 301\) \[Size: 312\] \[\-\-\> [http://192.168.0.106/cli/\]](#http://192.168.0.106/cli/])

/server\-status        \(Status: 403\) \[Size: 301\]
Progress: 220560 / 220561 \(100\.00%\)
===============================================================
Finished
