**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.0\.159
**Starting Nmap 7\.93 \( [https://nmap.org](#https://nmap.org)
\) at 2023\-11\-20 19:05 EST
Nmap scan report for 192\.168\.0\.159
Host is up \(0\.00086s latency\)\.
Not shown: 998 closed tcp ports \(reset\)
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 7\.6p1 Ubuntu 4ubuntu0\.3 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   2048 9c52325b8bf638c77fa1b704854954f3 \(RSA\)
|   256 d6135606153624ad655e7aa18ce564f4 \(ECDSA\)
|\_  256 1ba9f35ad05183183a23ddc4a9be59f0 \(ED25519\)
| vulners: 
|   cpe:/a:openbsd:openssh:7\.6p1: 
|       EXPLOITPACK:98FE96309F9524B8C84C508837551A19    5\.8     [https://vulners.com/exploitpack/EXPLOITPACK:98FE96309F9524B8C84C508837551A19](#https://vulners.com/exploitpack/EXPLOITPACK:98FE96309F9524B8C84C508837551A19)
\*EXPLOIT\*
|       EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97    5\.8     [https://vulners.com/exploitpack/EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97](#https://vulners.com/exploitpack/EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97)
\*EXPLOIT\*
|       1337DAY\-ID\-32328        5\.8     [https://vulners.com/zdt/1337DAY-ID-32328](#https://vulners.com/zdt/1337DAY-ID-32328)
\*EXPLOIT\*
|       1337DAY\-ID\-32009        5\.8     [https://vulners.com/zdt/1337DAY-ID-32009](#https://vulners.com/zdt/1337DAY-ID-32009)
\*EXPLOIT\*
|       SSH\_ENUM        5\.0     [https://vulners.com/canvas/SSH_ENUM](#https://vulners.com/canvas/SSH_ENUM)
\*EXPLOIT\*
|       PRION:CVE\-2018\-15919    5\.0     [https://vulners.com/prion/PRION:CVE-2018-15919](#https://vulners.com/prion/PRION:CVE-2018-15919)

|       PRION:CVE\-2018\-15473    5\.0     [https://vulners.com/prion/PRION:CVE-2018-15473](#https://vulners.com/prion/PRION:CVE-2018-15473)

|       PACKETSTORM:150621      5\.0     [https://vulners.com/packetstorm/PACKETSTORM:150621](#https://vulners.com/packetstorm/PACKETSTORM:150621)
\*EXPLOIT\*
|       EXPLOITPACK:F957D7E8A0CC1E23C3C649B764E13FB0    5\.0     [https://vulners.com/exploitpack/EXPLOITPACK:F957D7E8A0CC1E23C3C649B764E13FB0](#https://vulners.com/exploitpack/EXPLOITPACK:F957D7E8A0CC1E23C3C649B764E13FB0)
\*EXPLOIT\*
|       EXPLOITPACK:EBDBC5685E3276D648B4D14B75563283    5\.0     [https://vulners.com/exploitpack/EXPLOITPACK:EBDBC5685E3276D648B4D14B75563283](#https://vulners.com/exploitpack/EXPLOITPACK:EBDBC5685E3276D648B4D14B75563283)
\*EXPLOIT\*
|       EDB\-ID:45939    5\.0     [https://vulners.com/exploitdb/EDB-ID:45939](#https://vulners.com/exploitdb/EDB-ID:45939)
\*EXPLOIT\*
|       EDB\-ID:45233    5\.0     [https://vulners.com/exploitdb/EDB-ID:45233](#https://vulners.com/exploitdb/EDB-ID:45233)
\*EXPLOIT\*
|       CVE\-2018\-15919  5\.0     [https://vulners.com/cve/CVE-2018-15919](#https://vulners.com/cve/CVE-2018-15919)

|       CVE\-2018\-15473  5\.0     [https://vulners.com/cve/CVE-2018-15473](#https://vulners.com/cve/CVE-2018-15473)

|       1337DAY\-ID\-31730        5\.0     [https://vulners.com/zdt/1337DAY-ID-31730](#https://vulners.com/zdt/1337DAY-ID-31730)
\*EXPLOIT\*
|       PRION:CVE\-2019\-16905    4\.4     [https://vulners.com/prion/PRION:CVE-2019-16905](#https://vulners.com/prion/PRION:CVE-2019-16905)

|       CVE\-2020\-14145  4\.3     [https://vulners.com/cve/CVE-2020-14145](#https://vulners.com/cve/CVE-2020-14145)

|       PRION:CVE\-2019\-6110     4\.0     [https://vulners.com/prion/PRION:CVE-2019-6110](#https://vulners.com/prion/PRION:CVE-2019-6110)

|       PRION:CVE\-2019\-6109     4\.0     [https://vulners.com/prion/PRION:CVE-2019-6109](#https://vulners.com/prion/PRION:CVE-2019-6109)

|       EDB\-ID:46516    4\.0     [https://vulners.com/exploitdb/EDB-ID:46516](#https://vulners.com/exploitdb/EDB-ID:46516)
\*EXPLOIT\*
|       EDB\-ID:46193    4\.0     [https://vulners.com/exploitdb/EDB-ID:46193](#https://vulners.com/exploitdb/EDB-ID:46193)
\*EXPLOIT\*
|       CVE\-2019\-6110   4\.0     [https://vulners.com/cve/CVE-2019-6110](#https://vulners.com/cve/CVE-2019-6110)

|       PRION:CVE\-2019\-6111     2\.6     [https://vulners.com/prion/PRION:CVE-2019-6111](#https://vulners.com/prion/PRION:CVE-2019-6111)

|       PRION:CVE\-2018\-20685    2\.6     [https://vulners.com/prion/PRION:CVE-2018-20685](#https://vulners.com/prion/PRION:CVE-2018-20685)

|       CVE\-2018\-20685  2\.6     [https://vulners.com/cve/CVE-2018-20685](#https://vulners.com/cve/CVE-2018-20685)

|       PACKETSTORM:151227      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:151227](#https://vulners.com/packetstorm/PACKETSTORM:151227)
\*EXPLOIT\*
|       MSF:AUXILIARY\-SCANNER\-SSH\-SSH\_ENUMUSERS\-        0\.0     [https://vulners.com/metasploit/MSF:AUXILIARY-SCANNER-SSH-SSH_ENUMUSERS-](#https://vulners.com/metasploit/MSF:AUXILIARY-SCANNER-SSH-SSH_ENUMUSERS-)
\*EXPLOIT\*
|\_      1337DAY\-ID\-30937        0\.0     [https://vulners.com/zdt/1337DAY-ID-30937](#https://vulners.com/zdt/1337DAY-ID-30937)
\*EXPLOIT\*
80/tcp open  http    Apache httpd 2\.4\.29 \(\(Ubuntu\)\)
| http\-enum: 
|   /robots\.txt: Robots file
|   /phpmyadmin/: phpMyAdmin
|\_  /secret/: Potentially interesting folder
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
|\_http\-server\-header: Apache/2\.4\.29 \(Ubuntu\)
| vulners: 
|   cpe:/a:apache:http\_server:2\.4\.29: 
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
|\_http\-title: Apache2 Ubuntu Default Page: It works
MAC Address: 08:00:27:01:A8:33 \(Oracle VirtualBox virtual NIC\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

Service detection performed\. Please report any incorrect results at [https://nmap.org/submit/](#https://nmap.org/submit/)
\.
Nmap done: 1 IP address \(1 host up\) scanned in 62\.81 seconds

**nikto \-url 192\.168\.0\.159**
Server: Apache/2\.4\.29 \(Ubuntu\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /robots\.txt: contains 1 entry which should be manually viewed\. See: [https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt](#https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt)

\+ Apache/2\.4\.29 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ /: Server may leak inodes via ETags, header found with file /, inode: 2aa6, size: 5af9903d91639, mtime: gzip\. See: [http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-1418](#http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-1418)

\+ OPTIONS: Allowed HTTP Methods: OPTIONS, HEAD, GET, POST \.
\+ /phpmyadmin/changelog\.php: Uncommon header 'x\-ob\_mode' found, with contents: 1\.
\+ /secret/: This might be interesting\.
\+ /icons/README: Apache default file found\. See: [https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/](#https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/)

\+ /phpmyadmin/: phpMyAdmin directory found\.
\+ 8255 requests: 0 error\(s\) and 10 item\(s\) reported on remote host
\+ End Time:           2023\-11\-20 19:08:08 \(GMT\-5\) \(15 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested

