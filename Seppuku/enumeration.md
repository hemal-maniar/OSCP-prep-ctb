**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.0\.132**
Nmap scan report for 192\.168\.0\.132
Host is up \(0\.00055s latency\)\.
Not shown: 994 closed tcp ports \(reset\)
PORT     STATE SERVICE     VERSION
21/tcp   open  ftp         vsftpd 3\.0\.3
| vulners: 
|   cpe:/a:vsftpd:vsftpd:3\.0\.3: 
|       PRION:CVE\-2021\-3618     5\.8     [https://vulners.com/prion/PRION:CVE-2021-3618](#https://vulners.com/prion/PRION:CVE-2021-3618)

|\_      PRION:CVE\-2021\-30047    5\.0     [https://vulners.com/prion/PRION:CVE-2021-30047](#https://vulners.com/prion/PRION:CVE-2021-30047)

22/tcp   open  ssh         OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
| ssh\-hostkey: 
|   2048 cd55a8e40f28bcb2a67d4176bb9f71f4 \(RSA\)
|   256 16fa29e4e08a2e7d37d26f42b2dce922 \(ECDSA\)
|\_  256 bb74e897fa308ddaf95c99f0d9248ad5 \(ED25519\)
| vulners: 
|   cpe:/a:openbsd:openssh:7\.9p1: 
|       EXPLOITPACK:98FE96309F9524B8C84C508837551A19    5\.8     [https://vulners.com/exploitpack/EXPLOITPACK:98FE96309F9524B8C84C508837551A19](#https://vulners.com/exploitpack/EXPLOITPACK:98FE96309F9524B8C84C508837551A19)
\*EXPLOIT\*
|       EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97    5\.8     [https://vulners.com/exploitpack/EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97](#https://vulners.com/exploitpack/EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97)
\*EXPLOIT\*
|       EDB\-ID:46516    5\.8     [https://vulners.com/exploitdb/EDB-ID:46516](#https://vulners.com/exploitdb/EDB-ID:46516)
\*EXPLOIT\*
|       EDB\-ID:46193    5\.8     [https://vulners.com/exploitdb/EDB-ID:46193](#https://vulners.com/exploitdb/EDB-ID:46193)
\*EXPLOIT\*
|       1337DAY\-ID\-32328        5\.8     [https://vulners.com/zdt/1337DAY-ID-32328](#https://vulners.com/zdt/1337DAY-ID-32328)
\*EXPLOIT\*
|       1337DAY\-ID\-32009        5\.8     [https://vulners.com/zdt/1337DAY-ID-32009](#https://vulners.com/zdt/1337DAY-ID-32009)
\*EXPLOIT\*
|       PRION:CVE\-2019\-16905    4\.4     [https://vulners.com/prion/PRION:CVE-2019-16905](#https://vulners.com/prion/PRION:CVE-2019-16905)

|       CVE\-2021\-41617  4\.4     [https://vulners.com/cve/CVE-2021-41617](#https://vulners.com/cve/CVE-2021-41617)

|       CVE\-2019\-16905  4\.4     [https://vulners.com/cve/CVE-2019-16905](#https://vulners.com/cve/CVE-2019-16905)

|       CVE\-2020\-14145  4\.3     [https://vulners.com/cve/CVE-2020-14145](#https://vulners.com/cve/CVE-2020-14145)

|       PRION:CVE\-2019\-6110     4\.0     [https://vulners.com/prion/PRION:CVE-2019-6110](#https://vulners.com/prion/PRION:CVE-2019-6110)

|       PRION:CVE\-2019\-6109     4\.0     [https://vulners.com/prion/PRION:CVE-2019-6109](#https://vulners.com/prion/PRION:CVE-2019-6109)

|       CVE\-2019\-6110   4\.0     [https://vulners.com/cve/CVE-2019-6110](#https://vulners.com/cve/CVE-2019-6110)

|       PRION:CVE\-2019\-6111     2\.6     [https://vulners.com/prion/PRION:CVE-2019-6111](#https://vulners.com/prion/PRION:CVE-2019-6111)

|       PRION:CVE\-2018\-20685    2\.6     [https://vulners.com/prion/PRION:CVE-2018-20685](#https://vulners.com/prion/PRION:CVE-2018-20685)

|       CVE\-2018\-20685  2\.6     [https://vulners.com/cve/CVE-2018-20685](#https://vulners.com/cve/CVE-2018-20685)

|\_      PACKETSTORM:151227      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:151227](#https://vulners.com/packetstorm/PACKETSTORM:151227)
\*EXPLOIT\*
80/tcp   open  http        nginx 1\.14\.2
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
|\_http\-title: 401 Authorization Required
| http\-auth: 
| HTTP/1\.1 401 Unauthorized\\x0D
|\_  Basic realm=Restricted Content
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
| http\-enum: 
|\_  /info\.php: Possible information file
|\_http\-server\-header: nginx/1\.14\.2
139/tcp  open  netbios\-ssn Samba smbd 3\.X \- 4\.X \(workgroup: WORKGROUP\)
445/tcp  open  netbios\-ssn Samba smbd 4\.9\.5\-Debian \(workgroup: WORKGROUP\)
8088/tcp open  http        LiteSpeed httpd
|\_http\-vuln\-cve2017\-1001000: ERROR: Script execution failed \(use \-d to debug\)
|\_http\-server\-header: LiteSpeed
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
|\_http\-title: Seppuku
| http\-litespeed\-sourcecode\-download: 
| Litespeed Web Server Source Code Disclosure \(CVE\-2010\-2333\)
| /index\.php source code:

MAC Address: 00:0C:29:D0:82:89 \(VMware\)
Service Info: Host: SEPPUKU; OSs: Unix, Linux; CPE: cpe:/o:linux:linux\_kernel

Host script results:
|\_smb\-vuln\-ms10\-054: false
| smb2\-security\-mode: 
|   311: 
|\_    Message signing enabled but not required
| smb\-os\-discovery: 
|   OS: Windows 6\.1 \(Samba 4\.9\.5\-Debian\)
|   Computer name: seppuku
|   NetBIOS computer name: SEPPUKU\\x00
|   Domain name: \\x00
|   FQDN: seppuku
|\_  System time: 2023\-11\-24T14:15:43\-05:00
|\_nbstat: NetBIOS name: SEPPUKU, NetBIOS user: \<unknown\>, NetBIOS MAC: 000000000000 \(Xerox\)
| smb\-security\-mode: 
|   account\_used: guest
|   authentication\_level: user
|   challenge\_response: supported
|\_  message\_signing: disabled \(dangerous, but default\)
|\_clock\-skew: mean: 1h40m01s, deviation: 2h53m14s, median: 0s
| smb\-vuln\-regsvc\-dos: 
|   VULNERABLE:
|   Service regsvc in Microsoft Windows systems vulnerable to denial of service
|     State: VULNERABLE
|       The service regsvc in Microsoft Windows 2000 systems is vulnerable to denial of service caused by a null deference
|       pointer\. This script will crash the service if it is vulnerable\. This vulnerability was discovered by Ron Bowes
|       while working on smb\-enum\-sessions\.
|\_          
|\_smb\-vuln\-ms10\-061: false
| smb2\-time: 
|   date: 2023\-11\-24T19:15:40
|\_  start\_date: N/A
Nmap scan report for 192\.168\.0\.132
Host is up \(0\.00055s latency\)\.
Not shown: 994 closed tcp ports \(reset\)
PORT     STATE SERVICE     VERSION
21/tcp   open  ftp         vsftpd 3\.0\.3
| vulners: 
|   cpe:/a:vsftpd:vsftpd:3\.0\.3: 
|       PRION:CVE\-2021\-3618     5\.8     [https://vulners.com/prion/PRION:CVE-2021-3618](#https://vulners.com/prion/PRION:CVE-2021-3618)

|\_      PRION:CVE\-2021\-30047    5\.0     [https://vulners.com/prion/PRION:CVE-2021-30047](#https://vulners.com/prion/PRION:CVE-2021-30047)

22/tcp   open  ssh         OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
| ssh\-hostkey: 
|   2048 cd55a8e40f28bcb2a67d4176bb9f71f4 \(RSA\)
|   256 16fa29e4e08a2e7d37d26f42b2dce922 \(ECDSA\)
|\_  256 bb74e897fa308ddaf95c99f0d9248ad5 \(ED25519\)
| vulners: 
|   cpe:/a:openbsd:openssh:7\.9p1: 
|       EXPLOITPACK:98FE96309F9524B8C84C508837551A19    5\.8     [https://vulners.com/exploitpack/EXPLOITPACK:98FE96309F9524B8C84C508837551A19](#https://vulners.com/exploitpack/EXPLOITPACK:98FE96309F9524B8C84C508837551A19)
\*EXPLOIT\*
|       EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97    5\.8     [https://vulners.com/exploitpack/EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97](#https://vulners.com/exploitpack/EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97)
\*EXPLOIT\*
|       EDB\-ID:46516    5\.8     [https://vulners.com/exploitdb/EDB-ID:46516](#https://vulners.com/exploitdb/EDB-ID:46516)
\*EXPLOIT\*
|       EDB\-ID:46193    5\.8     [https://vulners.com/exploitdb/EDB-ID:46193](#https://vulners.com/exploitdb/EDB-ID:46193)
\*EXPLOIT\*
|       1337DAY\-ID\-32328        5\.8     [https://vulners.com/zdt/1337DAY-ID-32328](#https://vulners.com/zdt/1337DAY-ID-32328)
\*EXPLOIT\*
|       1337DAY\-ID\-32009        5\.8     [https://vulners.com/zdt/1337DAY-ID-32009](#https://vulners.com/zdt/1337DAY-ID-32009)
\*EXPLOIT\*
|       PRION:CVE\-2019\-16905    4\.4     [https://vulners.com/prion/PRION:CVE-2019-16905](#https://vulners.com/prion/PRION:CVE-2019-16905)

|       CVE\-2021\-41617  4\.4     [https://vulners.com/cve/CVE-2021-41617](#https://vulners.com/cve/CVE-2021-41617)

|       CVE\-2019\-16905  4\.4     [https://vulners.com/cve/CVE-2019-16905](#https://vulners.com/cve/CVE-2019-16905)

|       CVE\-2020\-14145  4\.3     [https://vulners.com/cve/CVE-2020-14145](#https://vulners.com/cve/CVE-2020-14145)

|       PRION:CVE\-2019\-6110     4\.0     [https://vulners.com/prion/PRION:CVE-2019-6110](#https://vulners.com/prion/PRION:CVE-2019-6110)

|       PRION:CVE\-2019\-6109     4\.0     [https://vulners.com/prion/PRION:CVE-2019-6109](#https://vulners.com/prion/PRION:CVE-2019-6109)

|       CVE\-2019\-6110   4\.0     [https://vulners.com/cve/CVE-2019-6110](#https://vulners.com/cve/CVE-2019-6110)

|       PRION:CVE\-2019\-6111     2\.6     [https://vulners.com/prion/PRION:CVE-2019-6111](#https://vulners.com/prion/PRION:CVE-2019-6111)

|       PRION:CVE\-2018\-20685    2\.6     [https://vulners.com/prion/PRION:CVE-2018-20685](#https://vulners.com/prion/PRION:CVE-2018-20685)

|       CVE\-2018\-20685  2\.6     [https://vulners.com/cve/CVE-2018-20685](#https://vulners.com/cve/CVE-2018-20685)

|\_      PACKETSTORM:151227      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:151227](#https://vulners.com/packetstorm/PACKETSTORM:151227)
\*EXPLOIT\*
80/tcp   open  http        nginx 1\.14\.2
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
|\_http\-title: 401 Authorization Required
| http\-auth: 
| HTTP/1\.1 401 Unauthorized\\x0D
|\_  Basic realm=Restricted Content
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
| http\-enum: 
|\_  /info\.php: Possible information file
|\_http\-server\-header: nginx/1\.14\.2
139/tcp  open  netbios\-ssn Samba smbd 3\.X \- 4\.X \(workgroup: WORKGROUP\)
445/tcp  open  netbios\-ssn Samba smbd 4\.9\.5\-Debian \(workgroup: WORKGROUP\)
8088/tcp open  http        LiteSpeed httpd
|\_http\-vuln\-cve2017\-1001000: ERROR: Script execution failed \(use \-d to debug\)
|\_http\-server\-header: LiteSpeed
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
|\_http\-title: Seppuku
| http\-litespeed\-sourcecode\-download: 
| Litespeed Web Server Source Code Disclosure \(CVE\-2010\-2333\)
| /index\.php source code:

MAC Address: 00:0C:29:D0:82:89 \(VMware\)
Service Info: Host: SEPPUKU; OSs: Unix, Linux; CPE: cpe:/o:linux:linux\_kernel

Host script results:
|\_smb\-vuln\-ms10\-054: false
| smb2\-security\-mode: 
|   311: 
|\_    Message signing enabled but not required
| smb\-os\-discovery: 
|   OS: Windows 6\.1 \(Samba 4\.9\.5\-Debian\)
|   Computer name: seppuku
|   NetBIOS computer name: SEPPUKU\\x00
|   Domain name: \\x00
|   FQDN: seppuku
|\_  System time: 2023\-11\-24T14:15:43\-05:00
|\_nbstat: NetBIOS name: SEPPUKU, NetBIOS user: \<unknown\>, NetBIOS MAC: 000000000000 \(Xerox\)
| smb\-security\-mode: 
|   account\_used: guest
|   authentication\_level: user
|   challenge\_response: supported
|\_  message\_signing: disabled \(dangerous, but default\)
|\_clock\-skew: mean: 1h40m01s, deviation: 2h53m14s, median: 0s
| smb\-vuln\-regsvc\-dos: 
|   VULNERABLE:
|   Service regsvc in Microsoft Windows systems vulnerable to denial of service
|     State: VULNERABLE
|       The service regsvc in Microsoft Windows 2000 systems is vulnerable to denial of service caused by a null deference
|       pointer\. This script will crash the service if it is vulnerable\. This vulnerability was discovered by Ron Bowes
|       while working on smb\-enum\-sessions\.
|\_          
|\_smb\-vuln\-ms10\-061: false
| smb2\-time: 
|   date: 2023\-11\-24T19:15:40
|\_  start\_date: N/A

**nikto \-url 192\.168\.0\.132**
\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.0\.132
\+ Target Hostname:    192\.168\.0\.132
\+ Target Port:        80
\+ Start Time:         2023\-11\-24 15:37:07 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: nginx/1\.14\.2
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ / \- Requires Authentication for realm 'Restricted Content'
\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /info\.php: Output from the phpinfo\(\) function was found\.
\+ /info\.php: PHP is installed, and a test script which runs phpinfo\(\) was found\. This gives a lot of system information\. See: CWE\-552
\+ /info\.php?file=[http://blog.cirt.net/rfiinc.txt:](#http://blog.cirt.net/rfiinc.txt:)
Remote File Inclusion \(RFI\) from RSnake's RFI list\. See: [https://gist.github.com/mubix/5d269c686584875015a2](#https://gist.github.com/mubix/5d269c686584875015a2)

\+ 8253 requests: 0 error\(s\) and 5 item\(s\) reported on remote host
\+ End Time:           2023\-11\-24 15:37:19 \(GMT\-5\) \(12 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested

**nmap \-sV \-p\- 192\.168\.0\.132 \-v   **
Starting Nmap 7\.93 \( [https://nmap.org](#https://nmap.org)
\) at 2023\-11\-25 02:21 EST
NSE: Loaded 45 scripts for scanning\.
Initiating Ping Scan at 02:21
Scanning 192\.168\.0\.132 \[2 ports\]
Completed Ping Scan at 02:21, 0\.00s elapsed \(1 total hosts\)
Initiating Parallel DNS resolution of 1 host\. at 02:21
Completed Parallel DNS resolution of 1 host\. at 02:21, 0\.01s elapsed
Initiating Connect Scan at 02:21
Scanning 192\.168\.0\.132 \[65535 ports\]
Discovered open port 80/tcp on 192\.168\.0\.132
Discovered open port 21/tcp on 192\.168\.0\.132
Discovered open port 22/tcp on 192\.168\.0\.132
Discovered open port 445/tcp on 192\.168\.0\.132
Discovered open port 139/tcp on 192\.168\.0\.132
Discovered open port 7080/tcp on 192\.168\.0\.132
Discovered open port 7601/tcp on 192\.168\.0\.132
Discovered open port 8088/tcp on 192\.168\.0\.132
Completed Connect Scan at 02:21, 2\.63s elapsed \(65535 total ports\)
Initiating Service scan at 02:21
Scanning 8 services on 192\.168\.0\.132
Completed Service scan at 02:21, 22\.09s elapsed \(8 services on 1 host\)
NSE: Script scanning 192\.168\.0\.132\.
Initiating NSE at 02:21
Completed NSE at 02:21, 0\.11s elapsed
Initiating NSE at 02:21
Completed NSE at 02:21, 0\.10s elapsed
Nmap scan report for 192\.168\.0\.132
Host is up \(0\.00037s latency\)\.
Not shown: 65527 closed tcp ports \(conn\-refused\)
PORT     STATE SERVICE     VERSION
21/tcp   open  ftp         vsftpd 3\.0\.3
22/tcp   open  ssh         OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
80/tcp   open  http        nginx 1\.14\.2
139/tcp  open  netbios\-ssn Samba smbd 3\.X \- 4\.X \(workgroup: WORKGROUP\)
445/tcp  open  netbios\-ssn Samba smbd 3\.X \- 4\.X \(workgroup: WORKGROUP\)
7080/tcp open  ssl/http    LiteSpeed httpd
7601/tcp open  http        Apache httpd 2\.4\.38 \(\(Debian\)\)
8088/tcp open  http        LiteSpeed httpd
Service Info: Host: SEPPUKU; OSs: Unix, Linux; CPE: cpe:/o:linux:linux\_kernel

Read data files from: /usr/bin/\.\./share/nmap
Service detection performed\. Please report any incorrect results at [https://nmap.org/submit/](#https://nmap.org/submit/)
\.
Nmap done: 1 IP address \(1 host up\) scanned in 25\.33 seconds

**gobuster dir \-u **[**http://192.168.0.132:7601**](#http://192.168.0.132:7601)
**\-w /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt \-t 100 \-x php,txt**
===============================================================
Gobuster v3\.6
by OJ Reeves \(@TheColonial\) \& Christian Mehlmauer \(@firefart\)
===============================================================
\[\+\] Url:                     [http://192.168.0.132:7601](#http://192.168.0.132:7601)

\[\+\] Method:                  GET
\[\+\] Threads:                 100
\[\+\] Wordlist:                /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt
\[\+\] Negative Status codes:   404
\[\+\] User Agent:              gobuster/3\.6
\[\+\] Extensions:              php,txt
\[\+\] Timeout:                 10s
===============================================================
Starting gobuster in directory enumeration mode
===============================================================
/a                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/a/\]](#http://192.168.0.132:7601/a/])

/b                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/b/\]](#http://192.168.0.132:7601/b/])

/c                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/c/\]](#http://192.168.0.132:7601/c/])

/t                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/t/\]](#http://192.168.0.132:7601/t/])

/r                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/r/\]](#http://192.168.0.132:7601/r/])

/d                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/d/\]](#http://192.168.0.132:7601/d/])

/f                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/f/\]](#http://192.168.0.132:7601/f/])

/e                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/e/\]](#http://192.168.0.132:7601/e/])

/h                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/h/\]](#http://192.168.0.132:7601/h/])

/w                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/w](#http://192.168.0.132:7601/w)
\] -  found password\.lst
/q                    \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.0.132:7601/q/\]](#http://192.168.0.132:7601/q/])

/database             \(Status: 301\) \[Size: 324\] \[\-\-\> [http://192.168.0.132:7601/database/\]](#http://192.168.0.132:7601/database/])

/production           \(Status: 301\) \[Size: 326\] \[\-\-\> [http://192.168.0.132:7601/production/\]](#http://192.168.0.132:7601/production/])

/keys                 \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.0.132:7601/keys/](#http://192.168.0.132:7601/keys/)
[\]](#http://192.168.0.132:7601/keys/])
-  found RSA private key and its backup
/secret               \(Status: 301\) \[Size: 322\] \[\-\-\> [http://192.168.0.132:7601/secret/](#http://192.168.0.132:7601/secret/)
[\]](#http://192.168.0.132:7601/secret/])
-  found same files along with shadow\.bk
/stg                  \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.0.132:7601/stg/\]](#http://192.168.0.132:7601/stg/])

/server\-status        \(Status: 403\) \[Size: 280\]go