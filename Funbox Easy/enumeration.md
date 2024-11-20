**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.0\.22 
**
Starting Nmap 7\.93 \( [https://nmap.org](#https://nmap.org)
\) at 2023\-11\-20 17:59 EST
Pre\-scan script results:
| broadcast\-avahi\-dos: 
|   Discovered hosts:
|     224\.0\.0\.251
|   After NULL UDP avahi packet DoS \(CVE\-2011\-1002\)\.
|\_  Hosts are all up \(not vulnerable\)\.
Nmap scan report for 192\.168\.0\.22
Host is up \(0\.00055s latency\)\.
Not shown: 998 closed tcp ports \(reset\)
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.1 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 b2d8516ec584051908ebc8582713132f \(RSA\)
|   256 b0de9703a72ff4e2ab4a9cd9439b8a48 \(ECDSA\)
|\_  256 9d0f9a26384f0180a7a6809dd1d4cfec \(ED25519\)
| vulners: 
|   cpe:/a:openbsd:openssh:8\.2p1: 
|       PRION:CVE\-2020\-12062    5\.0     [https://vulners.com/prion/PRION:CVE-2020-12062](#https://vulners.com/prion/PRION:CVE-2020-12062)

|       PRION:CVE\-2021\-28041    4\.6     [https://vulners.com/prion/PRION:CVE-2021-28041](#https://vulners.com/prion/PRION:CVE-2021-28041)

|       PRION:CVE\-2020\-15778    4\.4     [https://vulners.com/prion/PRION:CVE-2020-15778](#https://vulners.com/prion/PRION:CVE-2020-15778)

|       PRION:CVE\-2020\-14145    4\.3     [https://vulners.com/prion/PRION:CVE-2020-14145](#https://vulners.com/prion/PRION:CVE-2020-14145)

|       CVE\-2020\-14145  4\.3     [https://vulners.com/cve/CVE-2020-14145](#https://vulners.com/cve/CVE-2020-14145)

|       PRION:CVE\-2021\-41617    3\.5     [https://vulners.com/prion/PRION:CVE-2021-41617](#https://vulners.com/prion/PRION:CVE-2021-41617)

|\_      PRION:CVE\-2021\-36368    2\.6     [https://vulners.com/prion/PRION:CVE-2021-36368](#https://vulners.com/prion/PRION:CVE-2021-36368)

80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
|\_http\-title: Apache2 Ubuntu Default Page: It works
| http\-enum: 
|   /admin/: Possible admin folder
|   /admin/index\.php: Possible admin folder
|   /robots\.txt: Robots file
|   /secret/: Potentially interesting folder
|\_  /store/: Potentially interesting folder
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
|\_http\-server\-header: Apache/2\.4\.41 \(Ubuntu\)
| http\-cookie\-flags: 
|   /admin/: 
|     PHPSESSID: 
|       httponly flag not set
|   /admin/index\.php: 
|     PHPSESSID: 
|       httponly flag not set
|   /store/: 
|     PHPSESSID: 
|\_      httponly flag not set
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
| vulners: 
|   cpe:/a:apache:http\_server:2\.4\.41: 
|       PACKETSTORM:171631      7\.5     [https://vulners.com/packetstorm/PACKETSTORM:171631](#https://vulners.com/packetstorm/PACKETSTORM:171631)
\*EXPLOIT\*
|       EDB\-ID:51193    7\.5     [https://vulners.com/exploitdb/EDB-ID:51193](#https://vulners.com/exploitdb/EDB-ID:51193)
\*EXPLOIT\*
|       CNVD\-2022\-73123 7\.5     [https://vulners.com/cnvd/CNVD-2022-73123](#https://vulners.com/cnvd/CNVD-2022-73123)

|       CNVD\-2022\-03225 7\.5     [https://vulners.com/cnvd/CNVD-2022-03225](#https://vulners.com/cnvd/CNVD-2022-03225)

|       CNVD\-2021\-102386        7\.5     [https://vulners.com/cnvd/CNVD-2021-102386](#https://vulners.com/cnvd/CNVD-2021-102386)

|       1337DAY\-ID\-38427        7\.5     [https://vulners.com/zdt/1337DAY-ID-38427](#https://vulners.com/zdt/1337DAY-ID-38427)
\*EXPLOIT\*
|       CNVD\-2022\-03224 6\.8     [https://vulners.com/cnvd/CNVD-2022-03224](#https://vulners.com/cnvd/CNVD-2022-03224)

|       OSV:BIT\-2023\-31122      6\.4     [https://vulners.com/osv/OSV:BIT-2023-31122](#https://vulners.com/osv/OSV:BIT-2023-31122)

|       CVE\-2022\-36760  5\.1     [https://vulners.com/cve/CVE-2022-36760](#https://vulners.com/cve/CVE-2022-36760)

|       8AFB43C5\-ABD4\-52AD\-BB19\-24D7884FF2A2    5\.1     [https://vulners.com/githubexploit/8AFB43C5-ABD4-52AD-BB19-24D7884FF2A2](#https://vulners.com/githubexploit/8AFB43C5-ABD4-52AD-BB19-24D7884FF2A2)
\*EXPLOIT\*
|       4810E2D9\-AC5F\-5B08\-BFB3\-DDAFA2F63332    5\.1     [https://vulners.com/githubexploit/4810E2D9-AC5F-5B08-BFB3-DDAFA2F63332](#https://vulners.com/githubexploit/4810E2D9-AC5F-5B08-BFB3-DDAFA2F63332)
\*EXPLOIT\*
|       4373C92A\-2755\-5538\-9C91\-0469C995AA9B    5\.1     [https://vulners.com/githubexploit/4373C92A-2755-5538-9C91-0469C995AA9B](#https://vulners.com/githubexploit/4373C92A-2755-5538-9C91-0469C995AA9B)
\*EXPLOIT\*
|       OSV:BIT\-2023\-45802      5\.0     [https://vulners.com/osv/OSV:BIT-2023-45802](#https://vulners.com/osv/OSV:BIT-2023-45802)

|       OSV:BIT\-2023\-43622      5\.0     [https://vulners.com/osv/OSV:BIT-2023-43622](#https://vulners.com/osv/OSV:BIT-2023-43622)

|       E5C174E5\-D6E8\-56E0\-8403\-D287DE52EB3F    5\.0     [https://vulners.com/githubexploit/E5C174E5-D6E8-56E0-8403-D287DE52EB3F](#https://vulners.com/githubexploit/E5C174E5-D6E8-56E0-8403-D287DE52EB3F)
\*EXPLOIT\*
|       DB6E1BBD\-08B1\-574D\-A351\-7D6BB9898A4A    5\.0     [https://vulners.com/githubexploit/DB6E1BBD-08B1-574D-A351-7D6BB9898A4A](#https://vulners.com/githubexploit/DB6E1BBD-08B1-574D-A351-7D6BB9898A4A)
\*EXPLOIT\*
|       CVE\-2022\-37436  5\.0     [https://vulners.com/cve/CVE-2022-37436](#https://vulners.com/cve/CVE-2022-37436)

|       CVE\-2006\-20001  5\.0     [https://vulners.com/cve/CVE-2006-20001](#https://vulners.com/cve/CVE-2006-20001)

|       CNVD\-2023\-80558 5\.0     [https://vulners.com/cnvd/CNVD-2023-80558](#https://vulners.com/cnvd/CNVD-2023-80558)

|       CNVD\-2022\-73122 5\.0     [https://vulners.com/cnvd/CNVD-2022-73122](#https://vulners.com/cnvd/CNVD-2022-73122)

|       CNVD\-2022\-53584 5\.0     [https://vulners.com/cnvd/CNVD-2022-53584](#https://vulners.com/cnvd/CNVD-2022-53584)

|       CNVD\-2022\-53582 5\.0     [https://vulners.com/cnvd/CNVD-2022-53582](#https://vulners.com/cnvd/CNVD-2022-53582)

|       CNVD\-2022\-03223 5\.0     [https://vulners.com/cnvd/CNVD-2022-03223](#https://vulners.com/cnvd/CNVD-2022-03223)

|       BD3652A9\-D066\-57BA\-9943\-4E34970463B9    5\.0     [https://vulners.com/githubexploit/BD3652A9-D066-57BA-9943-4E34970463B9](#https://vulners.com/githubexploit/BD3652A9-D066-57BA-9943-4E34970463B9)
\*EXPLOIT\*
|       B0208442\-6E17\-5772\-B12D\-B5BE30FA5540    5\.0     [https://vulners.com/githubexploit/B0208442-6E17-5772-B12D-B5BE30FA5540](#https://vulners.com/githubexploit/B0208442-6E17-5772-B12D-B5BE30FA5540)
\*EXPLOIT\*
|       A820A056\-9F91\-5059\-B0BC\-8D92C7A31A52    5\.0     [https://vulners.com/githubexploit/A820A056-9F91-5059-B0BC-8D92C7A31A52](#https://vulners.com/githubexploit/A820A056-9F91-5059-B0BC-8D92C7A31A52)
\*EXPLOIT\*
|       9814661A\-35A4\-5DB7\-BB25\-A1040F365C81    5\.0     [https://vulners.com/githubexploit/9814661A-35A4-5DB7-BB25-A1040F365C81](#https://vulners.com/githubexploit/9814661A-35A4-5DB7-BB25-A1040F365C81)
\*EXPLOIT\*
|\_      17C6AD2A\-8469\-56C8\-BBBE\-1764D0DF1680    5\.0     [https://vulners.com/githubexploit/17C6AD2A-8469-56C8-BBBE-1764D0DF1680](#https://vulners.com/githubexploit/17C6AD2A-8469-56C8-BBBE-1764D0DF1680)
\*EXPLOIT\*
|\_http\-vuln\-cve2017\-1001000: ERROR: Script execution failed \(use \-d to debug\)
| http\-robots\.txt: 1 disallowed entry 
|\_gym
MAC Address: 08:00:27:58:32:65 \(Oracle VirtualBox virtual NIC\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

Service detection performed\. Please report any incorrect results at [https://nmap.org/submit/](#https://nmap.org/submit/)
\.
Nmap done: 1 IP address \(1 host up\) scanned in 63\.48 seconds

**nikto \-url 192\.168\.0\.22
**\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.0\.22
\+ Target Hostname:    192\.168\.0\.22
\+ Target Port:        80
\+ Start Time:         2023\-11\-20 18:01:47 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.4\.41 \(Ubuntu\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ /index\.php?: Cookie PHPSESSID created without the httponly flag\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /robots\.txt: contains 1 entry which should be manually viewed\. See: [https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt](#https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt)

\+ Apache/2\.4\.41 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ Multiple index files found: /index\.html, /index\.php\.
\+ /: Server may leak inodes via ETags, header found with file /, inode: 2aa6, size: 5abac58e39aeb, mtime: gzip\. See: [http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-1418](#http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-1418)

\+ OPTIONS: Allowed HTTP Methods: GET, POST, OPTIONS, HEAD \.
\+ /admin/: This might be interesting\.
\+ /secret/: This might be interesting\.
\+ /store/: This might be interesting\.
\+ /admin/index\.php: This might be interesting: has been seen in web logs from an unknown scanner\.
\+ 8103 requests: 0 error\(s\) and 12 item\(s\) reported on remote host
\+ End Time:           2023\-11\-20 18:02:02 \(GMT\-5\) \(15 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested

**sudo nmap \-sV \-p\- 192\.168\.0\.22
**
