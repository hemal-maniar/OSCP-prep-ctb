**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.164\.107**
Starting Nmap 7\.93 \( [https://nmap.org](#https://nmap.org)
\) at 2023\-11\-18 20:41 EST
Nmap scan report for 192\.168\.164\.107
Host is up \(0\.038s latency\)\.
Not shown: 997 closed tcp ports \(reset\)
PORT   STATE SERVICE VERSION
21/tcp open  ftp     ProFTPD 1\.3\.5e
| vulners: 
|   cpe:/a:proftpd:proftpd:1\.3\.5e: 
|       SAINT:FD1752E124A72FD3A26EEB9B315E8382  10\.0    [https://vulners.com/saint/SAINT:FD1752E124A72FD3A26EEB9B315E8382](#https://vulners.com/saint/SAINT:FD1752E124A72FD3A26EEB9B315E8382)
\*EXPLOIT\*
|       SAINT:950EB68D408A40399926A4CCAD3CC62E  10\.0    [https://vulners.com/saint/SAINT:950EB68D408A40399926A4CCAD3CC62E](#https://vulners.com/saint/SAINT:950EB68D408A40399926A4CCAD3CC62E)
\*EXPLOIT\*
|       SAINT:63FB77B9136D48259E4F0D4CDA35E957  10\.0    [https://vulners.com/saint/SAINT:63FB77B9136D48259E4F0D4CDA35E957](#https://vulners.com/saint/SAINT:63FB77B9136D48259E4F0D4CDA35E957)
\*EXPLOIT\*
|       SAINT:1B08F4664C428B180EEC9617B41D9A2C  10\.0    [https://vulners.com/saint/SAINT:1B08F4664C428B180EEC9617B41D9A2C](#https://vulners.com/saint/SAINT:1B08F4664C428B180EEC9617B41D9A2C)
\*EXPLOIT\*
|       PROFTPD\_MOD\_COPY        10\.0    [https://vulners.com/canvas/PROFTPD_MOD_COPY](#https://vulners.com/canvas/PROFTPD_MOD_COPY)
\*EXPLOIT\*
|       PACKETSTORM:162777      10\.0    [https://vulners.com/packetstorm/PACKETSTORM:162777](#https://vulners.com/packetstorm/PACKETSTORM:162777)
\*EXPLOIT\*
|       PACKETSTORM:132218      10\.0    [https://vulners.com/packetstorm/PACKETSTORM:132218](#https://vulners.com/packetstorm/PACKETSTORM:132218)
\*EXPLOIT\*
|       PACKETSTORM:131567      10\.0    [https://vulners.com/packetstorm/PACKETSTORM:131567](#https://vulners.com/packetstorm/PACKETSTORM:131567)
\*EXPLOIT\*
|       PACKETSTORM:131555      10\.0    [https://vulners.com/packetstorm/PACKETSTORM:131555](#https://vulners.com/packetstorm/PACKETSTORM:131555)
\*EXPLOIT\*
|       PACKETSTORM:131505      10\.0    [https://vulners.com/packetstorm/PACKETSTORM:131505](#https://vulners.com/packetstorm/PACKETSTORM:131505)
\*EXPLOIT\*
|       EDB\-ID:49908    10\.0    [https://vulners.com/exploitdb/EDB-ID:49908](#https://vulners.com/exploitdb/EDB-ID:49908)
\*EXPLOIT\*
|       CVE\-2015\-3306   10\.0    [https://vulners.com/cve/CVE-2015-3306](#https://vulners.com/cve/CVE-2015-3306)

|       1337DAY\-ID\-36298        10\.0    [https://vulners.com/zdt/1337DAY-ID-36298](#https://vulners.com/zdt/1337DAY-ID-36298)
\*EXPLOIT\*
|       1337DAY\-ID\-23720        10\.0    [https://vulners.com/zdt/1337DAY-ID-23720](#https://vulners.com/zdt/1337DAY-ID-23720)
\*EXPLOIT\*
|       1337DAY\-ID\-23544        10\.0    [https://vulners.com/zdt/1337DAY-ID-23544](#https://vulners.com/zdt/1337DAY-ID-23544)
\*EXPLOIT\*
|       SSV:61050       5\.0     [https://vulners.com/seebug/SSV:61050](#https://vulners.com/seebug/SSV:61050)
\*EXPLOIT\*
|       PRION:CVE\-2019\-19272    5\.0     [https://vulners.com/prion/PRION:CVE-2019-19272](#https://vulners.com/prion/PRION:CVE-2019-19272)

|       PRION:CVE\-2019\-19271    5\.0     [https://vulners.com/prion/PRION:CVE-2019-19271](#https://vulners.com/prion/PRION:CVE-2019-19271)

|       PRION:CVE\-2019\-19270    5\.0     [https://vulners.com/prion/PRION:CVE-2019-19270](#https://vulners.com/prion/PRION:CVE-2019-19270)

|       PRION:CVE\-2019\-18217    5\.0     [https://vulners.com/prion/PRION:CVE-2019-18217](#https://vulners.com/prion/PRION:CVE-2019-18217)

|       CVE\-2021\-46854  5\.0     [https://vulners.com/cve/CVE-2021-46854](#https://vulners.com/cve/CVE-2021-46854)

|       CVE\-2020\-9272   5\.0     [https://vulners.com/cve/CVE-2020-9272](#https://vulners.com/cve/CVE-2020-9272)

|       CVE\-2019\-19272  5\.0     [https://vulners.com/cve/CVE-2019-19272](#https://vulners.com/cve/CVE-2019-19272)

|       CVE\-2019\-19271  5\.0     [https://vulners.com/cve/CVE-2019-19271](#https://vulners.com/cve/CVE-2019-19271)

|       CVE\-2016\-3125   5\.0     [https://vulners.com/cve/CVE-2016-3125](#https://vulners.com/cve/CVE-2016-3125)

|       CVE\-2013\-4359   5\.0     [https://vulners.com/cve/CVE-2013-4359](#https://vulners.com/cve/CVE-2013-4359)

|       PRION:CVE\-2017\-7418     2\.1     [https://vulners.com/prion/PRION:CVE-2017-7418](#https://vulners.com/prion/PRION:CVE-2017-7418)

|\_      CVE\-2017\-7418   2\.1     [https://vulners.com/cve/CVE-2017-7418](#https://vulners.com/cve/CVE-2017-7418)

| ftp\-anon: Anonymous FTP login allowed \(FTP code 230\)
| \-rw\-rw\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 anna\.zip
| \-rw\-rw\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 ariel\.zip
| \-rw\-rw\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 bud\.zip
| \-rw\-rw\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 cathrine\.zip
| \-rw\-rw\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 homer\.zip
| \-rw\-rw\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 jessica\.zip
| \-rw\-rw\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 john\.zip
| \-rw\-rw\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 marge\.zip
| \-rw\-rw\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 miriam\.zip
| \-r\-\-r\-\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 tom\.zip
| \-rw\-r\-\-r\-\-   1 ftp      ftp           170 Jan 10  2018 welcome\.msg
|\_\-rw\-rw\-r\-\-   1 ftp      ftp          1477 Jul 25  2020 zlatan\.zip
22/tcp open  ssh     OpenSSH 7\.6p1 Ubuntu 4ubuntu0\.3 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   2048 f9467dfe0c4da97e2d77740fa2517251 \(RSA\)
|   256 15004667809b40123a0c6607db1d1847 \(ECDSA\)
|\_  256 75ba6695bb0f16de7e7ea17b273bb058 \(ED25519\)
| vulners: 
|   cpe:/a:openbsd:openssh:7\.6p1: 
|       PRION:CVE\-2019\-6111     5\.8     [https://vulners.com/prion/PRION:CVE-2019-6111](#https://vulners.com/prion/PRION:CVE-2019-6111)

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

|       CVE\-2017\-15906  5\.0     [https://vulners.com/cve/CVE-2017-15906](#https://vulners.com/cve/CVE-2017-15906)

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

|       PRION:CVE\-2018\-20685    2\.6     [https://vulners.com/prion/PRION:CVE-2018-20685](#https://vulners.com/prion/PRION:CVE-2018-20685)

|       CVE\-2018\-20685  2\.6     [https://vulners.com/cve/CVE-2018-20685](#https://vulners.com/cve/CVE-2018-20685)

|       PACKETSTORM:151227      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:151227](#https://vulners.com/packetstorm/PACKETSTORM:151227)
\*EXPLOIT\*
|       MSF:AUXILIARY\-SCANNER\-SSH\-SSH\_ENUMUSERS\-        0\.0     [https://vulners.com/metasploit/MSF:AUXILIARY-SCANNER-SSH-SSH_ENUMUSERS-](#https://vulners.com/metasploit/MSF:AUXILIARY-SCANNER-SSH-SSH_ENUMUSERS-)
\*EXPLOIT\*
|\_      1337DAY\-ID\-30937        0\.0     [https://vulners.com/zdt/1337DAY-ID-30937](#https://vulners.com/zdt/1337DAY-ID-30937)
\*EXPLOIT\*
80/tcp open  http    Apache httpd 2\.4\.29 \(\(Ubuntu\)\)
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
|\_http\-server\-header: Apache/2\.4\.29 \(Ubuntu\)
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
| http\-enum: 
|\_  /robots\.txt: Robots file
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
| http\-robots\.txt: 1 disallowed entry 
|\_/logs/
Service Info: OSs: Unix, Linux; CPE: cpe:/o:linux:linux\_kernel

Service detection performed\. Please report any incorrect results at [https://nmap.org/submit/](#https://nmap.org/submit/)
\.
Nmap done: 1 IP address \(1 host up\) scanned in 40\.58 seconds192\.168\.164\.107

