**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.0\.131**
Starting Nmap 7\.93 \( [https://nmap.org](#https://nmap.org)
\) at 2023\-12\-06 16:58 EST

Nmap scan report for 192\.168\.0\.131
Host is up \(0\.0013s latency\)\.
Not shown: 999 closed tcp ports \(reset\)
PORT   STATE SERVICE VERSION
80/tcp open  http    Apache httpd 2\.4\.10 \(\(Debian\)\)
|\_http\-title: Did not follow redirect to [http://dc-2/](#http://dc-2/)

|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
| http\-wordpress\-users: 
| Username found: admin
| Username found: tom
| Username found: jerry
|\_Search stopped at ID #25\. Increase the upper limit if necessary with 'http\-wordpress\-users\.limit'
|\_http\-server\-header: Apache/2\.4\.10 \(Debian\)
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
| vulners: 
|   cpe:/a:apache:http\_server:2\.4\.10: 
|       PACKETSTORM:171631      7\.5     [https://vulners.com/packetstorm/PACKETSTORM:171631](#https://vulners.com/packetstorm/PACKETSTORM:171631)
\*EXPLOIT\*
|       EDB\-ID:51193    7\.5     [https://vulners.com/exploitdb/EDB-ID:51193](#https://vulners.com/exploitdb/EDB-ID:51193)
\*EXPLOIT\*
|       CVE\-2022\-31813  7\.5     [https://vulners.com/cve/CVE-2022-31813](#https://vulners.com/cve/CVE-2022-31813)

|       CVE\-2022\-23943  7\.5     [https://vulners.com/cve/CVE-2022-23943](#https://vulners.com/cve/CVE-2022-23943)

|       CVE\-2022\-22720  7\.5     [https://vulners.com/cve/CVE-2022-22720](#https://vulners.com/cve/CVE-2022-22720)

|       CVE\-2021\-44790  7\.5     [https://vulners.com/cve/CVE-2021-44790](#https://vulners.com/cve/CVE-2021-44790)

|       CVE\-2021\-39275  7\.5     [https://vulners.com/cve/CVE-2021-39275](#https://vulners.com/cve/CVE-2021-39275)

|       CVE\-2021\-26691  7\.5     [https://vulners.com/cve/CVE-2021-26691](#https://vulners.com/cve/CVE-2021-26691)

|       CVE\-2017\-7679   7\.5     [https://vulners.com/cve/CVE-2017-7679](#https://vulners.com/cve/CVE-2017-7679)

|       CVE\-2017\-3169   7\.5     [https://vulners.com/cve/CVE-2017-3169](#https://vulners.com/cve/CVE-2017-3169)

|       CVE\-2017\-3167   7\.5     [https://vulners.com/cve/CVE-2017-3167](#https://vulners.com/cve/CVE-2017-3167)

|       CNVD\-2022\-73123 7\.5     [https://vulners.com/cnvd/CNVD-2022-73123](#https://vulners.com/cnvd/CNVD-2022-73123)

|       CNVD\-2022\-03225 7\.5     [https://vulners.com/cnvd/CNVD-2022-03225](#https://vulners.com/cnvd/CNVD-2022-03225)

|       CNVD\-2021\-102386        7\.5     [https://vulners.com/cnvd/CNVD-2021-102386](#https://vulners.com/cnvd/CNVD-2021-102386)

|       1337DAY\-ID\-38427        7\.5     [https://vulners.com/zdt/1337DAY-ID-38427](#https://vulners.com/zdt/1337DAY-ID-38427)
\*EXPLOIT\*
|       FDF3DFA1\-ED74\-5EE2\-BF5C\-BA752CA34AE8    6\.8     [https://vulners.com/githubexploit/FDF3DFA1-ED74-5EE2-BF5C-BA752CA34AE8](#https://vulners.com/githubexploit/FDF3DFA1-ED74-5EE2-BF5C-BA752CA34AE8)
\*EXPLOIT\*
|       CVE\-2021\-40438  6\.8     [https://vulners.com/cve/CVE-2021-40438](#https://vulners.com/cve/CVE-2021-40438)

|       CVE\-2020\-35452  6\.8     [https://vulners.com/cve/CVE-2020-35452](#https://vulners.com/cve/CVE-2020-35452)

|       CVE\-2018\-1312   6\.8     [https://vulners.com/cve/CVE-2018-1312](#https://vulners.com/cve/CVE-2018-1312)

|       CVE\-2017\-15715  6\.8     [https://vulners.com/cve/CVE-2017-15715](#https://vulners.com/cve/CVE-2017-15715)

|       CVE\-2016\-5387   6\.8     [https://vulners.com/cve/CVE-2016-5387](#https://vulners.com/cve/CVE-2016-5387)

|       CVE\-2014\-0226   6\.8     [https://vulners.com/cve/CVE-2014-0226](#https://vulners.com/cve/CVE-2014-0226)

|       CNVD\-2022\-03224 6\.8     [https://vulners.com/cnvd/CNVD-2022-03224](#https://vulners.com/cnvd/CNVD-2022-03224)

|       8AFB43C5\-ABD4\-52AD\-BB19\-24D7884FF2A2    6\.8     [https://vulners.com/githubexploit/8AFB43C5-ABD4-52AD-BB19-24D7884FF2A2](#https://vulners.com/githubexploit/8AFB43C5-ABD4-52AD-BB19-24D7884FF2A2)
\*EXPLOIT\*
|       4810E2D9\-AC5F\-5B08\-BFB3\-DDAFA2F63332    6\.8     [https://vulners.com/githubexploit/4810E2D9-AC5F-5B08-BFB3-DDAFA2F63332](#https://vulners.com/githubexploit/4810E2D9-AC5F-5B08-BFB3-DDAFA2F63332)
\*EXPLOIT\*
|       4373C92A\-2755\-5538\-9C91\-0469C995AA9B    6\.8     [https://vulners.com/githubexploit/4373C92A-2755-5538-9C91-0469C995AA9B](#https://vulners.com/githubexploit/4373C92A-2755-5538-9C91-0469C995AA9B)
\*EXPLOIT\*
|       0095E929\-7573\-5E4A\-A7FA\-F6598A35E8DE    6\.8     [https://vulners.com/githubexploit/0095E929-7573-5E4A-A7FA-F6598A35E8DE](#https://vulners.com/githubexploit/0095E929-7573-5E4A-A7FA-F6598A35E8DE)
\*EXPLOIT\*
|       OSV:BIT\-2023\-31122      6\.4     [https://vulners.com/osv/OSV:BIT-2023-31122](#https://vulners.com/osv/OSV:BIT-2023-31122)

|       CVE\-2022\-28615  6\.4     [https://vulners.com/cve/CVE-2022-28615](#https://vulners.com/cve/CVE-2022-28615)

|       CVE\-2021\-44224  6\.4     [https://vulners.com/cve/CVE-2021-44224](#https://vulners.com/cve/CVE-2021-44224)

|       CVE\-2017\-9788   6\.4     [https://vulners.com/cve/CVE-2017-9788](#https://vulners.com/cve/CVE-2017-9788)

|       CVE\-2019\-0217   6\.0     [https://vulners.com/cve/CVE-2019-0217](#https://vulners.com/cve/CVE-2019-0217)

|       CVE\-2022\-22721  5\.8     [https://vulners.com/cve/CVE-2022-22721](#https://vulners.com/cve/CVE-2022-22721)

|       CVE\-2020\-1927   5\.8     [https://vulners.com/cve/CVE-2020-1927](#https://vulners.com/cve/CVE-2020-1927)

|       CVE\-2019\-10098  5\.8     [https://vulners.com/cve/CVE-2019-10098](#https://vulners.com/cve/CVE-2019-10098)

|       1337DAY\-ID\-33577        5\.8     [https://vulners.com/zdt/1337DAY-ID-33577](#https://vulners.com/zdt/1337DAY-ID-33577)
\*EXPLOIT\*
|       CVE\-2022\-36760  5\.1     [https://vulners.com/cve/CVE-2022-36760](#https://vulners.com/cve/CVE-2022-36760)

|       SSV:96537       5\.0     [https://vulners.com/seebug/SSV:96537](#https://vulners.com/seebug/SSV:96537)
\*EXPLOIT\*
|       SSV:62058       5\.0     [https://vulners.com/seebug/SSV:62058](#https://vulners.com/seebug/SSV:62058)
\*EXPLOIT\*
|       OSV:BIT\-2023\-45802      5\.0     [https://vulners.com/osv/OSV:BIT-2023-45802](#https://vulners.com/osv/OSV:BIT-2023-45802)

|       OSV:BIT\-2023\-43622      5\.0     [https://vulners.com/osv/OSV:BIT-2023-43622](#https://vulners.com/osv/OSV:BIT-2023-43622)

|       F7F6E599\-CEF4\-5E03\-8E10\-FE18C4101E38    5\.0     [https://vulners.com/githubexploit/F7F6E599-CEF4-5E03-8E10-FE18C4101E38](#https://vulners.com/githubexploit/F7F6E599-CEF4-5E03-8E10-FE18C4101E38)
\*EXPLOIT\*
|       EXPLOITPACK:DAED9B9E8D259B28BF72FC7FDC4755A7    5\.0     [https://vulners.com/exploitpack/EXPLOITPACK:DAED9B9E8D259B28BF72FC7FDC4755A7](#https://vulners.com/exploitpack/EXPLOITPACK:DAED9B9E8D259B28BF72FC7FDC4755A7)
\*EXPLOIT\*
|       EXPLOITPACK:C8C256BE0BFF5FE1C0405CB0AA9C075D    5\.0     [https://vulners.com/exploitpack/EXPLOITPACK:C8C256BE0BFF5FE1C0405CB0AA9C075D](#https://vulners.com/exploitpack/EXPLOITPACK:C8C256BE0BFF5FE1C0405CB0AA9C075D)
\*EXPLOIT\*
|       EDB\-ID:42745    5\.0     [https://vulners.com/exploitdb/EDB-ID:42745](#https://vulners.com/exploitdb/EDB-ID:42745)
\*EXPLOIT\*
|       EDB\-ID:40961    5\.0     [https://vulners.com/exploitdb/EDB-ID:40961](#https://vulners.com/exploitdb/EDB-ID:40961)
\*EXPLOIT\*
|       E5C174E5\-D6E8\-56E0\-8403\-D287DE52EB3F    5\.0     [https://vulners.com/githubexploit/E5C174E5-D6E8-56E0-8403-D287DE52EB3F](#https://vulners.com/githubexploit/E5C174E5-D6E8-56E0-8403-D287DE52EB3F)
\*EXPLOIT\*
|       DB6E1BBD\-08B1\-574D\-A351\-7D6BB9898A4A    5\.0     [https://vulners.com/githubexploit/DB6E1BBD-08B1-574D-A351-7D6BB9898A4A](#https://vulners.com/githubexploit/DB6E1BBD-08B1-574D-A351-7D6BB9898A4A)
\*EXPLOIT\*
|       CVE\-2022\-37436  5\.0     [https://vulners.com/cve/CVE-2022-37436](#https://vulners.com/cve/CVE-2022-37436)

|       CVE\-2022\-30556  5\.0     [https://vulners.com/cve/CVE-2022-30556](#https://vulners.com/cve/CVE-2022-30556)

|       CVE\-2022\-29404  5\.0     [https://vulners.com/cve/CVE-2022-29404](#https://vulners.com/cve/CVE-2022-29404)

|       CVE\-2022\-28614  5\.0     [https://vulners.com/cve/CVE-2022-28614](#https://vulners.com/cve/CVE-2022-28614)

|       CVE\-2022\-26377  5\.0     [https://vulners.com/cve/CVE-2022-26377](#https://vulners.com/cve/CVE-2022-26377)

|       CVE\-2022\-22719  5\.0     [https://vulners.com/cve/CVE-2022-22719](#https://vulners.com/cve/CVE-2022-22719)

|       CVE\-2021\-34798  5\.0     [https://vulners.com/cve/CVE-2021-34798](#https://vulners.com/cve/CVE-2021-34798)

|       CVE\-2021\-26690  5\.0     [https://vulners.com/cve/CVE-2021-26690](#https://vulners.com/cve/CVE-2021-26690)

|       CVE\-2020\-1934   5\.0     [https://vulners.com/cve/CVE-2020-1934](#https://vulners.com/cve/CVE-2020-1934)

|       CVE\-2019\-17567  5\.0     [https://vulners.com/cve/CVE-2019-17567](#https://vulners.com/cve/CVE-2019-17567)

|       CVE\-2019\-0220   5\.0     [https://vulners.com/cve/CVE-2019-0220](#https://vulners.com/cve/CVE-2019-0220)

|       CVE\-2018\-17199  5\.0     [https://vulners.com/cve/CVE-2018-17199](#https://vulners.com/cve/CVE-2018-17199)

|       CVE\-2018\-1303   5\.0     [https://vulners.com/cve/CVE-2018-1303](#https://vulners.com/cve/CVE-2018-1303)

|       CVE\-2017\-9798   5\.0     [https://vulners.com/cve/CVE-2017-9798](#https://vulners.com/cve/CVE-2017-9798)

|       CVE\-2017\-15710  5\.0     [https://vulners.com/cve/CVE-2017-15710](#https://vulners.com/cve/CVE-2017-15710)

|       CVE\-2016\-8743   5\.0     [https://vulners.com/cve/CVE-2016-8743](#https://vulners.com/cve/CVE-2016-8743)

|       CVE\-2016\-2161   5\.0     [https://vulners.com/cve/CVE-2016-2161](#https://vulners.com/cve/CVE-2016-2161)

|       CVE\-2016\-0736   5\.0     [https://vulners.com/cve/CVE-2016-0736](#https://vulners.com/cve/CVE-2016-0736)

|       CVE\-2015\-3183   5\.0     [https://vulners.com/cve/CVE-2015-3183](#https://vulners.com/cve/CVE-2015-3183)

|       CVE\-2015\-0228   5\.0     [https://vulners.com/cve/CVE-2015-0228](#https://vulners.com/cve/CVE-2015-0228)

|       CVE\-2014\-3583   5\.0     [https://vulners.com/cve/CVE-2014-3583](#https://vulners.com/cve/CVE-2014-3583)

|       CVE\-2014\-3581   5\.0     [https://vulners.com/cve/CVE-2014-3581](#https://vulners.com/cve/CVE-2014-3581)

|       CVE\-2014\-0231   5\.0     [https://vulners.com/cve/CVE-2014-0231](#https://vulners.com/cve/CVE-2014-0231)

|       CVE\-2013\-5704   5\.0     [https://vulners.com/cve/CVE-2013-5704](#https://vulners.com/cve/CVE-2013-5704)

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
|       17C6AD2A\-8469\-56C8\-BBBE\-1764D0DF1680    5\.0     [https://vulners.com/githubexploit/17C6AD2A-8469-56C8-BBBE-1764D0DF1680](#https://vulners.com/githubexploit/17C6AD2A-8469-56C8-BBBE-1764D0DF1680)
\*EXPLOIT\*
|       1337DAY\-ID\-28573        5\.0     [https://vulners.com/zdt/1337DAY-ID-28573](#https://vulners.com/zdt/1337DAY-ID-28573)
\*EXPLOIT\*
|       1337DAY\-ID\-26574        5\.0     [https://vulners.com/zdt/1337DAY-ID-26574](#https://vulners.com/zdt/1337DAY-ID-26574)
\*EXPLOIT\*
|       CVE\-2020\-11985  4\.3     [https://vulners.com/cve/CVE-2020-11985](#https://vulners.com/cve/CVE-2020-11985)

|       CVE\-2019\-10092  4\.3     [https://vulners.com/cve/CVE-2019-10092](#https://vulners.com/cve/CVE-2019-10092)

|       CVE\-2018\-1302   4\.3     [https://vulners.com/cve/CVE-2018-1302](#https://vulners.com/cve/CVE-2018-1302)

|       CVE\-2018\-1301   4\.3     [https://vulners.com/cve/CVE-2018-1301](#https://vulners.com/cve/CVE-2018-1301)

|       CVE\-2016\-4975   4\.3     [https://vulners.com/cve/CVE-2016-4975](#https://vulners.com/cve/CVE-2016-4975)

|       CVE\-2015\-3185   4\.3     [https://vulners.com/cve/CVE-2015-3185](#https://vulners.com/cve/CVE-2015-3185)

|       CVE\-2014\-8109   4\.3     [https://vulners.com/cve/CVE-2014-8109](#https://vulners.com/cve/CVE-2014-8109)

|       CVE\-2014\-0118   4\.3     [https://vulners.com/cve/CVE-2014-0118](#https://vulners.com/cve/CVE-2014-0118)

|       4013EC74\-B3C1\-5D95\-938A\-54197A58586D    4\.3     [https://vulners.com/githubexploit/4013EC74-B3C1-5D95-938A-54197A58586D](#https://vulners.com/githubexploit/4013EC74-B3C1-5D95-938A-54197A58586D)
\*EXPLOIT\*
|       1337DAY\-ID\-33575        4\.3     [https://vulners.com/zdt/1337DAY-ID-33575](#https://vulners.com/zdt/1337DAY-ID-33575)
\*EXPLOIT\*
|       CVE\-2018\-1283   3\.5     [https://vulners.com/cve/CVE-2018-1283](#https://vulners.com/cve/CVE-2018-1283)

|       CVE\-2016\-8612   3\.3     [https://vulners.com/cve/CVE-2016-8612](#https://vulners.com/cve/CVE-2016-8612)

|\_      PACKETSTORM:140265      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:140265](#https://vulners.com/packetstorm/PACKETSTORM:140265)
\*EXPLOIT\*
| http\-enum: 
|   /wp\-login\.php: Possible admin folder
|   /readme\.html: Wordpress version: 2 
|   /wp\-includes/images/rss\.png: Wordpress version 2\.2 found\.
|   /wp\-includes/js/jquery/suggest\.js: Wordpress version 2\.5 found\.
|   /wp\-includes/images/blank\.gif: Wordpress version 2\.6 found\.
|   /wp\-includes/js/comment\-reply\.js: Wordpress version 2\.7 found\.
|   /wp\-login\.php: Wordpress login page\.
|   /wp\-admin/upgrade\.php: Wordpress login page\.
|\_  /readme\.html: Interesting, a readme\.
MAC Address: 08:00:27:48:91:A6 \(Oracle VirtualBox virtual NIC\)

**nikto \-url 192\.168\.0\.131           **
\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.0\.131
\+ Target Hostname:    192\.168\.0\.131
\+ Target Port:        80
\+ Start Time:         2023\-12\-06 17:01:02 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.4\.10 \(Debian\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ Root page / redirects to: [http://dc-2/](#http://dc-2/)

\+ /index\.php?: Drupal Link header found with value: ARRAY\(0x559770e60788\)\. See: [https://www.drupal.org/](#https://www.drupal.org/)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ Apache/2\.4\.10 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ /: Web Server returns a valid response with junk HTTP methods which may cause false positives\.
\+ /icons/README: Apache default file found\. See: [https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/](#https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/)

\+ /wp\-content/plugins/akismet/readme\.txt: The WordPress Akismet plugin 'Tested up to' version usually matches the WordPress version\.
\+ /wp\-links\-opml\.php: This WordPress script reveals the installed version\.
\+ /license\.txt: License file found may identify site software\.
\+ /wp\-login\.php?action=register: Cookie wordpress\_test\_cookie created without the httponly flag\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

\+ /wp\-login\.php: Wordpress login found\.
\+ 8102 requests: 0 error\(s\) and 11 item\(s\) reported on remote host
\+ End Time:           2023\-12\-06 17:01:27 \(GMT\-5\) \(25 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

nmap \-sV \-p\- 192\.168\.0\.131 \-v

PORT   STATE SERVICE VERSION
80/tcp   open  http    Apache httpd 2\.4\.10 \(\(Debian\)\)
7744/tcp open  ssh     OpenSSH 6\.7p1 Debian 5\+deb8u7 \(protocol 2\.0\)

wpscan \-\-url [http://dc-2/](#http://dc-2/)
\-\-ignore\-main\-redirect
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

\[\+\] URL: [http://dc-2/](#http://dc-2/)
\[192\.168\.0\.131\]
\[\+\] Started: Wed Dec  6 17:05:17 2023

Interesting Finding\(s\):

\[\+\] Headers
| Interesting Entry: Server: Apache/2\.4\.10 \(Debian\)
| Found By: Headers \(Passive Detection\)
| Confidence: 100%

\[\+\] XML\-RPC seems to be enabled: [http://dc-2/xmlrpc.php](#http://dc-2/xmlrpc.php)

| Found By: Direct Access \(Aggressive Detection\)
| Confidence: 100%
| References:
|  \- [http://codex.wordpress.org/XML-RPC_Pingback_API](#http://codex.wordpress.org/XML-RPC_Pingback_API)

|  \- [https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_ghost_scanner/](#https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_ghost_scanner/)

|  \- [https://www.rapid7.com/db/modules/auxiliary/dos/http/wordpress_xmlrpc_dos/](#https://www.rapid7.com/db/modules/auxiliary/dos/http/wordpress_xmlrpc_dos/)

|  \- [https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_xmlrpc_login/](#https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_xmlrpc_login/)

|  \- [https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_pingback_access/](#https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_pingback_access/)


\[\+\] WordPress readme found: [http://dc-2/readme.html](#http://dc-2/readme.html)

| Found By: Direct Access \(Aggressive Detection\)
| Confidence: 100%

\[\+\] The external WP\-Cron seems to be enabled: [http://dc-2/wp-cron.php](#http://dc-2/wp-cron.php)

| Found By: Direct Access \(Aggressive Detection\)
| Confidence: 60%
| References:
|  \- [https://www.iplocation.net/defend-wordpress-from-ddos](#https://www.iplocation.net/defend-wordpress-from-ddos)

|  \- [https://github.com/wpscanteam/wpscan/issues/1299](#https://github.com/wpscanteam/wpscan/issues/1299)


\[\+\] WordPress version 4\.7\.10 identified \(Insecure, released on 2018\-04\-03\)\.
| Found By: Rss Generator \(Passive Detection\)
|  \- [http://dc-2/index.php/feed/,](#http://dc-2/index.php/feed/,)
\<generator\>[https://wordpress.org/?v=4.7.10](#https://wordpress.org/?v=4.7.10)
\</generator\>
|  \- [http://dc-2/index.php/comments/feed/,](#http://dc-2/index.php/comments/feed/,)
\<generator\>[https://wordpress.org/?v=4.7.10](#https://wordpress.org/?v=4.7.10)
\</generator\>

\[\+\] WordPress theme in use: twentyseventeen
| Location: [http://dc-2/wp-content/themes/twentyseventeen/](#http://dc-2/wp-content/themes/twentyseventeen/)

| Last Updated: 2023\-11\-07T00:00:00\.000Z
| Readme: [http://dc-2/wp-content/themes/twentyseventeen/README.txt](#http://dc-2/wp-content/themes/twentyseventeen/README.txt)

| \[\!\] The version is out of date, the latest version is 3\.4
| Style URL: [http://dc-2/wp-content/themes/twentyseventeen/style.css?ver=4.7.10](#http://dc-2/wp-content/themes/twentyseventeen/style.css?ver=4.7.10)

| Style Name: Twenty Seventeen
| Style URI: [https://wordpress.org/themes/twentyseventeen/](#https://wordpress.org/themes/twentyseventeen/)

| Description: Twenty Seventeen brings your site to life with header video and immersive featured images\. With a fo\.\.\.
| Author: the WordPress team
| Author URI: [https://wordpress.org/](#https://wordpress.org/)

|
| Found By: Css Style In Homepage \(Passive Detection\)
|
| Version: 1\.2 \(80% confidence\)
| Found By: Style \(Passive Detection\)
|  \- [http://dc-2/wp-content/themes/twentyseventeen/style.css?ver=4.7.10,](#http://dc-2/wp-content/themes/twentyseventeen/style.css?ver=4.7.10,)
Match: 'Version: 1\.2'

\[\+\] Enumerating All Plugins \(via Passive Methods\)

\[i\] No plugins Found\.

\[\+\] Enumerating Config Backups \(via Passive and Aggressive Methods\)
Checking Config Backups \- Time: 00:00:00 \<============================================\> \(137 / 137\) 100\.00% Time: 00:00:00

\[i\] No Config Backups Found\.
