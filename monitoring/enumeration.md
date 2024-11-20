**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.0\.128**
PORT    STATE SERVICE  VERSION
22/tcp  open  ssh      OpenSSH 7\.2p2 Ubuntu 4ubuntu2\.10 \(Ubuntu Linux; protocol 2\.0\)
| vulners: 
|   cpe:/a:openbsd:openssh:7\.2p2: 
|       PRION:CVE\-2016\-8858     7\.8     [https://vulners.com/prion/PRION:CVE-2016-8858](#https://vulners.com/prion/PRION:CVE-2016-8858)

|       PRION:CVE\-2016\-6515     7\.8     [https://vulners.com/prion/PRION:CVE-2016-6515](#https://vulners.com/prion/PRION:CVE-2016-6515)

|       PACKETSTORM:140070      7\.8     [https://vulners.com/packetstorm/PACKETSTORM:140070*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:140070*EXPLOIT*)

|       EXPLOITPACK:5BCA798C6BA71FAE29334297EC0B6A09    7\.8     [https://vulners.com/exploitpack/EXPLOITPACK:5BCA798C6BA71FAE29334297EC0B6A09](#https://vulners.com/exploitpack/EXPLOITPACK:5BCA798C6BA71FAE29334297EC0B6A09)
\*EXPLOIT\*
|       EDB\-ID:40888    7\.8     [https://vulners.com/exploitdb/EDB-ID:40888](#https://vulners.com/exploitdb/EDB-ID:40888)
\*EXPLOIT\*
|       CVE\-2016\-8858   7\.8     [https://vulners.com/cve/CVE-2016-8858](#https://vulners.com/cve/CVE-2016-8858)

|       CVE\-2016\-6515   7\.8     [https://vulners.com/cve/CVE-2016-6515](#https://vulners.com/cve/CVE-2016-6515)

|       1337DAY\-ID\-26494        7\.8     [https://vulners.com/zdt/1337DAY-ID-26494](#https://vulners.com/zdt/1337DAY-ID-26494)
\*EXPLOIT\*
|       SSV:92579       7\.5     [https://vulners.com/seebug/SSV:92579](#https://vulners.com/seebug/SSV:92579)
\*EXPLOIT\*
|       PRION:CVE\-2023\-35784    7\.5     [https://vulners.com/prion/PRION:CVE-2023-35784](#https://vulners.com/prion/PRION:CVE-2023-35784)

|       PRION:CVE\-2016\-10009    7\.5     [https://vulners.com/prion/PRION:CVE-2016-10009](#https://vulners.com/prion/PRION:CVE-2016-10009)

|       PACKETSTORM:173661      7\.5     [https://vulners.com/packetstorm/PACKETSTORM:173661*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:173661*EXPLOIT*)

|       CVE\-2023\-35784  7\.5     [https://vulners.com/cve/CVE-2023-35784](#https://vulners.com/cve/CVE-2023-35784)

|       CVE\-2016\-10009  7\.5     [https://vulners.com/cve/CVE-2016-10009](#https://vulners.com/cve/CVE-2016-10009)

|       1337DAY\-ID\-26576        7\.5     [https://vulners.com/zdt/1337DAY-ID-26576](#https://vulners.com/zdt/1337DAY-ID-26576)
\*EXPLOIT\*
|       SSV:92582       7\.2     [https://vulners.com/seebug/SSV:92582](#https://vulners.com/seebug/SSV:92582)
\*EXPLOIT\*
|       PRION:CVE\-2016\-10012    7\.2     [https://vulners.com/prion/PRION:CVE-2016-10012](#https://vulners.com/prion/PRION:CVE-2016-10012)

|       PRION:CVE\-2015\-8325     7\.2     [https://vulners.com/prion/PRION:CVE-2015-8325](#https://vulners.com/prion/PRION:CVE-2015-8325)

|       CVE\-2016\-10012  7\.2     [https://vulners.com/cve/CVE-2016-10012](#https://vulners.com/cve/CVE-2016-10012)

|       CVE\-2015\-8325   7\.2     [https://vulners.com/cve/CVE-2015-8325](#https://vulners.com/cve/CVE-2015-8325)

|       SSV:92580       6\.9     [https://vulners.com/seebug/SSV:92580](#https://vulners.com/seebug/SSV:92580)
\*EXPLOIT\*
|       PRION:CVE\-2016\-10010    6\.9     [https://vulners.com/prion/PRION:CVE-2016-10010](#https://vulners.com/prion/PRION:CVE-2016-10010)

|       CVE\-2016\-10010  6\.9     [https://vulners.com/cve/CVE-2016-10010](#https://vulners.com/cve/CVE-2016-10010)

|       1337DAY\-ID\-26577        6\.9     [https://vulners.com/zdt/1337DAY-ID-26577](#https://vulners.com/zdt/1337DAY-ID-26577)
\*EXPLOIT\*
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
|       SSV:91041       5\.5     [https://vulners.com/seebug/SSV:91041](#https://vulners.com/seebug/SSV:91041)
\*EXPLOIT\*
|       PRION:CVE\-2016\-3115     5\.5     [https://vulners.com/prion/PRION:CVE-2016-3115](#https://vulners.com/prion/PRION:CVE-2016-3115)

|       PACKETSTORM:140019      5\.5     [https://vulners.com/packetstorm/PACKETSTORM:140019*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:140019*EXPLOIT*)

|       PACKETSTORM:136234      5\.5     [https://vulners.com/packetstorm/PACKETSTORM:136234*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:136234*EXPLOIT*)

|       EXPLOITPACK:F92411A645D85F05BDBD274FD222226F    5\.5     [https://vulners.com/exploitpack/EXPLOITPACK:F92411A645D85F05BDBD274FD222226F](#https://vulners.com/exploitpack/EXPLOITPACK:F92411A645D85F05BDBD274FD222226F)
\*EXPLOIT\*
|       EXPLOITPACK:9F2E746846C3C623A27A441281EAD138    5\.5     [https://vulners.com/exploitpack/EXPLOITPACK:9F2E746846C3C623A27A441281EAD138](#https://vulners.com/exploitpack/EXPLOITPACK:9F2E746846C3C623A27A441281EAD138)
\*EXPLOIT\*
|       EXPLOITPACK:1902C998CBF9154396911926B4C3B330    5\.5     [https://vulners.com/exploitpack/EXPLOITPACK:1902C998CBF9154396911926B4C3B330](#https://vulners.com/exploitpack/EXPLOITPACK:1902C998CBF9154396911926B4C3B330)
\*EXPLOIT\*
|       EDB\-ID:40858    5\.5     [https://vulners.com/exploitdb/EDB-ID:40858](#https://vulners.com/exploitdb/EDB-ID:40858)
\*EXPLOIT\*
|       EDB\-ID:40119    5\.5     [https://vulners.com/exploitdb/EDB-ID:40119](#https://vulners.com/exploitdb/EDB-ID:40119)
\*EXPLOIT\*
|       EDB\-ID:39569    5\.5     [https://vulners.com/exploitdb/EDB-ID:39569](#https://vulners.com/exploitdb/EDB-ID:39569)
\*EXPLOIT\*
|       CVE\-2016\-3115   5\.5     [https://vulners.com/cve/CVE-2016-3115](#https://vulners.com/cve/CVE-2016-3115)

|       SSH\_ENUM        5\.0     [https://vulners.com/canvas/SSH_ENUM](#https://vulners.com/canvas/SSH_ENUM)
\*EXPLOIT\*
|       PRION:CVE\-2023\-27567    5\.0     [https://vulners.com/prion/PRION:CVE-2023-27567](#https://vulners.com/prion/PRION:CVE-2023-27567)

|       PRION:CVE\-2018\-15919    5\.0     [https://vulners.com/prion/PRION:CVE-2018-15919](#https://vulners.com/prion/PRION:CVE-2018-15919)

|       PRION:CVE\-2018\-15473    5\.0     [https://vulners.com/prion/PRION:CVE-2018-15473](#https://vulners.com/prion/PRION:CVE-2018-15473)

|       PRION:CVE\-2017\-15906    5\.0     [https://vulners.com/prion/PRION:CVE-2017-15906](#https://vulners.com/prion/PRION:CVE-2017-15906)

|       PRION:CVE\-2016\-10708    5\.0     [https://vulners.com/prion/PRION:CVE-2016-10708](#https://vulners.com/prion/PRION:CVE-2016-10708)

|       PACKETSTORM:150621      5\.0     [https://vulners.com/packetstorm/PACKETSTORM:150621*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:150621*EXPLOIT*)

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

|       PRION:CVE\-2023\-29323    4\.3     [https://vulners.com/prion/PRION:CVE-2023-29323](#https://vulners.com/prion/PRION:CVE-2023-29323)

|       PRION:CVE\-2016\-6210     4\.3     [https://vulners.com/prion/PRION:CVE-2016-6210](#https://vulners.com/prion/PRION:CVE-2016-6210)

|       EXPLOITPACK:802AF3229492E147A5F09C7F2B27C6DF    4\.3     [https://vulners.com/exploitpack/EXPLOITPACK:802AF3229492E147A5F09C7F2B27C6DF](#https://vulners.com/exploitpack/EXPLOITPACK:802AF3229492E147A5F09C7F2B27C6DF)
\*EXPLOIT\*
|       EXPLOITPACK:5652DDAA7FE452E19AC0DC1CD97BA3EF    4\.3     [https://vulners.com/exploitpack/EXPLOITPACK:5652DDAA7FE452E19AC0DC1CD97BA3EF](#https://vulners.com/exploitpack/EXPLOITPACK:5652DDAA7FE452E19AC0DC1CD97BA3EF)
\*EXPLOIT\*
|       EDB\-ID:40136    4\.3     [https://vulners.com/exploitdb/EDB-ID:40136](#https://vulners.com/exploitdb/EDB-ID:40136)
\*EXPLOIT\*
|       EDB\-ID:40113    4\.3     [https://vulners.com/exploitdb/EDB-ID:40113](#https://vulners.com/exploitdb/EDB-ID:40113)
\*EXPLOIT\*
|       CVE\-2023\-29323  4\.3     [https://vulners.com/cve/CVE-2023-29323](#https://vulners.com/cve/CVE-2023-29323)

|       CVE\-2020\-14145  4\.3     [https://vulners.com/cve/CVE-2020-14145](#https://vulners.com/cve/CVE-2020-14145)

|       CVE\-2016\-6210   4\.3     [https://vulners.com/cve/CVE-2016-6210](#https://vulners.com/cve/CVE-2016-6210)

|       1337DAY\-ID\-25440        4\.3     [https://vulners.com/zdt/1337DAY-ID-25440](#https://vulners.com/zdt/1337DAY-ID-25440)
\*EXPLOIT\*
|       1337DAY\-ID\-25438        4\.3     [https://vulners.com/zdt/1337DAY-ID-25438](#https://vulners.com/zdt/1337DAY-ID-25438)
\*EXPLOIT\*
|       PRION:CVE\-2019\-6110     4\.0     [https://vulners.com/prion/PRION:CVE-2019-6110](#https://vulners.com/prion/PRION:CVE-2019-6110)

|       PRION:CVE\-2019\-6109     4\.0     [https://vulners.com/prion/PRION:CVE-2019-6109](#https://vulners.com/prion/PRION:CVE-2019-6109)

|       CVE\-2019\-6110   4\.0     [https://vulners.com/cve/CVE-2019-6110](#https://vulners.com/cve/CVE-2019-6110)

|       CVE\-2019\-6109   4\.0     [https://vulners.com/cve/CVE-2019-6109](#https://vulners.com/cve/CVE-2019-6109)

|       PRION:CVE\-2019\-6111     2\.6     [https://vulners.com/prion/PRION:CVE-2019-6111](#https://vulners.com/prion/PRION:CVE-2019-6111)

|       PRION:CVE\-2018\-20685    2\.6     [https://vulners.com/prion/PRION:CVE-2018-20685](#https://vulners.com/prion/PRION:CVE-2018-20685)

|       CVE\-2018\-20685  2\.6     [https://vulners.com/cve/CVE-2018-20685](#https://vulners.com/cve/CVE-2018-20685)

|       SSV:92581       2\.1     [https://vulners.com/seebug/SSV:92581](#https://vulners.com/seebug/SSV:92581)
\*EXPLOIT\*
|       PRION:CVE\-2016\-10011    2\.1     [https://vulners.com/prion/PRION:CVE-2016-10011](#https://vulners.com/prion/PRION:CVE-2016-10011)

|       CVE\-2016\-10011  2\.1     [https://vulners.com/cve/CVE-2016-10011](#https://vulners.com/cve/CVE-2016-10011)

|       PACKETSTORM:151227      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:151227*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:151227*EXPLOIT*)

|       PACKETSTORM:140261      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:140261*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:140261*EXPLOIT*)

|       PACKETSTORM:138006      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:138006*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:138006*EXPLOIT*)

|       PACKETSTORM:137942      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:137942*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:137942*EXPLOIT*)

|\_      1337DAY\-ID\-30937        0\.0     [https://vulners.com/zdt/1337DAY-ID-30937](#https://vulners.com/zdt/1337DAY-ID-30937)
\*EXPLOIT\*
| ssh\-hostkey: 
|   2048 b8:8c:40:f6:5f:2a:8b:f7:92:a8:81:4b:bb:59:6d:02 \(RSA\)
|   256 e7:bb:11:c1:2e:cd:39:91:68:4e:aa:01:f6:de:e6:19 \(ECDSA\)
|\_  256 0f:8e:28:a7:b7:1d:60:bf:a6:2b:dd:a3:6d:d1:4e:a4 \(ED25519\)
25/tcp  open  smtp     Postfix smtpd
| smtp\-vuln\-cve2010\-4344: 
|\_  The SMTP server is not Exim: NOT VULNERABLE
|\_smtp\-commands: ubuntu, PIPELINING, SIZE 10240000, VRFY, ETRN, STARTTLS, ENHANCEDSTATUSCODES, 8BITMIME, DSN
| ssl\-cert: Subject: commonName=ubuntu
| Not valid before: 2020\-09\-08T17:59:00
|\_Not valid after:  2030\-09\-06T17:59:00
| ssl\-dh\-params: 
|   VULNERABLE:
|   Anonymous Diffie\-Hellman Key Exchange MitM Vulnerability
|     State: VULNERABLE
|       Transport Layer Security \(TLS\) services that use anonymous
|       Diffie\-Hellman key exchange only provide protection against passive
|       eavesdropping, and are vulnerable to active man\-in\-the\-middle attacks
|       which could completely compromise the confidentiality and integrity
|       of any data exchanged over the resulting session\.
|     Check results:
|       ANONYMOUS DH GROUP 1
|             Cipher Suite: TLS\_DH\_anon\_WITH\_AES\_256\_CBC\_SHA
|             Modulus Type: Safe prime
|             Modulus Source: Unknown/Custom\-generated
|             Modulus Length: 2048
|             Generator Length: 8
|             Public Key Length: 2048
|     References:
|\_      [https://www.ietf.org/rfc/rfc2246.txt](#https://www.ietf.org/rfc/rfc2246.txt)

|\_ssl\-date: TLS randomness does not represent time
80/tcp  open  http     Apache httpd 2\.4\.18 \(\(Ubuntu\)\)
|\_http\-title: Nagios XI
| http\-fileupload\-exploiter: 
|   
|\_    Couldn't find a file\-type field\.
| vulners: 
|   cpe:/a:apache:http\_server:2\.4\.18: 
|       PACKETSTORM:176334      7\.5     [https://vulners.com/packetstorm/PACKETSTORM:176334*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:176334*EXPLOIT*)

|       PACKETSTORM:171631      7\.5     [https://vulners.com/packetstorm/PACKETSTORM:171631*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:171631*EXPLOIT*)

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

|       CVE\-2017\-3169   7\.5     [https://vulners.com/cve/CVE-2017-3169](#https://vulners.com/cve/CVE-2017-3169)

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
|       EXPLOITPACK:44C5118F831D55FAF4259C41D8BDA0AB    7\.2     [https://vulners.com/exploitpack/EXPLOITPACK:44C5118F831D55FAF4259C41D8BDA0AB](#https://vulners.com/exploitpack/EXPLOITPACK:44C5118F831D55FAF4259C41D8BDA0AB)
\*EXPLOIT\*
|       EDB\-ID:46676    7\.2     [https://vulners.com/exploitdb/EDB-ID:46676](#https://vulners.com/exploitdb/EDB-ID:46676)
\*EXPLOIT\*
|       CVE\-2019\-0211   7\.2     [https://vulners.com/cve/CVE-2019-0211](#https://vulners.com/cve/CVE-2019-0211)

|       1337DAY\-ID\-32502        7\.2     [https://vulners.com/zdt/1337DAY-ID-32502](#https://vulners.com/zdt/1337DAY-ID-32502)
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
|       0095E929\-7573\-5E4A\-A7FA\-F6598A35E8DE    6\.8     [https://vulners.com/githubexploit/0095E929-7573-5E4A-A7FA-F6598A35E8DE](#https://vulners.com/githubexploit/0095E929-7573-5E4A-A7FA-F6598A35E8DE)
\*EXPLOIT\*
|       OSV:BIT\-APACHE\-2022\-28615       6\.4     [https://vulners.com/osv/OSV:BIT-APACHE-2022-28615](#https://vulners.com/osv/OSV:BIT-APACHE-2022-28615)

|       OSV:BIT\-APACHE\-2021\-44224       6\.4     [https://vulners.com/osv/OSV:BIT-APACHE-2021-44224](#https://vulners.com/osv/OSV:BIT-APACHE-2021-44224)

|       OSV:BIT\-2023\-31122      6\.4     [https://vulners.com/osv/OSV:BIT-2023-31122](#https://vulners.com/osv/OSV:BIT-2023-31122)

|       CVE\-2022\-28615  6\.4     [https://vulners.com/cve/CVE-2022-28615](#https://vulners.com/cve/CVE-2022-28615)

|       CVE\-2021\-44224  6\.4     [https://vulners.com/cve/CVE-2021-44224](#https://vulners.com/cve/CVE-2021-44224)

|       CVE\-2019\-10082  6\.4     [https://vulners.com/cve/CVE-2019-10082](#https://vulners.com/cve/CVE-2019-10082)

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
|       EXPLOITPACK:C8C256BE0BFF5FE1C0405CB0AA9C075D    5\.0     [https://vulners.com/exploitpack/EXPLOITPACK:C8C256BE0BFF5FE1C0405CB0AA9C075D](#https://vulners.com/exploitpack/EXPLOITPACK:C8C256BE0BFF5FE1C0405CB0AA9C075D)
\*EXPLOIT\*
|       EXPLOITPACK:2666FB0676B4B582D689921651A30355    5\.0     [https://vulners.com/exploitpack/EXPLOITPACK:2666FB0676B4B582D689921651A30355](#https://vulners.com/exploitpack/EXPLOITPACK:2666FB0676B4B582D689921651A30355)
\*EXPLOIT\*
|       EDB\-ID:42745    5\.0     [https://vulners.com/exploitdb/EDB-ID:42745](#https://vulners.com/exploitdb/EDB-ID:42745)
\*EXPLOIT\*
|       EDB\-ID:40909    5\.0     [https://vulners.com/exploitdb/EDB-ID:40909](#https://vulners.com/exploitdb/EDB-ID:40909)
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

|       CVE\-2021\-33193  5\.0     [https://vulners.com/cve/CVE-2021-33193](#https://vulners.com/cve/CVE-2021-33193)

|       CVE\-2021\-26690  5\.0     [https://vulners.com/cve/CVE-2021-26690](#https://vulners.com/cve/CVE-2021-26690)

|       CVE\-2020\-1934   5\.0     [https://vulners.com/cve/CVE-2020-1934](#https://vulners.com/cve/CVE-2020-1934)

|       CVE\-2019\-17567  5\.0     [https://vulners.com/cve/CVE-2019-17567](#https://vulners.com/cve/CVE-2019-17567)

|       CVE\-2019\-0220   5\.0     [https://vulners.com/cve/CVE-2019-0220](#https://vulners.com/cve/CVE-2019-0220)

|       CVE\-2019\-0196   5\.0     [https://vulners.com/cve/CVE-2019-0196](#https://vulners.com/cve/CVE-2019-0196)

|       CVE\-2018\-17199  5\.0     [https://vulners.com/cve/CVE-2018-17199](#https://vulners.com/cve/CVE-2018-17199)

|       CVE\-2018\-17189  5\.0     [https://vulners.com/cve/CVE-2018-17189](#https://vulners.com/cve/CVE-2018-17189)

|       CVE\-2018\-1333   5\.0     [https://vulners.com/cve/CVE-2018-1333](#https://vulners.com/cve/CVE-2018-1333)

|       CVE\-2018\-1303   5\.0     [https://vulners.com/cve/CVE-2018-1303](#https://vulners.com/cve/CVE-2018-1303)

|       CVE\-2017\-9798   5\.0     [https://vulners.com/cve/CVE-2017-9798](#https://vulners.com/cve/CVE-2017-9798)

|       CVE\-2017\-15710  5\.0     [https://vulners.com/cve/CVE-2017-15710](#https://vulners.com/cve/CVE-2017-15710)

|       CVE\-2016\-8743   5\.0     [https://vulners.com/cve/CVE-2016-8743](#https://vulners.com/cve/CVE-2016-8743)

|       CVE\-2016\-8740   5\.0     [https://vulners.com/cve/CVE-2016-8740](#https://vulners.com/cve/CVE-2016-8740)

|       CVE\-2016\-4979   5\.0     [https://vulners.com/cve/CVE-2016-4979](#https://vulners.com/cve/CVE-2016-4979)

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

|       CVE\-2018\-11763  4\.3     [https://vulners.com/cve/CVE-2018-11763](#https://vulners.com/cve/CVE-2018-11763)

|       CVE\-2016\-4975   4\.3     [https://vulners.com/cve/CVE-2016-4975](#https://vulners.com/cve/CVE-2016-4975)

|       CVE\-2016\-1546   4\.3     [https://vulners.com/cve/CVE-2016-1546](#https://vulners.com/cve/CVE-2016-1546)

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

|\_      PACKETSTORM:152441      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:152441*EXPLOIT*](#https://vulners.com/packetstorm/PACKETSTORM:152441*EXPLOIT*)

| http\-csrf: 
| Spidering limited to: maxdepth=3; maxpagecount=20; withinhost=192\.168\.0\.128
|   Found the following possible CSRF vulnerabilities: 
|     
|     Path: [http://192.168.0.128:80/nagiosxi/login.php?redirect=/nagiosxi/index.php%3F&noauth=1](#http://192.168.0.128:80/nagiosxi/login.php?redirect=/nagiosxi/index.php%3F&noauth=1)

|     Form id: loginform
|     Form action: /nagiosxi/login\.php
|     
|     Path: [http://192.168.0.128:80/nagiosxi/login.php?redirect=/nagiosxi/index.php%3F&noauth=1](#http://192.168.0.128:80/nagiosxi/login.php?redirect=/nagiosxi/index.php%3F&noauth=1)

|     Form id: loginform
|\_    Form action: /nagiosxi/login\.php
|\_http\-vuln\-cve2017\-1001000: ERROR: Script execution failed \(use \-d to debug\)
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
|\_http\-server\-header: Apache/2\.4\.18 \(Ubuntu\)
| http\-slowloris\-check: 
|   VULNERABLE:
|   Slowloris DOS attack
|     State: LIKELY VULNERABLE
|     IDs:  CVE:CVE\-2007\-6750
|       Slowloris tries to keep many connections to the target web server open and hold
|       them open as long as possible\.  It accomplishes this by opening connections to
|       the target web server and sending a partial request\. By doing so, it starves
|       the http server's resources causing Denial Of Service\.
|       
|     Disclosure date: 2009\-09\-17
|     References:
|       [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-6750](#https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-6750)

|\_      [http://ha.ckers.org/slowloris/](#http://ha.ckers.org/slowloris/)

|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
389/tcp open  ldap     OpenLDAP 2\.2\.X \- 2\.3\.X
443/tcp open  ssl/http Apache httpd 2\.4\.18 \(\(Ubuntu\)\)
|\_http\-vuln\-cve2017\-1001000: ERROR: Script execution failed \(use \-d to debug\)
| tls\-alpn: 
|\_  http/1\.1
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
| http\-csrf: 
| Spidering limited to: maxdepth=3; maxpagecount=20; withinhost=192\.168\.0\.128
|   Found the following possible CSRF vulnerabilities: 
|     
|     Path: [https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3F&noauth=1](#https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3F&noauth=1)

|     Form id: loginform
|     Form action: /nagiosxi/login\.php
|     
|     Path: [https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3F&noauth=1](#https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3F&noauth=1)

|     Form id: loginform
|     Form action: /nagiosxi/login\.php
|     
|     Path: [https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dde_DE&noauth=1](#https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dde_DE&noauth=1)

|     Form id: loginform
|     Form action: /nagiosxi/login\.php
|     
|     Path: [https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dpl_PL&noauth=1](#https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dpl_PL&noauth=1)

|     Form id: loginform
|     Form action: /nagiosxi/login\.php
|     
|     Path: [https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dko_KR&noauth=1](#https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dko_KR&noauth=1)

|     Form id: loginform
|     Form action: /nagiosxi/login\.php
|     
|     Path: [https://192.168.0.128:443/nagiosxi/login.php](#https://192.168.0.128:443/nagiosxi/login.php)

|     Form id: loginform
|     Form action: /nagiosxi/login\.php
|     
|     Path: [https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Den_US&noauth=1](#https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Den_US&noauth=1)

|     Form id: loginform
|     Form action: /nagiosxi/login\.php
|     
|     Path: [https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dcs_CZ&noauth=1](#https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dcs_CZ&noauth=1)

|     Form id: loginform
|     Form action: /nagiosxi/login\.php
|     
|     Path: [https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dzh_CN&noauth=1](#https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dzh_CN&noauth=1)

|     Form id: loginform
|     Form action: /nagiosxi/login\.php
|     
|     Path: [https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dbg_BG&noauth=1](#https://192.168.0.128:443/nagiosxi/login.php?redirect=/nagiosxi/index.php%3Flocale%3Dbg_BG&noauth=1)

|     Form id: loginform
|\_    Form action: /nagiosxi/login\.php
|\_http\-title: Nagios XI
| ssl\-cert: Subject: commonName=192\.168\.1\.6/organizationName=Nagios Enterprises/stateOrProvinceName=Minnesota/countryName=US
| Not valid before: 2020\-09\-08T18:28:08
|\_Not valid after:  2030\-09\-06T18:28:08
| http\-slowloris\-check: 
|   VULNERABLE:
|   Slowloris DOS attack
|     State: LIKELY VULNERABLE
|     IDs:  CVE:CVE\-2007\-6750
|       Slowloris tries to keep many connections to the target web server open and hold
|       them open as long as possible\.  It accomplishes this by opening connections to
|       the target web server and sending a partial request\. By doing so, it starves
|       the http server's resources causing Denial Of Service\.
|       
|     Disclosure date: 2009\-09\-17
|     References:
|       [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-6750](#https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-6750)

|\_      [http://ha.ckers.org/slowloris/](#http://ha.ckers.org/slowloris/)

|\_ssl\-date: TLS randomness does not represent time
|\_http\-server\-header: Apache/2\.4\.18 \(Ubuntu\)
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
| http\-fileupload\-exploiter: 
|   
|\_    Couldn't find a file\-type field\.
MAC Address: 00:0C:29:C7:9E:7E \(VMware\)
Service Info: Host:  ubuntu; OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**nmap \-sV \-p\- 192\.168\.0\.128 \-v**
PORT     STATE SERVICE    VERSION
22/tcp   open  ssh        OpenSSH 7\.2p2 Ubuntu 4ubuntu2\.10 \(Ubuntu Linux; protocol 2\.0\)
25/tcp   open  smtp       Postfix smtpd
80/tcp   open  http       Apache httpd 2\.4\.18 \(\(Ubuntu\)\)
389/tcp  open  ldap       OpenLDAP 2\.2\.X \- 2\.3\.X
443/tcp  open  ssl/http   Apache httpd 2\.4\.18 \(\(Ubuntu\)\)
5667/tcp open  tcpwrapped
Service Info: Host:  ubuntu; OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**nikto \-url **[**http://192.168.0.128**](#http://192.168.0.128)
****
\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.0\.128
\+ Target Hostname:    192\.168\.0\.128
\+ Target Port:        80
\+ Start Time:         2024\-02\-05 20:14:41 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: Apache/2\.4\.18 \(Ubuntu\)
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ Apache/2\.4\.18 appears to be outdated \(current is at least Apache/2\.4\.54\)\. Apache 2\.2\.34 is the EOL for the 2\.x branch\.
\+ /: Web Server returns a valid response with junk HTTP methods which may cause false positives\.
\+ /icons/README: Apache default file found\. See: [https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/](#https://www.vntweb.co.uk/apache-restricting-access-to-iconsreadme/)

\+ 8913 requests: 0 error\(s\) and 5 item\(s\) reported on remote host
\+ End Time:           2024\-02\-05 20:14:56 \(GMT\-5\) \(15 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ 1 host\(s\) tested
