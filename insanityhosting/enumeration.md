**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.0\.24 **
PORT   STATE SERVICE VERSION
21/tcp open  ftp     vsftpd 3\.0\.2
| vulners: 
|   cpe:/a:vsftpd:vsftpd:3\.0\.2: 
|       PRION:CVE\-2021\-3618     5\.8     [https://vulners.com/prion/PRION:CVE-2021-3618](#https://vulners.com/prion/PRION:CVE-2021-3618)

|\_      PRION:CVE\-2015\-1419     5\.0     [https://vulners.com/prion/PRION:CVE-2015-1419](#https://vulners.com/prion/PRION:CVE-2015-1419)

| ftp\-anon: Anonymous FTP login allowed \(FTP code 230\)
|\_Can't get directory listing: ERROR
| ftp\-syst: 
|   STAT: 
| FTP server status:
|      Connected to ::ffff:192\.168\.0\.63
|      Logged in as ftp
|      TYPE: ASCII
|      No session bandwidth limit
|      Session timeout in seconds is 300
|      Control connection is plain text
|      Data connections will be plain text
|      At session startup, client count was 1
|      vsFTPd 3\.0\.2 \- secure, fast, stable
|\_End of status
22/tcp open  ssh     OpenSSH 7\.4 \(protocol 2\.0\)
| ssh\-hostkey: 
|   2048 85:46:41:06:da:83:04:01:b0:e4:1f:9b:7e:8b:31:9f \(RSA\)
|   256 e4:9c:b1:f2:44:f1:f0:4b:c3:80:93:a9:5d:96:98:d3 \(ECDSA\)
|\_  256 65:cf:b4:af:ad:86:56:ef:ae:8b:bf:f2:f0:d9:be:10 \(ED25519\)
| vulners: 
|   cpe:/a:openbsd:openssh:7\.4: 
|       PRION:CVE\-2019\-6111     5\.8     [https://vulners.com/prion/PRION:CVE-2019-6111](#https://vulners.com/prion/PRION:CVE-2019-6111)

|       EXPLOITPACK:98FE96309F9524B8C84C508837551A19    5\.8     [https://vulners.com/exploitpack/EXPLOITPACK:98FE96309F9524B8C84C508837551A19](#https://vulners.com/exploitpack/EXPLOITPACK:98FE96309F9524B8C84C508837551A19)
\*EXPLOIT\*
|       EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97    5\.8     [https://vulners.com/exploitpack/EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97](#https://vulners.com/exploitpack/EXPLOITPACK:5330EA02EBDE345BFC9D6DDDD97F9E97)
\*EXPLOIT\*
|       EDB\-ID:46516    5\.8     [https://vulners.com/exploitdb/EDB-ID:46516](#https://vulners.com/exploitdb/EDB-ID:46516)
\*EXPLOIT\*
|       EDB\-ID:46193    5\.8     [https://vulners.com/exploitdb/EDB-ID:46193](#https://vulners.com/exploitdb/EDB-ID:46193)
\*EXPLOIT\*
|       CVE\-2019\-6111   5\.8     [https://vulners.com/cve/CVE-2019-6111](#https://vulners.com/cve/CVE-2019-6111)

|       1337DAY\-ID\-32328        5\.8     [https://vulners.com/zdt/1337DAY-ID-32328](#https://vulners.com/zdt/1337DAY-ID-32328)
\*EXPLOIT\*
|       1337DAY\-ID\-32009        5\.8     [https://vulners.com/zdt/1337DAY-ID-32009](#https://vulners.com/zdt/1337DAY-ID-32009)
\*EXPLOIT\*
|       SSH\_ENUM        5\.0     [https://vulners.com/canvas/SSH_ENUM](#https://vulners.com/canvas/SSH_ENUM)
\*EXPLOIT\*
|       PRION:CVE\-2018\-15919    5\.0     [https://vulners.com/prion/PRION:CVE-2018-15919](#https://vulners.com/prion/PRION:CVE-2018-15919)

|       PRION:CVE\-2018\-15473    5\.0     [https://vulners.com/prion/PRION:CVE-2018-15473](#https://vulners.com/prion/PRION:CVE-2018-15473)

|       PRION:CVE\-2017\-15906    5\.0     [https://vulners.com/prion/PRION:CVE-2017-15906](#https://vulners.com/prion/PRION:CVE-2017-15906)

|       PACKETSTORM:150621      5\.0     [https://vulners.com/packetstorm/PACKETSTORM:150621](#https://vulners.com/packetstorm/PACKETSTORM:150621)
\*EXPLOIT\*
|       MSF:AUXILIARY\-SCANNER\-SSH\-SSH\_ENUMUSERS\-        5\.0     [https://vulners.com/metasploit/MSF:AUXILIARY-SCANNER-SSH-SSH_ENUMUSERS-](#https://vulners.com/metasploit/MSF:AUXILIARY-SCANNER-SSH-SSH_ENUMUSERS-)
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

|       CVE\-2016\-10708  5\.0     [https://vulners.com/cve/CVE-2016-10708](#https://vulners.com/cve/CVE-2016-10708)

|       1337DAY\-ID\-31730        5\.0     [https://vulners.com/zdt/1337DAY-ID-31730](#https://vulners.com/zdt/1337DAY-ID-31730)
\*EXPLOIT\*
|       PRION:CVE\-2019\-16905    4\.4     [https://vulners.com/prion/PRION:CVE-2019-16905](#https://vulners.com/prion/PRION:CVE-2019-16905)

|       CVE\-2020\-14145  4\.3     [https://vulners.com/cve/CVE-2020-14145](#https://vulners.com/cve/CVE-2020-14145)

|       PRION:CVE\-2019\-6110     4\.0     [https://vulners.com/prion/PRION:CVE-2019-6110](#https://vulners.com/prion/PRION:CVE-2019-6110)

|       PRION:CVE\-2019\-6109     4\.0     [https://vulners.com/prion/PRION:CVE-2019-6109](#https://vulners.com/prion/PRION:CVE-2019-6109)

|       CVE\-2019\-6110   4\.0     [https://vulners.com/cve/CVE-2019-6110](#https://vulners.com/cve/CVE-2019-6110)

|       CVE\-2019\-6109   4\.0     [https://vulners.com/cve/CVE-2019-6109](#https://vulners.com/cve/CVE-2019-6109)

|       PRION:CVE\-2018\-20685    2\.6     [https://vulners.com/prion/PRION:CVE-2018-20685](#https://vulners.com/prion/PRION:CVE-2018-20685)

|       CVE\-2018\-20685  2\.6     [https://vulners.com/cve/CVE-2018-20685](#https://vulners.com/cve/CVE-2018-20685)

|       PACKETSTORM:151227      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:151227](#https://vulners.com/packetstorm/PACKETSTORM:151227)
\*EXPLOIT\*
|\_      1337DAY\-ID\-30937        0\.0     [https://vulners.com/zdt/1337DAY-ID-30937](#https://vulners.com/zdt/1337DAY-ID-30937)
\*EXPLOIT\*
80/tcp open  http    Apache httpd 2\.4\.6 \(\(CentOS\) PHP/7\.2\.33\)
|\_http\-trace: TRACE is enabled
|\_http\-server\-header: Apache/2\.4\.6 \(CentOS\) PHP/7\.2\.33
| http\-enum: 
|   /phpinfo\.php: Possible information file
|   /phpmyadmin/: phpMyAdmin
|   /webmail/src/login\.php: squirrelmail version 1\.4\.22
|   /webmail/images/sm\_logo\.png: SquirrelMail
|   /css/: Potentially interesting folder w/ directory listing
|   /data/: Potentially interesting folder w/ directory listing
|   /icons/: Potentially interesting folder w/ directory listing
|   /img/: Potentially interesting folder w/ directory listing
|   /js/: Potentially interesting folder w/ directory listing
|\_  /news/: Potentially interesting folder
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
| http\-sql\-injection: 
|   Possible sqli for queries:
|     [http://192.168.0.24:80/js/?C=S%3BO%3DA%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=S%3BO%3DA%27%20OR%20sqlspider)

|     [http://192.168.0.24:80/js/?C=M%3BO%3DA%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=M%3BO%3DA%27%20OR%20sqlspider)

|     [http://192.168.0.24:80/js/?C=N%3BO%3DD%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=N%3BO%3DD%27%20OR%20sqlspider)

|     [http://192.168.0.24:80/js/?C=D%3BO%3DA%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=D%3BO%3DA%27%20OR%20sqlspider)

|     [http://192.168.0.24:80/js/?C=N%3BO%3DA%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=N%3BO%3DA%27%20OR%20sqlspider)

|     [http://192.168.0.24:80/js/?C=S%3BO%3DD%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=S%3BO%3DD%27%20OR%20sqlspider)

|     [http://192.168.0.24:80/js/?C=D%3BO%3DA%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=D%3BO%3DA%27%20OR%20sqlspider)

|     [http://192.168.0.24:80/js/?C=M%3BO%3DA%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=M%3BO%3DA%27%20OR%20sqlspider)

|     [http://192.168.0.24:80/js/?C=N%3BO%3DA%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=N%3BO%3DA%27%20OR%20sqlspider)

|     [http://192.168.0.24:80/js/?C=D%3BO%3DA%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=D%3BO%3DA%27%20OR%20sqlspider)

|     [http://192.168.0.24:80/js/?C=S%3BO%3DA%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=S%3BO%3DA%27%20OR%20sqlspider)

|\_    [http://192.168.0.24:80/js/?C=M%3BO%3DD%27%20OR%20sqlspider](#http://192.168.0.24:80/js/?C=M%3BO%3DD%27%20OR%20sqlspider)

| http\-methods: 
|\_  Potentially risky methods: TRACE
|\_http\-vuln\-cve2017\-1001000: ERROR: Script execution failed \(use \-d to debug\)
|\_http\-title: Insanity \- UK and European Servers
| vulners: 
|   cpe:/a:apache:http\_server:2\.4\.6: 
|       PACKETSTORM:176334      7\.5     [https://vulners.com/packetstorm/PACKETSTORM:176334](#https://vulners.com/packetstorm/PACKETSTORM:176334)
\*EXPLOIT\*
|       PACKETSTORM:171631      7\.5     [https://vulners.com/packetstorm/PACKETSTORM:171631](#https://vulners.com/packetstorm/PACKETSTORM:171631)
\*EXPLOIT\*
|       OSV:BIT\-APACHE\-2023\-25690       7\.5     [https://vulners.com/osv/OSV:BIT-APACHE-2023-25690](#https://vulners.com/osv/OSV:BIT-APACHE-2023-25690)

|       OSV:BIT\-APACHE\-2022\-31813       7\.5     [https://vulners.com/osv/OSV:BIT-APACHE-2022-31813](#https://vulners.com/osv/OSV:BIT-APACHE-2022-31813)

|       OSV:BIT\-APACHE\-2022\-23943       7\.5     [https://vulners.com/osv/OSV:BIT-APACHE-2022-23943](#https://vulners.com/osv/OSV:BIT-APACHE-2022-23943)

|       OSV:BIT\-APACHE\-2022\-22720       7\.5     [https://vulners.com/osv/OSV:BIT-APACHE-2022-22720](#https://vulners.com/osv/OSV:BIT-APACHE-2022-22720)

|       OSV:BIT\-APACHE\-2021\-44790       7\.5     [https://vulners.com/osv/OSV:BIT-APACHE-2021-44790](#https://vulners.com/osv/OSV:BIT-APACHE-2021-44790)

|       OSV:BIT\-APACHE\-2021\-42013       7\.5     [https://vulners.com/osv/OSV:BIT-APACHE-2021-42013](#https://vulners.com/osv/OSV:BIT-APACHE-2021-42013)

|       OSV:BIT\-APACHE\-2021\-41773       7\.5     [https://vulners.com/osv/OSV:BIT-APACHE-2021-41773](#https://vulners.com/osv/OSV:BIT-APACHE-2021-41773)

|       OSV:BIT\-APACHE\-2021\-39275       7\.5     [https://vulners.com/osv/OSV:BIT-APACHE-2021-39275](#https://vulners.com/osv/OSV:BIT-APACHE-2021-39275)

|       OSV:BIT\-APACHE\-2021\-26691       7\.5     [https://vulners.com/osv/OSV:BIT-APACHE-2021-26691](#https://vulners.com/osv/OSV:BIT-APACHE-2021-26691)

|       OSV:BIT\-APACHE\-2020\-11984       7\.5     [https://vulners.com/osv/OSV:BIT-APACHE-2020-11984](#https://vulners.com/osv/OSV:BIT-APACHE-2020-11984)

|       MSF:EXPLOIT\-MULTI\-HTTP\-APACHE\_NORMALIZE\_PATH\_RCE\-       7\.5     [https://vulners.com/metasploit/MSF:EXPLOIT-MULTI-HTTP-APACHE_NORMALIZE_PATH_RCE-](#https://vulners.com/metasploit/MSF:EXPLOIT-MULTI-HTTP-APACHE_NORMALIZE_PATH_RCE-)
\*EXPLOIT\*
|       MSF:AUXILIARY\-SCANNER\-HTTP\-APACHE\_NORMALIZE\_PATH\-       7\.5     [https://vulners.com/metasploit/MSF:AUXILIARY-SCANNER-HTTP-APACHE_NORMALIZE_PATH-](#https://vulners.com/metasploit/MSF:AUXILIARY-SCANNER-HTTP-APACHE_NORMALIZE_PATH-)
\*EXPLOIT\*
|       F9C0CD4B\-3B60\-5720\-AE7A\-7CC31DB839C5    7\.5     [https://vulners.com/githubexploit/F9C0CD4B-3B60-5720-AE7A-7CC31DB839C5](#https://vulners.com/githubexploit/F9C0CD4B-3B60-5720-AE7A-7CC31DB839C5)
\*EXPLOIT\*
|       EDB\-ID:51193    7\.5     [https://vulners.com/exploitdb/EDB-ID:51193](#https://vulners.com/exploitdb/EDB-ID:51193)
\*EXPLOIT\*
|       EDB\-ID:50512    7\.5     [https://vulners.com/exploitdb/EDB-ID:50512](#https://vulners.com/exploitdb/EDB-ID:50512)
\*EXPLOIT\*
|       EDB\-ID:50446    7\.5     [https://vulners.com/exploitdb/EDB-ID:50446](#https://vulners.com/exploitdb/EDB-ID:50446)
\*EXPLOIT\*
|       EDB\-ID:50406    7\.5     [https://vulners.com/exploitdb/EDB-ID:50406](#https://vulners.com/exploitdb/EDB-ID:50406)
\*EXPLOIT\*
|       E796A40A\-8A8E\-59D1\-93FB\-78EF4D8B7FA6    7\.5     [https://vulners.com/githubexploit/E796A40A-8A8E-59D1-93FB-78EF4D8B7FA6](#https://vulners.com/githubexploit/E796A40A-8A8E-59D1-93FB-78EF4D8B7FA6)
\*EXPLOIT\*
|       CVE\-2023\-25690  7\.5     [https://vulners.com/cve/CVE-2023-25690](#https://vulners.com/cve/CVE-2023-25690)

|       CVE\-2022\-31813  7\.5     [https://vulners.com/cve/CVE-2022-31813](#https://vulners.com/cve/CVE-2022-31813)

|       CVE\-2022\-23943  7\.5     [https://vulners.com/cve/CVE-2022-23943](#https://vulners.com/cve/CVE-2022-23943)

|       CVE\-2022\-22720  7\.5     [https://vulners.com/cve/CVE-2022-22720](#https://vulners.com/cve/CVE-2022-22720)

|       CVE\-2021\-44790  7\.5     [https://vulners.com/cve/CVE-2021-44790](#https://vulners.com/cve/CVE-2021-44790)

|       CVE\-2021\-39275  7\.5     [https://vulners.com/cve/CVE-2021-39275](#https://vulners.com/cve/CVE-2021-39275)

|       CVE\-2021\-26691  7\.5     [https://vulners.com/cve/CVE-2021-26691](#https://vulners.com/cve/CVE-2021-26691)

|       CVE\-2017\-7679   7\.5     [https://vulners.com/cve/CVE-2017-7679](#https://vulners.com/cve/CVE-2017-7679)

|       CVE\-2017\-3167   7\.5     [https://vulners.com/cve/CVE-2017-3167](#https://vulners.com/cve/CVE-2017-3167)

|       CNVD\-2022\-73123 7\.5     [https://vulners.com/cnvd/CNVD-2022-73123](#https://vulners.com/cnvd/CNVD-2022-73123)

|       CNVD\-2022\-03225 7\.5     [https://vulners.com/cnvd/CNVD-2022-03225](#https://vulners.com/cnvd/CNVD-2022-03225)

|       CNVD\-2021\-102386        7\.5     [https://vulners.com/cnvd/CNVD-2021-102386](#https://vulners.com/cnvd/CNVD-2021-102386)

|       CC15AE65\-B697\-525A\-AF4B\-38B1501CAB49    7\.5     [https://vulners.com/githubexploit/CC15AE65-B697-525A-AF4B-38B1501CAB49](#https://vulners.com/githubexploit/CC15AE65-B697-525A-AF4B-38B1501CAB49)
\*EXPLOIT\*
|       9B4F4E4A\-CFDF\-5847\-805F\-C0BAE809DBD5    7\.5     [https://vulners.com/githubexploit/9B4F4E4A-CFDF-5847-805F-C0BAE809DBD5](#https://vulners.com/githubexploit/9B4F4E4A-CFDF-5847-805F-C0BAE809DBD5)
\*EXPLOIT\*
|       8713FD59\-264B\-5FD7\-8429\-3251AB5AB3B8    7\.5     [https://vulners.com/githubexploit/8713FD59-264B-5FD7-8429-3251AB5AB3B8](#https://vulners.com/githubexploit/8713FD59-264B-5FD7-8429-3251AB5AB3B8)
\*EXPLOIT\*
|       6A0A657E\-8300\-5312\-99CE\-E11F460B1DBF    7\.5     [https://vulners.com/githubexploit/6A0A657E-8300-5312-99CE-E11F460B1DBF](#https://vulners.com/githubexploit/6A0A657E-8300-5312-99CE-E11F460B1DBF)
\*EXPLOIT\*
|       61075B23\-F713\-537A\-9B84\-7EB9B96CF228    7\.5     [https://vulners.com/githubexploit/61075B23-F713-537A-9B84-7EB9B96CF228](#https://vulners.com/githubexploit/61075B23-F713-537A-9B84-7EB9B96CF228)
\*EXPLOIT\*
|       5C1BB960\-90C1\-5EBF\-9BEF\-F58BFFDFEED9    7\.5     [https://vulners.com/githubexploit/5C1BB960-90C1-5EBF-9BEF-F58BFFDFEED9](#https://vulners.com/githubexploit/5C1BB960-90C1-5EBF-9BEF-F58BFFDFEED9)
\*EXPLOIT\*
|       5312D04F\-9490\-5472\-84FA\-86B3BBDC8928    7\.5     [https://vulners.com/githubexploit/5312D04F-9490-5472-84FA-86B3BBDC8928](#https://vulners.com/githubexploit/5312D04F-9490-5472-84FA-86B3BBDC8928)
\*EXPLOIT\*
|       52E13088\-9643\-5E81\-B0A0\-B7478BCF1F2C    7\.5     [https://vulners.com/githubexploit/52E13088-9643-5E81-B0A0-B7478BCF1F2C](#https://vulners.com/githubexploit/52E13088-9643-5E81-B0A0-B7478BCF1F2C)
\*EXPLOIT\*
|       3F17CA20\-788F\-5C45\-88B3\-E12DB2979B7B    7\.5     [https://vulners.com/githubexploit/3F17CA20-788F-5C45-88B3-E12DB2979B7B](#https://vulners.com/githubexploit/3F17CA20-788F-5C45-88B3-E12DB2979B7B)
\*EXPLOIT\*
|       22DCCD26\-B68C\-5905\-BAC2\-71D10DE3F123    7\.5     [https://vulners.com/githubexploit/22DCCD26-B68C-5905-BAC2-71D10DE3F123](#https://vulners.com/githubexploit/22DCCD26-B68C-5905-BAC2-71D10DE3F123)
\*EXPLOIT\*
|       2108729F\-1E99\-54EF\-9A4B\-47299FD89FF2    7\.5     [https://vulners.com/githubexploit/2108729F-1E99-54EF-9A4B-47299FD89FF2](#https://vulners.com/githubexploit/2108729F-1E99-54EF-9A4B-47299FD89FF2)
\*EXPLOIT\*
|       1337DAY\-ID\-39214        7\.5     [https://vulners.com/zdt/1337DAY-ID-39214](#https://vulners.com/zdt/1337DAY-ID-39214)
\*EXPLOIT\*
|       1337DAY\-ID\-38427        7\.5     [https://vulners.com/zdt/1337DAY-ID-38427](#https://vulners.com/zdt/1337DAY-ID-38427)
\*EXPLOIT\*
|       1337DAY\-ID\-37777        7\.5     [https://vulners.com/zdt/1337DAY-ID-37777](#https://vulners.com/zdt/1337DAY-ID-37777)
\*EXPLOIT\*
|       1337DAY\-ID\-36952        7\.5     [https://vulners.com/zdt/1337DAY-ID-36952](#https://vulners.com/zdt/1337DAY-ID-36952)
\*EXPLOIT\*
|       1337DAY\-ID\-34882        7\.5     [https://vulners.com/zdt/1337DAY-ID-34882](#https://vulners.com/zdt/1337DAY-ID-34882)
\*EXPLOIT\*
|       PACKETSTORM:127546      6\.8     [https://vulners.com/packetstorm/PACKETSTORM:127546](#https://vulners.com/packetstorm/PACKETSTORM:127546)
\*EXPLOIT\*
|       OSV:BIT\-APACHE\-2021\-40438       6\.8     [https://vulners.com/osv/OSV:BIT-APACHE-2021-40438](#https://vulners.com/osv/OSV:BIT-APACHE-2021-40438)

|       OSV:BIT\-APACHE\-2020\-35452       6\.8     [https://vulners.com/osv/OSV:BIT-APACHE-2020-35452](#https://vulners.com/osv/OSV:BIT-APACHE-2020-35452)

|       FDF3DFA1\-ED74\-5EE2\-BF5C\-BA752CA34AE8    6\.8     [https://vulners.com/githubexploit/FDF3DFA1-ED74-5EE2-BF5C-BA752CA34AE8](#https://vulners.com/githubexploit/FDF3DFA1-ED74-5EE2-BF5C-BA752CA34AE8)
\*EXPLOIT\*
|       CVE\-2021\-40438  6\.8     [https://vulners.com/cve/CVE-2021-40438](#https://vulners.com/cve/CVE-2021-40438)

|       CVE\-2020\-35452  6\.8     [https://vulners.com/cve/CVE-2020-35452](#https://vulners.com/cve/CVE-2020-35452)

|       CVE\-2018\-1312   6\.8     [https://vulners.com/cve/CVE-2018-1312](#https://vulners.com/cve/CVE-2018-1312)

|       CVE\-2017\-15715  6\.8     [https://vulners.com/cve/CVE-2017-15715](#https://vulners.com/cve/CVE-2017-15715)

|       CVE\-2016\-5387   6\.8     [https://vulners.com/cve/CVE-2016-5387](#https://vulners.com/cve/CVE-2016-5387)

|       CVE\-2014\-0226   6\.8     [https://vulners.com/cve/CVE-2014-0226](#https://vulners.com/cve/CVE-2014-0226)

|       CNVD\-2022\-03224 6\.8     [https://vulners.com/cnvd/CNVD-2022-03224](#https://vulners.com/cnvd/CNVD-2022-03224)

|       AE3EF1CC\-A0C3\-5CB7\-A6EF\-4DAAAFA59C8C    6\.8     [https://vulners.com/githubexploit/AE3EF1CC-A0C3-5CB7-A6EF-4DAAAFA59C8C](#https://vulners.com/githubexploit/AE3EF1CC-A0C3-5CB7-A6EF-4DAAAFA59C8C)
\*EXPLOIT\*
|       8AFB43C5\-ABD4\-52AD\-BB19\-24D7884FF2A2    6\.8     [https://vulners.com/githubexploit/8AFB43C5-ABD4-52AD-BB19-24D7884FF2A2](#https://vulners.com/githubexploit/8AFB43C5-ABD4-52AD-BB19-24D7884FF2A2)
\*EXPLOIT\*
|       4810E2D9\-AC5F\-5B08\-BFB3\-DDAFA2F63332    6\.8     [https://vulners.com/githubexploit/4810E2D9-AC5F-5B08-BFB3-DDAFA2F63332](#https://vulners.com/githubexploit/4810E2D9-AC5F-5B08-BFB3-DDAFA2F63332)
\*EXPLOIT\*
|       4373C92A\-2755\-5538\-9C91\-0469C995AA9B    6\.8     [https://vulners.com/githubexploit/4373C92A-2755-5538-9C91-0469C995AA9B](#https://vulners.com/githubexploit/4373C92A-2755-5538-9C91-0469C995AA9B)
\*EXPLOIT\*
|       36618CA8\-9316\-59CA\-B748\-82F15F407C4F    6\.8     [https://vulners.com/githubexploit/36618CA8-9316-59CA-B748-82F15F407C4F](#https://vulners.com/githubexploit/36618CA8-9316-59CA-B748-82F15F407C4F)
\*EXPLOIT\*
|       1337DAY\-ID\-22451        6\.8     [https://vulners.com/zdt/1337DAY-ID-22451](#https://vulners.com/zdt/1337DAY-ID-22451)
\*EXPLOIT\*
|       0095E929\-7573\-5E4A\-A7FA\-F6598A35E8DE    6\.8     [https://vulners.com/githubexploit/0095E929-7573-5E4A-A7FA-F6598A35E8DE](#https://vulners.com/githubexploit/0095E929-7573-5E4A-A7FA-F6598A35E8DE)
\*EXPLOIT\*
|       OSV:BIT\-APACHE\-2022\-28615       6\.4     [https://vulners.com/osv/OSV:BIT-APACHE-2022-28615](#https://vulners.com/osv/OSV:BIT-APACHE-2022-28615)

|       OSV:BIT\-APACHE\-2021\-44224       6\.4     [https://vulners.com/osv/OSV:BIT-APACHE-2021-44224](#https://vulners.com/osv/OSV:BIT-APACHE-2021-44224)

|       OSV:BIT\-2023\-31122      6\.4     [https://vulners.com/osv/OSV:BIT-2023-31122](#https://vulners.com/osv/OSV:BIT-2023-31122)

|       CVE\-2022\-28615  6\.4     [https://vulners.com/cve/CVE-2022-28615](#https://vulners.com/cve/CVE-2022-28615)

|       CVE\-2017\-9788   6\.4     [https://vulners.com/cve/CVE-2017-9788](#https://vulners.com/cve/CVE-2017-9788)

|       CVE\-2019\-0217   6\.0     [https://vulners.com/cve/CVE-2019-0217](#https://vulners.com/cve/CVE-2019-0217)

|       OSV:BIT\-APACHE\-2022\-22721       5\.8     [https://vulners.com/osv/OSV:BIT-APACHE-2022-22721](#https://vulners.com/osv/OSV:BIT-APACHE-2022-22721)

|       OSV:BIT\-APACHE\-2020\-1927        5\.8     [https://vulners.com/osv/OSV:BIT-APACHE-2020-1927](#https://vulners.com/osv/OSV:BIT-APACHE-2020-1927)

|       CVE\-2022\-22721  5\.8     [https://vulners.com/cve/CVE-2022-22721](#https://vulners.com/cve/CVE-2022-22721)

|       CVE\-2020\-1927   5\.8     [https://vulners.com/cve/CVE-2020-1927](#https://vulners.com/cve/CVE-2020-1927)

|       CVE\-2019\-10098  5\.8     [https://vulners.com/cve/CVE-2019-10098](#https://vulners.com/cve/CVE-2019-10098)

|       1337DAY\-ID\-33577        5\.8     [https://vulners.com/zdt/1337DAY-ID-33577](#https://vulners.com/zdt/1337DAY-ID-33577)
\*EXPLOIT\*
|       OSV:BIT\-APACHE\-2022\-36760       5\.1     [https://vulners.com/osv/OSV:BIT-APACHE-2022-36760](#https://vulners.com/osv/OSV:BIT-APACHE-2022-36760)

|       CVE\-2022\-36760  5\.1     [https://vulners.com/cve/CVE-2022-36760](#https://vulners.com/cve/CVE-2022-36760)

|       SSV:96537       5\.0     [https://vulners.com/seebug/SSV:96537](#https://vulners.com/seebug/SSV:96537)
\*EXPLOIT\*
|       SSV:62058       5\.0     [https://vulners.com/seebug/SSV:62058](#https://vulners.com/seebug/SSV:62058)
\*EXPLOIT\*
|       SSV:61874       5\.0     [https://vulners.com/seebug/SSV:61874](#https://vulners.com/seebug/SSV:61874)
\*EXPLOIT\*
|       OSV:BIT\-APACHE\-2023\-45802       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2023-45802](#https://vulners.com/osv/OSV:BIT-APACHE-2023-45802)

|       OSV:BIT\-APACHE\-2023\-43622       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2023-43622](#https://vulners.com/osv/OSV:BIT-APACHE-2023-43622)

|       OSV:BIT\-APACHE\-2023\-31122       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2023-31122](#https://vulners.com/osv/OSV:BIT-APACHE-2023-31122)

|       OSV:BIT\-APACHE\-2023\-27522       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2023-27522](#https://vulners.com/osv/OSV:BIT-APACHE-2023-27522)

|       OSV:BIT\-APACHE\-2022\-37436       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2022-37436](#https://vulners.com/osv/OSV:BIT-APACHE-2022-37436)

|       OSV:BIT\-APACHE\-2022\-30556       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2022-30556](#https://vulners.com/osv/OSV:BIT-APACHE-2022-30556)

|       OSV:BIT\-APACHE\-2022\-30522       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2022-30522](#https://vulners.com/osv/OSV:BIT-APACHE-2022-30522)

|       OSV:BIT\-APACHE\-2022\-29404       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2022-29404](#https://vulners.com/osv/OSV:BIT-APACHE-2022-29404)

|       OSV:BIT\-APACHE\-2022\-28614       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2022-28614](#https://vulners.com/osv/OSV:BIT-APACHE-2022-28614)

|       OSV:BIT\-APACHE\-2022\-28330       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2022-28330](#https://vulners.com/osv/OSV:BIT-APACHE-2022-28330)

|       OSV:BIT\-APACHE\-2022\-26377       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2022-26377](#https://vulners.com/osv/OSV:BIT-APACHE-2022-26377)

|       OSV:BIT\-APACHE\-2022\-22719       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2022-22719](#https://vulners.com/osv/OSV:BIT-APACHE-2022-22719)

|       OSV:BIT\-APACHE\-2021\-41524       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2021-41524](#https://vulners.com/osv/OSV:BIT-APACHE-2021-41524)

|       OSV:BIT\-APACHE\-2021\-36160       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2021-36160](#https://vulners.com/osv/OSV:BIT-APACHE-2021-36160)

|       OSV:BIT\-APACHE\-2021\-34798       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2021-34798](#https://vulners.com/osv/OSV:BIT-APACHE-2021-34798)

|       OSV:BIT\-APACHE\-2021\-33193       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2021-33193](#https://vulners.com/osv/OSV:BIT-APACHE-2021-33193)

|       OSV:BIT\-APACHE\-2021\-31618       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2021-31618](#https://vulners.com/osv/OSV:BIT-APACHE-2021-31618)

|       OSV:BIT\-APACHE\-2021\-30641       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2021-30641](#https://vulners.com/osv/OSV:BIT-APACHE-2021-30641)

|       OSV:BIT\-APACHE\-2021\-26690       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2021-26690](#https://vulners.com/osv/OSV:BIT-APACHE-2021-26690)

|       OSV:BIT\-APACHE\-2020\-9490        5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2020-9490](#https://vulners.com/osv/OSV:BIT-APACHE-2020-9490)

|       OSV:BIT\-APACHE\-2020\-1934        5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2020-1934](#https://vulners.com/osv/OSV:BIT-APACHE-2020-1934)

|       OSV:BIT\-APACHE\-2020\-13950       5\.0     [https://vulners.com/osv/OSV:BIT-APACHE-2020-13950](#https://vulners.com/osv/OSV:BIT-APACHE-2020-13950)

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
|       CVE\-2023\-31122  5\.0     [https://vulners.com/cve/CVE-2023-31122](#https://vulners.com/cve/CVE-2023-31122)

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

|       CVE\-2014\-3581   5\.0     [https://vulners.com/cve/CVE-2014-3581](#https://vulners.com/cve/CVE-2014-3581)

|       CVE\-2014\-0231   5\.0     [https://vulners.com/cve/CVE-2014-0231](#https://vulners.com/cve/CVE-2014-0231)

|       CVE\-2014\-0098   5\.0     [https://vulners.com/cve/CVE-2014-0098](#https://vulners.com/cve/CVE-2014-0098)

|       CVE\-2013\-6438   5\.0     [https://vulners.com/cve/CVE-2013-6438](#https://vulners.com/cve/CVE-2013-6438)

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
|       5A864BCC\-B490\-5532\-83AB\-2E4109BB3C31    5\.0     [https://vulners.com/githubexploit/5A864BCC-B490-5532-83AB-2E4109BB3C31](#https://vulners.com/githubexploit/5A864BCC-B490-5532-83AB-2E4109BB3C31)
\*EXPLOIT\*
|       17C6AD2A\-8469\-56C8\-BBBE\-1764D0DF1680    5\.0     [https://vulners.com/githubexploit/17C6AD2A-8469-56C8-BBBE-1764D0DF1680](#https://vulners.com/githubexploit/17C6AD2A-8469-56C8-BBBE-1764D0DF1680)
\*EXPLOIT\*
|       1337DAY\-ID\-28573        5\.0     [https://vulners.com/zdt/1337DAY-ID-28573](#https://vulners.com/zdt/1337DAY-ID-28573)
\*EXPLOIT\*
|       1337DAY\-ID\-26574        5\.0     [https://vulners.com/zdt/1337DAY-ID-26574](#https://vulners.com/zdt/1337DAY-ID-26574)
\*EXPLOIT\*
|       SSV:87152       4\.3     [https://vulners.com/seebug/SSV:87152](#https://vulners.com/seebug/SSV:87152)
\*EXPLOIT\*
|       PACKETSTORM:127563      4\.3     [https://vulners.com/packetstorm/PACKETSTORM:127563](#https://vulners.com/packetstorm/PACKETSTORM:127563)
\*EXPLOIT\*
|       OSV:BIT\-APACHE\-2020\-11993       4\.3     [https://vulners.com/osv/OSV:BIT-APACHE-2020-11993](#https://vulners.com/osv/OSV:BIT-APACHE-2020-11993)

|       OSV:BIT\-APACHE\-2020\-11985       4\.3     [https://vulners.com/osv/OSV:BIT-APACHE-2020-11985](#https://vulners.com/osv/OSV:BIT-APACHE-2020-11985)

|       FF610CB4\-801A\-5D1D\-9AC9\-ADFC287C8482    4\.3     [https://vulners.com/githubexploit/FF610CB4-801A-5D1D-9AC9-ADFC287C8482](#https://vulners.com/githubexploit/FF610CB4-801A-5D1D-9AC9-ADFC287C8482)
\*EXPLOIT\*
|       FDF4BBB1\-979C\-5320\-95EA\-9EC7EB064D72    4\.3     [https://vulners.com/githubexploit/FDF4BBB1-979C-5320-95EA-9EC7EB064D72](#https://vulners.com/githubexploit/FDF4BBB1-979C-5320-95EA-9EC7EB064D72)
\*EXPLOIT\*
|       FCAF01A0\-F921\-5DB1\-BBC5\-850EC2DC5C46    4\.3     [https://vulners.com/githubexploit/FCAF01A0-F921-5DB1-BBC5-850EC2DC5C46](#https://vulners.com/githubexploit/FCAF01A0-F921-5DB1-BBC5-850EC2DC5C46)
\*EXPLOIT\*
|       EDB\-ID:50383    4\.3     [https://vulners.com/exploitdb/EDB-ID:50383](#https://vulners.com/exploitdb/EDB-ID:50383)
\*EXPLOIT\*
|       E7B177F6\-FA62\-52FE\-A108\-4B8FC8112B7F    4\.3     [https://vulners.com/githubexploit/E7B177F6-FA62-52FE-A108-4B8FC8112B7F](#https://vulners.com/githubexploit/E7B177F6-FA62-52FE-A108-4B8FC8112B7F)
\*EXPLOIT\*
|       E6B39247\-8016\-5007\-B505\-699F05FCA1B5    4\.3     [https://vulners.com/githubexploit/E6B39247-8016-5007-B505-699F05FCA1B5](#https://vulners.com/githubexploit/E6B39247-8016-5007-B505-699F05FCA1B5)
\*EXPLOIT\*
|       DBF996C3\-DC2A\-5859\-B767\-6B2FC38F2185    4\.3     [https://vulners.com/githubexploit/DBF996C3-DC2A-5859-B767-6B2FC38F2185](#https://vulners.com/githubexploit/DBF996C3-DC2A-5859-B767-6B2FC38F2185)
\*EXPLOIT\*
|       D0E79214\-C9E8\-52BD\-BC24\-093970F5F34E    4\.3     [https://vulners.com/githubexploit/D0E79214-C9E8-52BD-BC24-093970F5F34E](#https://vulners.com/githubexploit/D0E79214-C9E8-52BD-BC24-093970F5F34E)
\*EXPLOIT\*
|       CVE\-2020\-11985  4\.3     [https://vulners.com/cve/CVE-2020-11985](#https://vulners.com/cve/CVE-2020-11985)

|       CVE\-2019\-10092  4\.3     [https://vulners.com/cve/CVE-2019-10092](#https://vulners.com/cve/CVE-2019-10092)

|       CVE\-2018\-1302   4\.3     [https://vulners.com/cve/CVE-2018-1302](#https://vulners.com/cve/CVE-2018-1302)

|       CVE\-2018\-1301   4\.3     [https://vulners.com/cve/CVE-2018-1301](#https://vulners.com/cve/CVE-2018-1301)

|       CVE\-2016\-4975   4\.3     [https://vulners.com/cve/CVE-2016-4975](#https://vulners.com/cve/CVE-2016-4975)

|       CVE\-2015\-3185   4\.3     [https://vulners.com/cve/CVE-2015-3185](#https://vulners.com/cve/CVE-2015-3185)

|       CVE\-2014\-8109   4\.3     [https://vulners.com/cve/CVE-2014-8109](#https://vulners.com/cve/CVE-2014-8109)

|       CVE\-2014\-0118   4\.3     [https://vulners.com/cve/CVE-2014-0118](#https://vulners.com/cve/CVE-2014-0118)

|       CVE\-2014\-0117   4\.3     [https://vulners.com/cve/CVE-2014-0117](#https://vulners.com/cve/CVE-2014-0117)

|       CVE\-2013\-4352   4\.3     [https://vulners.com/cve/CVE-2013-4352](#https://vulners.com/cve/CVE-2013-4352)

|       CVE\-2013\-1896   4\.3     [https://vulners.com/cve/CVE-2013-1896](#https://vulners.com/cve/CVE-2013-1896)

|       CF47F8BF\-37F7\-5EF9\-ABAB\-E88ECF6B64FE    4\.3     [https://vulners.com/githubexploit/CF47F8BF-37F7-5EF9-ABAB-E88ECF6B64FE](#https://vulners.com/githubexploit/CF47F8BF-37F7-5EF9-ABAB-E88ECF6B64FE)
\*EXPLOIT\*
|       CD48BD40\-E52A\-5A8B\-AE27\-B57C358BB0EE    4\.3     [https://vulners.com/githubexploit/CD48BD40-E52A-5A8B-AE27-B57C358BB0EE](#https://vulners.com/githubexploit/CD48BD40-E52A-5A8B-AE27-B57C358BB0EE)
\*EXPLOIT\*
|       C8C7BBD4\-C089\-5DA7\-8474\-A5B2B7DC5E79    4\.3     [https://vulners.com/githubexploit/C8C7BBD4-C089-5DA7-8474-A5B2B7DC5E79](#https://vulners.com/githubexploit/C8C7BBD4-C089-5DA7-8474-A5B2B7DC5E79)
\*EXPLOIT\*
|       C8799CA3\-C88C\-5B39\-B291\-2895BE0D9133    4\.3     [https://vulners.com/githubexploit/C8799CA3-C88C-5B39-B291-2895BE0D9133](#https://vulners.com/githubexploit/C8799CA3-C88C-5B39-B291-2895BE0D9133)
\*EXPLOIT\*
|       C0380E16\-C468\-5540\-A427\-7FE34E7CF36B    4\.3     [https://vulners.com/githubexploit/C0380E16-C468-5540-A427-7FE34E7CF36B](#https://vulners.com/githubexploit/C0380E16-C468-5540-A427-7FE34E7CF36B)
\*EXPLOIT\*
|       BC027F41\-02AD\-5D71\-A452\-4DD62B0F1EE1    4\.3     [https://vulners.com/githubexploit/BC027F41-02AD-5D71-A452-4DD62B0F1EE1](#https://vulners.com/githubexploit/BC027F41-02AD-5D71-A452-4DD62B0F1EE1)
\*EXPLOIT\*
|       B946B2A1\-2914\-537A\-BF26\-94B48FC501B3    4\.3     [https://vulners.com/githubexploit/B946B2A1-2914-537A-BF26-94B48FC501B3](#https://vulners.com/githubexploit/B946B2A1-2914-537A-BF26-94B48FC501B3)
\*EXPLOIT\*
|       B9151905\-5395\-5622\-B789\-E16B88F30C71    4\.3     [https://vulners.com/githubexploit/B9151905-5395-5622-B789-E16B88F30C71](#https://vulners.com/githubexploit/B9151905-5395-5622-B789-E16B88F30C71)
\*EXPLOIT\*
|       B58E6202\-6D04\-5CB0\-8529\-59713C0E13B8    4\.3     [https://vulners.com/githubexploit/B58E6202-6D04-5CB0-8529-59713C0E13B8](#https://vulners.com/githubexploit/B58E6202-6D04-5CB0-8529-59713C0E13B8)
\*EXPLOIT\*
|       B53D7077\-1A2B\-5640\-9581\-0196F6138301    4\.3     [https://vulners.com/githubexploit/B53D7077-1A2B-5640-9581-0196F6138301](#https://vulners.com/githubexploit/B53D7077-1A2B-5640-9581-0196F6138301)
\*EXPLOIT\*
|       A9C7FB0F\-65EC\-5557\-B6E8\-6AFBBF8F140F    4\.3     [https://vulners.com/githubexploit/A9C7FB0F-65EC-5557-B6E8-6AFBBF8F140F](#https://vulners.com/githubexploit/A9C7FB0F-65EC-5557-B6E8-6AFBBF8F140F)
\*EXPLOIT\*
|       9EE3F7E3\-70E6\-503E\-9929\-67FE3F3735A2    4\.3     [https://vulners.com/githubexploit/9EE3F7E3-70E6-503E-9929-67FE3F3735A2](#https://vulners.com/githubexploit/9EE3F7E3-70E6-503E-9929-67FE3F3735A2)
\*EXPLOIT\*
|       9D511461\-7D24\-5402\-8E2A\-58364D6E758F    4\.3     [https://vulners.com/githubexploit/9D511461-7D24-5402-8E2A-58364D6E758F](#https://vulners.com/githubexploit/9D511461-7D24-5402-8E2A-58364D6E758F)
\*EXPLOIT\*
|       9CEA663C\-6236\-5F45\-B207\-A873B971F988    4\.3     [https://vulners.com/githubexploit/9CEA663C-6236-5F45-B207-A873B971F988](#https://vulners.com/githubexploit/9CEA663C-6236-5F45-B207-A873B971F988)
\*EXPLOIT\*
|       987C6FDB\-3E70\-5FF5\-AB5B\-D50065D27594    4\.3     [https://vulners.com/githubexploit/987C6FDB-3E70-5FF5-AB5B-D50065D27594](#https://vulners.com/githubexploit/987C6FDB-3E70-5FF5-AB5B-D50065D27594)
\*EXPLOIT\*
|       789B6112\-E84C\-566E\-89A7\-82CC108EFCD9    4\.3     [https://vulners.com/githubexploit/789B6112-E84C-566E-89A7-82CC108EFCD9](#https://vulners.com/githubexploit/789B6112-E84C-566E-89A7-82CC108EFCD9)
\*EXPLOIT\*
|       788F7DF8\-01F3\-5D13\-9B3E\-E4AA692153E6    4\.3     [https://vulners.com/githubexploit/788F7DF8-01F3-5D13-9B3E-E4AA692153E6](#https://vulners.com/githubexploit/788F7DF8-01F3-5D13-9B3E-E4AA692153E6)
\*EXPLOIT\*
|       749F952B\-3ACF\-56B2\-809D\-D66E756BE839    4\.3     [https://vulners.com/githubexploit/749F952B-3ACF-56B2-809D-D66E756BE839](#https://vulners.com/githubexploit/749F952B-3ACF-56B2-809D-D66E756BE839)
\*EXPLOIT\*
|       6E484197\-456B\-55DF\-8D51\-C2BB4925F45C    4\.3     [https://vulners.com/githubexploit/6E484197-456B-55DF-8D51-C2BB4925F45C](#https://vulners.com/githubexploit/6E484197-456B-55DF-8D51-C2BB4925F45C)
\*EXPLOIT\*
|       68E78C64\-D93A\-5E8B\-9DEA\-4A8D826B474E    4\.3     [https://vulners.com/githubexploit/68E78C64-D93A-5E8B-9DEA-4A8D826B474E](#https://vulners.com/githubexploit/68E78C64-D93A-5E8B-9DEA-4A8D826B474E)
\*EXPLOIT\*
|       6758CFA9\-271A\-5E99\-A590\-E51F4E0C5046    4\.3     [https://vulners.com/githubexploit/6758CFA9-271A-5E99-A590-E51F4E0C5046](#https://vulners.com/githubexploit/6758CFA9-271A-5E99-A590-E51F4E0C5046)
\*EXPLOIT\*
|       674BA200\-C494\-57E6\-B1B4\-1672DDA15D3C    4\.3     [https://vulners.com/githubexploit/674BA200-C494-57E6-B1B4-1672DDA15D3C](#https://vulners.com/githubexploit/674BA200-C494-57E6-B1B4-1672DDA15D3C)
\*EXPLOIT\*
|       5A54F5DA\-F9C1\-508B\-AD2D\-3E45CD647D31    4\.3     [https://vulners.com/githubexploit/5A54F5DA-F9C1-508B-AD2D-3E45CD647D31](#https://vulners.com/githubexploit/5A54F5DA-F9C1-508B-AD2D-3E45CD647D31)
\*EXPLOIT\*
|       4E5A5BA8\-3BAF\-57F0\-B71A\-F04B4D066E4F    4\.3     [https://vulners.com/githubexploit/4E5A5BA8-3BAF-57F0-B71A-F04B4D066E4F](#https://vulners.com/githubexploit/4E5A5BA8-3BAF-57F0-B71A-F04B4D066E4F)
\*EXPLOIT\*
|       4C79D8E5\-D595\-5460\-AA84\-18D4CB93E8FC    4\.3     [https://vulners.com/githubexploit/4C79D8E5-D595-5460-AA84-18D4CB93E8FC](#https://vulners.com/githubexploit/4C79D8E5-D595-5460-AA84-18D4CB93E8FC)
\*EXPLOIT\*
|       4B44115D\-85A3\-5E62\-B9A8\-5F336C24673F    4\.3     [https://vulners.com/githubexploit/4B44115D-85A3-5E62-B9A8-5F336C24673F](#https://vulners.com/githubexploit/4B44115D-85A3-5E62-B9A8-5F336C24673F)
\*EXPLOIT\*
|       4013EC74\-B3C1\-5D95\-938A\-54197A58586D    4\.3     [https://vulners.com/githubexploit/4013EC74-B3C1-5D95-938A-54197A58586D](#https://vulners.com/githubexploit/4013EC74-B3C1-5D95-938A-54197A58586D)
\*EXPLOIT\*
|       3CF66144\-235E\-5F7A\-B889\-113C11ABF150    4\.3     [https://vulners.com/githubexploit/3CF66144-235E-5F7A-B889-113C11ABF150](#https://vulners.com/githubexploit/3CF66144-235E-5F7A-B889-113C11ABF150)
\*EXPLOIT\*
|       379FCF38\-0B4A\-52EC\-BE3E\-408A0467BF20    4\.3     [https://vulners.com/githubexploit/379FCF38-0B4A-52EC-BE3E-408A0467BF20](#https://vulners.com/githubexploit/379FCF38-0B4A-52EC-BE3E-408A0467BF20)
\*EXPLOIT\*
|       365CD0B0\-D956\-59D6\-9500\-965BF4017E2D    4\.3     [https://vulners.com/githubexploit/365CD0B0-D956-59D6-9500-965BF4017E2D](#https://vulners.com/githubexploit/365CD0B0-D956-59D6-9500-965BF4017E2D)
\*EXPLOIT\*
|       2E98EA81\-24D1\-5D5B\-80B9\-A8D616BF3C3F    4\.3     [https://vulners.com/githubexploit/2E98EA81-24D1-5D5B-80B9-A8D616BF3C3F](#https://vulners.com/githubexploit/2E98EA81-24D1-5D5B-80B9-A8D616BF3C3F)
\*EXPLOIT\*
|       2B4FEB27\-377B\-557B\-AE46\-66D677D5DA1C    4\.3     [https://vulners.com/githubexploit/2B4FEB27-377B-557B-AE46-66D677D5DA1C](#https://vulners.com/githubexploit/2B4FEB27-377B-557B-AE46-66D677D5DA1C)
\*EXPLOIT\*
|       1B75F2E2\-5B30\-58FA\-98A4\-501B91327D7F    4\.3     [https://vulners.com/githubexploit/1B75F2E2-5B30-58FA-98A4-501B91327D7F](#https://vulners.com/githubexploit/1B75F2E2-5B30-58FA-98A4-501B91327D7F)
\*EXPLOIT\*
|       1337DAY\-ID\-35422        4\.3     [https://vulners.com/zdt/1337DAY-ID-35422](#https://vulners.com/zdt/1337DAY-ID-35422)
\*EXPLOIT\*
|       1337DAY\-ID\-33575        4\.3     [https://vulners.com/zdt/1337DAY-ID-33575](#https://vulners.com/zdt/1337DAY-ID-33575)
\*EXPLOIT\*
|       1145F3D1\-0ECB\-55AA\-B25D\-A26892116505    4\.3     [https://vulners.com/githubexploit/1145F3D1-0ECB-55AA-B25D-A26892116505](#https://vulners.com/githubexploit/1145F3D1-0ECB-55AA-B25D-A26892116505)
\*EXPLOIT\*
|       108A0713\-4AB8\-5A1F\-A16B\-4BB13ECEC9B2    4\.3     [https://vulners.com/githubexploit/108A0713-4AB8-5A1F-A16B-4BB13ECEC9B2](#https://vulners.com/githubexploit/108A0713-4AB8-5A1F-A16B-4BB13ECEC9B2)
\*EXPLOIT\*
|       0BC014D0\-F944\-5E78\-B5FA\-146A8E5D0F8A    4\.3     [https://vulners.com/githubexploit/0BC014D0-F944-5E78-B5FA-146A8E5D0F8A](#https://vulners.com/githubexploit/0BC014D0-F944-5E78-B5FA-146A8E5D0F8A)
\*EXPLOIT\*
|       06076ECD\-3FB7\-53EC\-8572\-ABBB20029812    4\.3     [https://vulners.com/githubexploit/06076ECD-3FB7-53EC-8572-ABBB20029812](#https://vulners.com/githubexploit/06076ECD-3FB7-53EC-8572-ABBB20029812)
\*EXPLOIT\*
|       05403438\-4985\-5E78\-A702\-784E03F724D4    4\.3     [https://vulners.com/githubexploit/05403438-4985-5E78-A702-784E03F724D4](#https://vulners.com/githubexploit/05403438-4985-5E78-A702-784E03F724D4)
\*EXPLOIT\*
|       00EC8F03\-D8A3\-56D4\-9F8C\-8DD1F5ACCA08    4\.3     [https://vulners.com/githubexploit/00EC8F03-D8A3-56D4-9F8C-8DD1F5ACCA08](#https://vulners.com/githubexploit/00EC8F03-D8A3-56D4-9F8C-8DD1F5ACCA08)
\*EXPLOIT\*
|       CVE\-2018\-1283   3\.5     [https://vulners.com/cve/CVE-2018-1283](#https://vulners.com/cve/CVE-2018-1283)

|       CVE\-2016\-8612   3\.3     [https://vulners.com/cve/CVE-2016-8612](#https://vulners.com/cve/CVE-2016-8612)

|       CVE\-2023\-45802  2\.6     [https://vulners.com/cve/CVE-2023-45802](#https://vulners.com/cve/CVE-2023-45802)

|       OSV:BIT\-APACHE\-2020\-13938       2\.1     [https://vulners.com/osv/OSV:BIT-APACHE-2020-13938](#https://vulners.com/osv/OSV:BIT-APACHE-2020-13938)

|\_      PACKETSTORM:140265      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:140265](#https://vulners.com/packetstorm/PACKETSTORM:140265)
\*EXPLOIT\*
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
MAC Address: 08:00:27:29:3A:25 \(Oracle VirtualBox virtual NIC\)
Service Info: OS: Unix

**nikto \-url **[**http://192.168.0.24**](#http://192.168.0.24)
****
\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.0\.24
\+ Target Hostname:    192\.168\.0\.24
\+ Target Port:        80
\+ Start Time:         2024\-02\-06 11:54:00 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.4\.6 \(CentOS\) PHP/7\.2\.33
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ /index\.php?: Retrieved x\-powered\-by header: PHP/7\.2\.33\.
\+ PHP/7\.2\.33 appears to be outdated \(current is at least 8\.1\.5\), PHP 7\.4\.28 for the 7\.4 branch\.
\+ Apache/2\.4\.6 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ Multiple index files found: /index\.html, /index\.php\.
\+ OPTIONS: Allowed HTTP Methods: GET, HEAD, POST, OPTIONS, TRACE \.
\+ /: HTTP TRACE method is active which suggests the host is vulnerable to XST\. See: [https://owasp.org/www-community/attacks/Cross_Site_Tracing](#https://owasp.org/www-community/attacks/Cross_Site_Tracing)

\+ /phpinfo\.php: Output from the phpinfo\(\) function was found\.
\+ /css/: Directory indexing found\.
\+ /css/: This might be interesting\.
\+ /data/: Directory indexing found\.
\+ /data/: This might be interesting\.
\+ /img/: Directory indexing found\.
\+ /img/: This might be interesting\.
\+ /phpmyadmin/changelog\.php: Uncommon header 'x\-ob\_mode' found, with contents: 1\.
\+ /phpmyadmin/changelog\.php: Cookie goto created without the httponly flag\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

\+ /phpmyadmin/changelog\.php: Cookie back created without the httponly flag\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

\+ /phpmyadmin/ChangeLog: phpMyAdmin is for managing MySQL databases, and should be protected or limited to authorized hosts\.
\+ /webmail/src/read\_body\.php: Cookie SQMSESSID created without the httponly flag\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

\+ /webmail/src/read\_body\.php: SquirrelMail found\.
\+ /phpinfo\.php: PHP is installed, and a test script which runs phpinfo\(\) was found\. This gives a lot of system information\. See: CWE\-552
\+ /icons/: Directory indexing found\.
\+ /icons/README: Apache default file found\. See: [https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/](#https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/)

\+ /webmail/src/configtest\.php: Squirrelmail configuration test may reveal version and system info\.
\+ /phpmyadmin/: phpMyAdmin directory found\.
\+ /phpmyadmin/README: phpMyAdmin is for managing MySQL databases, and should be protected or limited to authorized hosts\. See: [https://typo3.org/](#https://typo3.org/)

\+ /package\.json: Node\.js package file found\. It may contain sensitive information\.
\+ 8909 requests: 0 error\(s\) and 28 item\(s\) reported on remote host
\+ End Time:           2024\-02\-06 11:54:19 \(GMT\-5\) \(19 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested

**gobuster dir \-u **[**http://192.168.0.24**](#http://192.168.0.24)
**\-w /usr/share/wordlists/seclists/Discovery/Web\-Content/combined\_words\.txt \-t 100**
===============================================================
Gobuster v3\.6
by OJ Reeves \(@TheColonial\) \& Christian Mehlmauer \(@firefart\)
===============================================================
\[\+\] Url:                     [http://192.168.0.24](#http://192.168.0.24)

\[\+\] Method:                  GET
\[\+\] Threads:                 100
\[\+\] Wordlist:                /usr/share/wordlists/seclists/Discovery/Web\-Content/combined\_words\.txt
\[\+\] Negative Status codes:   404
\[\+\] User Agent:              gobuster/3\.6
\[\+\] Timeout:                 10s
===============================================================
Starting gobuster in directory enumeration mode
===============================================================
/\.hta                 \(Status: 403\) \[Size: 206\]
/cgi\-bin/             \(Status: 403\) \[Size: 210\]
/css                  \(Status: 301\) \[Size: 232\] \[\-\-\> [http://192.168.0.24/css/\]](#http://192.168.0.24/css/])

/data                 \(Status: 301\) \[Size: 233\] \[\-\-\> [http://192.168.0.24/data/\]](#http://192.168.0.24/data/])

/fonts                \(Status: 301\) \[Size: 234\] \[\-\-\> [http://192.168.0.24/fonts/\]](#http://192.168.0.24/fonts/])

/img                  \(Status: 301\) \[Size: 232\] \[\-\-\> [http://192.168.0.24/img/\]](#http://192.168.0.24/img/])

/index\.html           \(Status: 200\) \[Size: 22263\]
/index\.php            \(Status: 200\) \[Size: 31\]
/js                   \(Status: 301\) \[Size: 231\] \[\-\-\> [http://192.168.0.24/js/\]](#http://192.168.0.24/js/])

/licence              \(Status: 200\) \[Size: 57\]
/monitoring           \(Status: 301\) \[Size: 239\] \[\-\-\> [http://192.168.0.24/monitoring/\]](#http://192.168.0.24/monitoring/])

/news                 \(Status: 301\) \[Size: 233\] \[\-\-\> [http://192.168.0.24/news/\]](#http://192.168.0.24/news/])

/phpinfo\.php          \(Status: 200\) \[Size: 85266\]
/phpmyadmin           \(Status: 301\) \[Size: 239\] \[\-\-\> [http://192.168.0.24/phpmyadmin/\]](#http://192.168.0.24/phpmyadmin/])

/webmail              \(Status: 301\) \[Size: 236\] \[\-\-\> [http://192.168.0.24/webmail/\]](#http://192.168.0.24/webmail/])


**gobuster dir \-u **[**http://192.168.0.24**](#http://192.168.0.24)
**\-w /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt \-t 100 **
===============================================================
Gobuster v3\.6
by OJ Reeves \(@TheColonial\) \& Christian Mehlmauer \(@firefart\)
===============================================================
\[\+\] Url:                     [http://192.168.0.24](#http://192.168.0.24)

\[\+\] Method:                  GET
\[\+\] Threads:                 100
\[\+\] Wordlist:                /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt
\[\+\] Negative Status codes:   404
\[\+\] User Agent:              gobuster/3\.6
\[\+\] Timeout:                 10s
===============================================================
Starting gobuster in directory enumeration mode
===============================================================
/data                 \(Status: 301\) \[Size: 233\] \[\-\-\> [http://192.168.0.24/data/\]](#http://192.168.0.24/data/])

/css                  \(Status: 301\) \[Size: 232\] \[\-\-\> [http://192.168.0.24/css/\]](#http://192.168.0.24/css/])

/js                   \(Status: 301\) \[Size: 231\] \[\-\-\> [http://192.168.0.24/js/\]](#http://192.168.0.24/js/])

/webmail              \(Status: 301\) \[Size: 236\] \[\-\-\> [http://192.168.0.24/webmail/\]](#http://192.168.0.24/webmail/])

/fonts                \(Status: 301\) \[Size: 234\] \[\-\-\> [http://192.168.0.24/fonts/\]](#http://192.168.0.24/fonts/])

/monitoring           \(Status: 301\) \[Size: 239\] \[\-\-\> [http://192.168.0.24/monitoring/\]](#http://192.168.0.24/monitoring/])

/news                 \(Status: 301\) \[Size: 233\] \[\-\-\> [http://192.168.0.24/news/\]](#http://192.168.0.24/news/])

/img                  \(Status: 301\) \[Size: 232\] \[\-\-\> [http://192.168.0.24/img/\]](#http://192.168.0.24/img/])

/licence              \(Status: 200\) \[Size: 57\]
/phpmyadmin           \(Status: 301\) \[Size: 239\] \[\-\-\> [http://192.168.0.24/phpmyadmin/\]](#http://192.168.0.24/phpmyadmin/])

Progress: 220560 / 220561 \(100\.00%\)
===============================================================
Finished
===============================================================
