**sudo nmap \-sS \-sV \-\-script=default 192\.168\.0\.229**
PORT    STATE SERVICE  VERSION
80/tcp  open  http     Apache httpd 2\.4\.38 \(\(Debian\)\)
|\_http\-title: PowerGrid \- Turning your lights off unless you pay\.
|\_http\-server\-header: Apache/2\.4\.38 \(Debian\)
143/tcp open  imap     Dovecot imapd
|\_ssl\-date: TLS randomness does not represent time
|\_imap\-capabilities: ENABLE Pre\-login more capabilities STARTTLS post\-login listed have LOGIN\-REFERRALS OK ID IDLE IMAP4rev1 LOGINDISABLEDA0001 LITERAL\+ SASL\-IR
| ssl\-cert: Subject: commonName=powergrid
| Subject Alternative Name: DNS:powergrid
| Not valid before: 2020\-05\-19T16:49:55
|\_Not valid after:  2030\-05\-17T16:49:55
993/tcp open  ssl/imap Dovecot imapd
|\_ssl\-date: TLS randomness does not represent time
| ssl\-cert: Subject: commonName=powergrid
| Subject Alternative Name: DNS:powergrid
| Not valid before: 2020\-05\-19T16:49:55
|\_Not valid after:  2030\-05\-17T16:49:55
|\_imap\-capabilities: ENABLE AUTH=PLAINA0001 more capabilities post\-login listed have LOGIN\-REFERRALS Pre\-login ID IDLE IMAP4rev1 OK LITERAL\+ SASL\-IR
MAC Address: 08:00:27:CD:9B:90 \(Oracle VirtualBox virtual NIC\)

**nmap \-sV \-p\- 192\.168\.0\.229 \-v
**PORT    STATE SERVICE  VERSION
80/tcp  open  http     Apache httpd 2\.4\.38 \(\(Debian\)\)
143/tcp open  imap     Dovecot imapd
993/tcp open  ssl/imap Dovecot imapd

**nikto \-url **[**http://192.168.0.229**](#http://192.168.0.229)

\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.0\.229
\+ Target Hostname:    192\.168\.0\.229
\+ Target Port:        80
\+ Start Time:         2024\-02\-15 12:30:26 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.4\.38 \(Debian\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /images: The web server may reveal its internal or real IP in the Location header via a request to with HTTP/1\.0\. The value is "127\.0\.0\.1"\. See: [http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2000-0649](#http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2000-0649)

\+ Apache/2\.4\.38 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ /: Web Server returns a valid response with junk HTTP methods which may cause false positives\.
\+ /images/: Directory indexing found\.
\+ /icons/README: Apache default file found\. See: [https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/](#https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/)

\+ 8102 requests: 0 error\(s\) and 7 item\(s\) reported on remote host
\+ End Time:           2024\-02\-15 12:30:40 \(GMT\-5\) \(14 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested

**gobuster dir \-u **[**http://192.168.0.229**](#http://192.168.0.229)
**\-w /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt \-t 100**
===============================================================
Gobuster v3\.6
by OJ Reeves \(@TheColonial\) \& Christian Mehlmauer \(@firefart\)
===============================================================
\[\+\] Url:                     [http://192.168.0.229](#http://192.168.0.229)

\[\+\] Method:                  GET
\[\+\] Threads:                 100
\[\+\] Wordlist:                /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt
\[\+\] Negative Status codes:   404
\[\+\] User Agent:              gobuster/3\.6
\[\+\] Timeout:                 10s
===============================================================
Starting gobuster in directory enumeration mode
===============================================================
/images               \(Status: 301\) \[Size: 315\] \[\-\-\> [http://192.168.0.229/images/\]](#http://192.168.0.229/images/])

/zmail                \(Status: 401\) \[Size: 460\]
/server\-status        \(Status: 403\) \[Size: 278\]
Progress: 220560 / 220561 \(100\.00%\)
