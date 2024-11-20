**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.0\.31 **
Starting Nmap 7\.93 \( [https://nmap.org](#https://nmap.org)
\) at 2023\-11\-29 00:51 EST
Pre\-scan script results:
| broadcast\-avahi\-dos: 
|   Discovered hosts:
|     224\.0\.0\.251
|   After NULL UDP avahi packet DoS \(CVE\-2011\-1002\)\.
|\_  Hosts are all up \(not vulnerable\)\.
Nmap scan report for 192\.168\.0\.31
Host is up \(0\.0014s latency\)\.
Not shown: 997 closed tcp ports \(reset\)
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
| ssh\-hostkey: 
|   2048 9cfe0b8b8d15e7727e3c23e58655512d \(RSA\)
|   256 feebef5d40e706679b6367f8d97ed3e2 \(ECDSA\)
|\_  256 3583682c338bb46c2421200d52edcd16 \(ED25519\)
| vulners: 
|   cpe:/a:openbsd:openssh:7\.9p1: 
|       EXPLOITPACK:98FE96309F9524B8C84C508837551A19    5\.8     [https://vulners.com/exploitpack/EXPLOITPACK:98FE96309F9524B8C84C508837551A19](#https://vulners.com/exploitpack/EXPLOITPACK:98FE96309F9524B8C84C508837551A19)
\*EXPLOIT\*
|       EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97    5\.8     [https://vulners.com/exploitpack/EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97](#https://vulners.com/exploitpack/EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97)
\*EXPLOIT\*
|       1337DAY\-ID\-32328        5\.8     [https://vulners.com/zdt/1337DAY-ID-32328](#https://vulners.com/zdt/1337DAY-ID-32328)
\*EXPLOIT\*
|       1337DAY\-ID\-32009        5\.8     [https://vulners.com/zdt/1337DAY-ID-32009](#https://vulners.com/zdt/1337DAY-ID-32009)
\*EXPLOIT\*
|       PRION:CVE\-2019\-16905    4\.4     [https://vulners.com/prion/PRION:CVE-2019-16905](#https://vulners.com/prion/PRION:CVE-2019-16905)

|       CVE\-2019\-16905  4\.4     [https://vulners.com/cve/CVE-2019-16905](#https://vulners.com/cve/CVE-2019-16905)

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

|\_      PACKETSTORM:151227      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:151227](#https://vulners.com/packetstorm/PACKETSTORM:151227)
\*EXPLOIT\*
80/tcp   open  http    Apache httpd 2\.4\.38 \(\(Debian\)\)
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
| http\-robots\.txt: 1 disallowed entry 
|\_/wp\-admin/
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
| vulners: 
|   cpe:/a:apache:http\_server:2\.4\.38: 
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

|       F7F6E599\-CEF4\-5E03\-8E10\-FE18C4101E38    5\.0     [https://vulners.com/githubexploit/F7F6E599-CEF4-5E03-8E10-FE18C4101E38](#https://vulners.com/githubexploit/F7F6E599-CEF4-5E03-8E10-FE18C4101E38)
\*EXPLOIT\*
|       E5C174E5\-D6E8\-56E0\-8403\-D287DE52EB3F    5\.0     [https://vulners.com/githubexploit/E5C174E5-D6E8-56E0-8403-D287DE52EB3F](#https://vulners.com/githubexploit/E5C174E5-D6E8-56E0-8403-D287DE52EB3F)
\*EXPLOIT\*
|       DB6E1BBD\-08B1\-574D\-A351\-7D6BB9898A4A    5\.0     [https://vulners.com/githubexploit/DB6E1BBD-08B1-574D-A351-7D6BB9898A4A](#https://vulners.com/githubexploit/DB6E1BBD-08B1-574D-A351-7D6BB9898A4A)
\*EXPLOIT\*
|       CVE\-2022\-37436  5\.0     [https://vulners.com/cve/CVE-2022-37436](#https://vulners.com/cve/CVE-2022-37436)

|       CVE\-2006\-20001  5\.0     [https://vulners.com/cve/CVE-2006-20001](#https://vulners.com/cve/CVE-2006-20001)

|       CNVD\-2023\-93320 5\.0     [https://vulners.com/cnvd/CNVD-2023-93320](#https://vulners.com/cnvd/CNVD-2023-93320)

|       CNVD\-2023\-80558 5\.0     [https://vulners.com/cnvd/CNVD-2023-80558](#https://vulners.com/cnvd/CNVD-2023-80558)

|       CNVD\-2022\-73122 5\.0     [https://vulners.com/cnvd/CNVD-2022-73122](#https://vulners.com/cnvd/CNVD-2022-73122)

|       CNVD\-2022\-53584 5\.0     [https://vulners.com/cnvd/CNVD-2022-53584](#https://vulners.com/cnvd/CNVD-2022-53584)

|       CNVD\-2022\-53582 5\.0     [https://vulners.com/cnvd/CNVD-2022-53582](#https://vulners.com/cnvd/CNVD-2022-53582)

|       CNVD\-2022\-03223 5\.0     [https://vulners.com/cnvd/CNVD-2022-03223](#https://vulners.com/cnvd/CNVD-2022-03223)

|       C9A1C0C1\-B6E3\-5955\-A4F1\-DEA0E505B14B    5\.0     [https://vulners.com/githubexploit/C9A1C0C1-B6E3-5955-A4F1-DEA0E505B14B](#https://vulners.com/githubexploit/C9A1C0C1-B6E3-5955-A4F1-DEA0E505B14B)
\*EXPLOIT\*
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
|\_http\-server\-header: Apache/2\.4\.38 \(Debian\)
| http\-wordpress\-users: 
| Username found: admin
|\_Search stopped at ID #25\. Increase the upper limit if necessary with 'http\-wordpress\-users\.limit'
| http\-enum: 
|   /blog/: Blog
|   /wp\-login\.php: Possible admin folder
|   /wp\-json: Possible admin folder
|   /robots\.txt: Robots file
|   /readme\.html: Wordpress version: 2 
|   /feed/: Wordpress version: 5\.4\.2
|   /wp\-includes/images/rss\.png: Wordpress version 2\.2 found\.
|   /wp\-includes/js/jquery/suggest\.js: Wordpress version 2\.5 found\.
|   /wp\-includes/images/blank\.gif: Wordpress version 2\.6 found\.
|   /wp\-includes/js/comment\-reply\.js: Wordpress version 2\.7 found\.
|   /wp\-login\.php: Wordpress login page\.
|   /wp\-admin/upgrade\.php: Wordpress login page\.
|   /readme\.html: Interesting, a readme\.
|   /0/: Potentially interesting folder
|   /contact/: Potentially interesting folder
|\_  /home/: Potentially interesting folder
|\_http\-title: Did not follow redirect to [http://sunset-midnight/](#http://sunset-midnight/)

3306/tcp open  mysql   MySQL 5\.5\.5\-10\.3\.22\-MariaDB\-0\+deb10u1
| mysql\-info: 
|   Protocol: 10
|   Version: 5\.5\.5\-10\.3\.22\-MariaDB\-0\+deb10u1
|   Thread ID: 51
|   Capabilities flags: 63486
|   Some Capabilities: Support41Auth, LongColumnFlag, Speaks41ProtocolOld, SupportsLoadDataLocal, IgnoreSigpipes, InteractiveClient, DontAllowDatabaseTableColumn, FoundRows, Speaks41ProtocolNew, SupportsCompression, ConnectWithDatabase, ODBCClient, IgnoreSpaceBeforeParenthesis, SupportsTransactions, SupportsMultipleStatments, SupportsAuthPlugins, SupportsMultipleResults
|   Status: Autocommit
|   Salt: a;B\{dbA^4'dEid91\(t17
|\_  Auth Plugin Name: mysql\_native\_password
MAC Address: 08:00:27:84:D9:19 \(Oracle VirtualBox virtual NIC\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

Service detection performed\. Please report any incorrect results at [https://nmap.org/submit/](#https://nmap.org/submit/)
\.
Nmap done: 1 IP address \(1 host up\) scanned in 73\.65 seconds

**nikto \-url 192\.168\.0\.31**
\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.0\.31
\+ Target Hostname:    192\.168\.0\.31
\+ Target Port:        80
\+ Start Time:         2023\-11\-29 00:57:39 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.4\.38 \(Debian\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: Uncommon header 'x\-redirect\-by' found, with contents: WordPress\.
\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ Root page / redirects to: [http://sunset-midnight/](#http://sunset-midnight/)

\+ /kuhptzs2\.old: Drupal Link header found with value: \<[http://sunset-midnight/wp-json/](#http://sunset-midnight/wp-json/)
\>; rel="[https://api.w.org/](#https://api.w.org/)
"\. See: [https://www.drupal.org/](#https://www.drupal.org/)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /robots\.txt: contains 2 entries which should be manually viewed\. See: [https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt](#https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt)

\+ Apache/2\.4\.38 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ /: Web Server returns a valid response with junk HTTP methods which may cause false positives\.
\+ /home/: This might be interesting\.
\+ /icons/README: Apache default file found\. See: [https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/](#https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/)

\+ /wp\-links\-opml\.php: This WordPress script reveals the installed version\.
\+ /license\.txt: License file found may identify site software\.
\+ /wp\-app\.log: Wordpress' wp\-app\.log may leak application/system details\.
\+ /wordpress/wp\-app\.log: Wordpress' wp\-app\.log may leak application/system details\.
\+ /wordpress/: A Wordpress installation was found\.
\+ /wp\-login\.php?action=register: Cookie wordpress\_test\_cookie created without the httponly flag\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

\+ /wp\-content/uploads/: Directory indexing found\.
\+ /wp\-content/uploads/: Wordpress uploads directory is browsable\. This may reveal sensitive information\.
\+ /wp\-login\.php: Wordpress login found\.
\+ 8106 requests: 0 error\(s\) and 18 item\(s\) reported on remote host
\+ End Time:           2023\-11\-29 00:59:36 \(GMT\-5\) \(117 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested

**nmap \-sV \-p\- 192\.168\.0\.31 \-v **

PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 7\.9p1 Debian 10\+deb10u2 \(protocol 2\.0\)
80/tcp   open  http    Apache httpd 2\.4\.38 \(\(Debian\)\)
3306/tcp open  mysql   MySQL 5\.5\.5\-10\.3\.22\-MariaDB\-0\+deb10u1
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**wpscan \-\-url **[**http://192.168.0.31**](#http://192.168.0.31)
**\-\-ignore\-main\-redirect**
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
\_\_          \_\_\_\_\_\_\_   \_\_\_\_\_
\\ \\        / /  \_\_ \\ / \_\_\_\_|
\\ \\  /\\  / /| |\_\_\) | \(\_\_\_   \_\_\_  \_\_ \_ \_ \_\_ ®
\\ \\/  \\/ / |  \_\_\_/ \\\_\_\_ \\ / \_\_|/ \_\` | '\_ \\
\\  /\\  /  | |     \_\_\_\_\) | \(\_\_| \(\_| | | | |
\\/  \\/   |\_|    |\_\_\_\_\_/ \\\_\_\_|\\\_\_,\_|\_| |\_|

WordPress Security Scanner by the WPScan Team
Version 3\.8\.25
Sponsored by Automattic \- [https://automattic.com/](#https://automattic.com/)

@\_WPScan\_, @ethicalhack3r, @erwan\_lr, @firefart
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

\[\+\] URL: [http://192.168.0.31/](#http://192.168.0.31/)
\[192\.168\.0\.31\]
\[\+\] Started: Wed Nov 29 01:01:41 2023

Interesting Finding\(s\):

\[\+\] Headers
| Interesting Entries:
|  \- Server: Apache/2\.4\.38 \(Debian\)
|  \- X\-Redirect\-By: WordPress
| Found By: Headers \(Passive Detection\)
| Confidence: 100%

\[\+\] robots\.txt found: [http://192.168.0.31/robots.txt](#http://192.168.0.31/robots.txt)

| Interesting Entries:
|  \- /wp\-admin/
|  \- /wp\-admin/admin\-ajax\.php
| Found By: Robots Txt \(Aggressive Detection\)
| Confidence: 100%

\[\+\] XML\-RPC seems to be enabled: [http://192.168.0.31/xmlrpc.php](#http://192.168.0.31/xmlrpc.php)

| Found By: Direct Access \(Aggressive Detection\)
| Confidence: 100%
| References:
|  \- [http://codex.wordpress.org/XML-RPC_Pingback_API](#http://codex.wordpress.org/XML-RPC_Pingback_API)

|  \- [https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_ghost_scanner/](#https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_ghost_scanner/)

|  \- [https://www.rapid7.com/db/modules/auxiliary/dos/http/wordpress_xmlrpc_dos/](#https://www.rapid7.com/db/modules/auxiliary/dos/http/wordpress_xmlrpc_dos/)

|  \- [https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_xmlrpc_login/](#https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_xmlrpc_login/)

|  \- [https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_pingback_access/](#https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_pingback_access/)


\[\+\] WordPress readme found: [http://192.168.0.31/readme.html](#http://192.168.0.31/readme.html)

| Found By: Direct Access \(Aggressive Detection\)
| Confidence: 100%

\[\+\] Upload directory has listing enabled: [http://192.168.0.31/wp-content/uploads/](#http://192.168.0.31/wp-content/uploads/)

| Found By: Direct Access \(Aggressive Detection\)
| Confidence: 100%

\[\+\] The external WP\-Cron seems to be enabled: [http://192.168.0.31/wp-cron.php](#http://192.168.0.31/wp-cron.php)

| Found By: Direct Access \(Aggressive Detection\)
| Confidence: 60%
| References:
|  \- [https://www.iplocation.net/defend-wordpress-from-ddos](#https://www.iplocation.net/defend-wordpress-from-ddos)

|  \- [https://github.com/wpscanteam/wpscan/issues/1299](#https://github.com/wpscanteam/wpscan/issues/1299)


\[\+\] WordPress version 5\.4\.2 identified \(Insecure, released on 2020\-06\-10\)\.
| Found By: Emoji Settings \(Passive Detection\)
|  \- [http://192.168.0.31/165dd2f.html,](#http://192.168.0.31/165dd2f.html,)
Match: 'wp\-includes\\/js\\/wp\-emoji\-release\.min\.js?ver=5\.4\.2'
| Confirmed By: Meta Generator \(Passive Detection\)
|  \- [http://192.168.0.31/165dd2f.html,](#http://192.168.0.31/165dd2f.html,)
Match: 'WordPress 5\.4\.2'

\[i\] The main theme could not be detected\.

\[\+\] Enumerating All Plugins \(via Passive Methods\)

\[i\] No plugins Found\.

\[\+\] Enumerating Config Backups \(via Passive and Aggressive Methods\)
Checking Config Backups \- Time: 00:00:01 \<=============================================\> \(137 / 137\) 100\.00% Time: 00:00:01

\[i\] No Config Backups Found\.

\[\!\] No WPScan API Token given, as a result vulnerability data has not been output\.
\[\!\] You can get a free API token with 25 daily requests by registering at [https://wpscan.com/register](#https://wpscan.com/register)


\[\+\] Finished: Wed Nov 29 01:01:45 2023
\[\+\] Requests Done: 163
\[\+\] Cached Requests: 7
\[\+\] Data Sent: 39\.721 KB
\[\+\] Data Received: 166\.403 KB
\[\+\] Memory used: 222\.098 MB
\[\+\] Elapsed time: 00:00:03