**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.0\.172**
PORT     STATE  SERVICE     VERSION
20/tcp   closed ftp\-data
21/tcp   open   ftp         vsftpd 2\.0\.8 or later
| ftp\-anon: Anonymous FTP login allowed \(FTP code 230\)
|\_Can't get directory listing: PASV failed: 550 Permission denied\.
| ftp\-syst: 
|   STAT: 
| FTP server status:
|      Connected to 192\.168\.0\.92
|      Logged in as ftp
|      TYPE: ASCII
|      No session bandwidth limit
|      Session timeout in seconds is 300
|      Control connection is plain text
|      Data connections will be plain text
|      At session startup, client count was 6
|      vsFTPd 3\.0\.3 \- secure, fast, stable
|\_End of status
22/tcp   open   ssh         OpenSSH 7\.2p2 Ubuntu 4 \(Ubuntu Linux; protocol 2\.0\)
| vulners: 
|   cpe:/a:openbsd:openssh:7\.2p2: 
|       PRION:CVE\-2016\-8858     7\.8     [https://vulners.com/prion/PRION:CVE-2016-8858](#https://vulners.com/prion/PRION:CVE-2016-8858)

|       PRION:CVE\-2016\-6515     7\.8     [https://vulners.com/prion/PRION:CVE-2016-6515](#https://vulners.com/prion/PRION:CVE-2016-6515)

|       PACKETSTORM:140070      7\.8     [https://vulners.com/packetstorm/PACKETSTORM:140070](#https://vulners.com/packetstorm/PACKETSTORM:140070)
\*EXPLOIT\*
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

|       PACKETSTORM:173661      7\.5     [https://vulners.com/packetstorm/PACKETSTORM:173661](#https://vulners.com/packetstorm/PACKETSTORM:173661)
\*EXPLOIT\*
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

|       PACKETSTORM:140019      5\.5     [https://vulners.com/packetstorm/PACKETSTORM:140019](#https://vulners.com/packetstorm/PACKETSTORM:140019)
\*EXPLOIT\*
|       PACKETSTORM:136234      5\.5     [https://vulners.com/packetstorm/PACKETSTORM:136234](#https://vulners.com/packetstorm/PACKETSTORM:136234)
\*EXPLOIT\*
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

|       PACKETSTORM:151227      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:151227](#https://vulners.com/packetstorm/PACKETSTORM:151227)
\*EXPLOIT\*
|       PACKETSTORM:140261      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:140261](#https://vulners.com/packetstorm/PACKETSTORM:140261)
\*EXPLOIT\*
|       PACKETSTORM:138006      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:138006](#https://vulners.com/packetstorm/PACKETSTORM:138006)
\*EXPLOIT\*
|       PACKETSTORM:137942      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:137942](#https://vulners.com/packetstorm/PACKETSTORM:137942)
\*EXPLOIT\*
|\_      1337DAY\-ID\-30937        0\.0     [https://vulners.com/zdt/1337DAY-ID-30937](#https://vulners.com/zdt/1337DAY-ID-30937)
\*EXPLOIT\*
| ssh\-hostkey: 
|   2048 8121cea11a05b1694f4ded8028e89905 \(RSA\)
|   256 5ba5bb67911a51c2d321dac0caf0db9e \(ECDSA\)
|\_  256 6d01b773acb0936ffab989e6ae3cabd3 \(ED25519\)
53/tcp   open   domain      dnsmasq 2\.75
| dns\-nsid: 
|   NSID: provnsrrpc01 \(70726f766e73727270633031\)
|   id\.server: provnsrrpc01
|\_  bind\.version: dnsmasq\-2\.75
80/tcp   open   http        PHP cli server 5\.5 or later
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
|\_http\-csrf: Couldn't find any CSRF vulnerabilities\.
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
|       [http://ha.ckers.org/slowloris/](#http://ha.ckers.org/slowloris/)

|\_      [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-6750](#https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-6750)

|\_http\-title: 404 Not Found
|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
139/tcp  open   netbios\-ssn Samba smbd 4\.3\.9\-Ubuntu \(workgroup: WORKGROUP\)
666/tcp  open   doom?
| fingerprint\-strings: 
|   NULL: 
|     message2\.jpgUT 
|     QWux
|     "DL\[E
|     #;3\[
|     \\xf6
|     u\(\[r
|     qYQq
|     Y\_?n2
|     3\&M~\{
|     9\-a\)T
|     L\}AJ
|\_    \.npy\.9
3306/tcp open   mysql       MySQL 5\.7\.12\-0ubuntu1
| mysql\-info: 
|   Protocol: 10
|   Version: 5\.7\.12\-0ubuntu1
|   Thread ID: 14
|   Capabilities flags: 63487
|   Some Capabilities: FoundRows, Speaks41ProtocolOld, Speaks41ProtocolNew, SupportsLoadDataLocal, LongPassword, Support41Auth, SupportsTransactions, IgnoreSigpipes, IgnoreSpaceBeforeParenthesis, DontAllowDatabaseTableColumn, LongColumnFlag, ODBCClient, ConnectWithDatabase, SupportsCompression, InteractiveClient, SupportsMultipleResults, SupportsMultipleStatments, SupportsAuthPlugins
|   Status: Autocommit
|   Salt: 6\\x19S\&QP0\\x13\.YRyMW7\\x15=ZmQ
|\_  Auth Plugin Name: mysql\_native\_password
1 service unrecognized despite returning data\. If you know the service/version, please submit the following fingerprint at [https://nmap.org/cgi-bin/submit.cgi?new-service](#https://nmap.org/cgi-bin/submit.cgi?new-service)
:
SF\-Port666\-TCP:V=7\.93%I=7%D=2/3%Time=65BE8352%P=x86\_64\-pc\-linux\-gnu%r\(NULL
SF:,1000,"PK\\x03\\x04\\x14\\0\\x02\\0\\x08\\0d\\x80\\xc3Hp\\xdf\\x15\\x81\\xaa,\\0\\0\\x15
SF:2\\0\\0\\x0c\\0\\x1c\\0message2\\\.jpgUT\\t\\0\\x03\\\+\\x9cQWJ\\x9cQWux\\x0b\\0\\x01\\x04
SF:\\xf5\\x01\\0\\0\\x04\\x14\\0\\0\\0\\xadz\\x0bT\\x13\\xe7\\xbe\\xefP\\x94\\x88\\x88A@\\xa2
SF:\\x20\\x19\\xabUT\\xc4T\\x11\\xa9\\x102\>\\x8a\\xd4RDK\\x15\\x85Jj\\xa9\\"DL\\\[E\\xa2\\x
SF:0c\\x19\\x140\<\\xc4\\xb4\\xb5\\xca\\xaen\\x89\\x8a\\x8aV\\x11\\x91W\\xc5H\\x20\\x0f\\xb
SF:2\\xf7\\xb6\\x88\\n\\x82@%\\x99d\\xb7\\xc8#;3\\\[\\r\_\\xcddr\\x87\\xbd\\xcf9\\xf7\\xaeu\\
SF:xeeY\\xeb\\xdc\\xb3oX\\xacY\\xf92\\xf3e\\xfe\\xdf\\xff\\xff\\xff=2\\x9f\\xf3\\x99\\xd3
SF:\\x08y\}\\xb8a\\xe3\\x06\\xc8\\xc5\\x05\\x82\>\`\\xfe\\x20\\xa7\\x05:\\xb4y\\xaf\\xf8\\xa0
SF:\\xf8\\xc0\\^\\xf1\\x97sC\\x97\\xbd\\x0b\\xbd\\xb7nc\\xdc\\xa4I\\xd0\\xc4\\\+j\\xce\\\[\\x8
SF:7\\xa0\\xe5\\x1b\\xf7\\xcc=,\\xce\\x9a\\xbb\\xeb\\xeb\\xdds\\xbf\\xde\\xbd\\xeb\\x8b\\xf
SF:4\\xfdis\\x0f\\xeeM\\?\\xb0\\xf4\\x1f\\xa3\\xcceY\\xfb\\xbe\\x98\\x9b\\xb6\\xfb\\xe0\\xd
SF:c\\\]sS\\xc5bQ\\xfa\\xee\\xb7\\xe7\\xbc\\x05AoA\\x93\\xfe9\\xd3\\x82\\x7f\\xcc\\xe4\\xd5
SF:\\x1dx\\xa2O\\x0e\\xdd\\x994\\x9c\\xe7\\xfe\\x871\\xb0N\\xea\\x1c\\x80\\xd63w\\xf1\\xaf
SF:\\xbd\&\&q\\xf9\\x97'i\\x85fL\\x81\\xe2\\\\\\xf6\\xb9\\xba\\xcc\\x80\\xde\\x9a\\xe1\\xe2:\\
SF:xc3\\xc5\\xa9\\x85\`\\x08r\\x99\\xfc\\xcf\\x13\\xa0\\x7f\{\\xb9\\xbc\\xe5:i\\xb2\\x1bk\\x
SF:8a\\xfbT\\x0f\\xe6\\x84\\x06/\\xe8\-\\x17W\\xd7\\xb7\&\\xb9N\\x9e\<\\xb1\\\\\\\.\\xb9\\xcc\\x
SF:e7\\xd0\\xa4\\x19\\x93\\xbd\\xdf\\^\\xbe\\xd6\\xcdg\\xcb\\\.\\xd6\\xbc\\xaf\\|W\\x1c\\xfd\\
SF:xf6\\xe2\\x94\\xf9\\xebj\\xdbf~\\xfc\\x98x'\\xf4\\xf3\\xaf\\x8f\\xb9O\\xf5\\xe3\\xcc\\x
SF:9a\\xed\\xbf\`a\\xd0\\xa2\\xc5KV\\x86\\xad\\n\\x7fou\\xc4\\xfa\\xf7\\xa37\\xc4\\|\\xb0\\x
SF:f1\\xc3\\x84O\\xb6nK\\xdc\\xbe#\\\)\\xf5\\x8b\\xdd\{\\xd2\\xf6\\xa6g\\x1c8\\x98u\\\(\\\[r\\x
SF:f8H~A\\xe1qYQq\\xc9w\\xa7\\xbe\\?\}\\xa6\\xfc\\x0f\\?\\x9c\\xbdTy\\xf9\\xca\\xd5\\xaak\\
SF:xd7\\x7f\\xbcSW\\xdf\\xd0\\xd8\\xf4\\xd3\\xddf\\xb5F\\xabk\\xd7\\xff\\xe9\\xcf\\x7fy\\x
SF:d2\\xd5\\xfd\\xb4\\xa7\\xf7Y\_\\?n2\\xff\\xf5\\xd7\\xdf\\x86\\^\\x0c\\x8f\\x90\\x7f\\x7f\\
SF:xf9\\xea\\xb5m\\x1c\\xfc\\xfef\\"\\\.\\x17\\xc8\\xf5\\?B\\xff\\xbf\\xc6\\xc5,\\x82\\xcb\\\[
SF:\\x93\&\\xb9NbM\\xc4\\xe5\\xf2V\\xf6\\xc4\\t3\&M~\{\\xb9\\x9b\\xf7\\xda\-\\xac\\\]\_\\xf9\\xc
SF:c\\\[qt\\x8a\\xef\\xbao/\\xd6\\xb6\\xb9\\xcf\\x0f\\xfd\\x98\\x98\\xf9\\xf9\\xd7\\x8f\\xa7
SF:\\xfa\\xbd\\xb3\\x12\_@N\\x84\\xf6\\x8f\\xc8\\xfe\{\\x81\\x1d\\xfb\\x1fE\\xf6\\x1f\\x81\\x
SF:fd\\xef\\xb8\\xfa\\xa1i\\xae\\\.L\\xf2\\\\g@\\x08D\\xbb\\xbfp\\xb5\\xd4\\xf4Ym\\x0bI\\x96
SF:\\x1e\\xcb\\x879\-a\\\)T\\x02\\xc8\\$\\x14k\\x08\\xae\\xfcZ\\x90\\xe6E\\xcb\<C\\xcap\\x8f\\
SF:xd0\\x8f\\x9fu\\x01\\x8dvT\\xf0'\\x9b\\xe4ST%\\x9f5\\x95\\xab\\rSWb\\xecN\\xfb\&\\xf4\\
SF:xed\\xe3v\\x13O\\xb73A#\\xf0,\\xd5\\xc2\\^\\xe8\\xfc\\xc0\\xa7\\xaf\\xab4\\xcfC\\xcd\\x
SF:88\\x8e\}\\xac\\x15\\xf6~\\xc4R\\x8e\`wT\\x96\\xa8KT\\x1cam\\xdb\\x99f\\xfb\\n\\xbc\\xbc
SF:L\}AJ\\xe5H\\x912\\x88\\\(O\\0k\\xc9\\xa9\\x1a\\x93\\xb8\\x84\\x8fdN\\xbf\\x17\\xf5\\xf0\\
SF:\.npy\\\.9\\x04\\xcf\\x14\\x1d\\x89Rr9\\xe4\\xd2\\xae\\x91#\\xfbOg\\xed\\xf6\\x15\\x04\\x
SF:f6~\\xf1\\\]V\\xdcBGu\\xeb\\xaa=\\x8e\\xef\\xa4HU\\x1e\\x8f\\x9f\\x9bI\\xf4\\xb6GTQ\\xf
SF:3\\xe9\\xe5\\x8e\\x0b\\x14L\\xb2\\xda\\x92\\x12\\xf3\\x95\\xa2\\x1c\\xb3\\x13\\\*P\\x11\\?
SF:\\xfb\\xf3\\xda\\xcaDfv\\x89\`\\xa9\\xe4k\\xc4S\\x0e\\xd6P0"\);
MAC Address: 08:00:27:18:56:B3 \(Oracle VirtualBox virtual NIC\)
Service Info: Host: RED; OS: Linux; CPE: cpe:/o:linux:linux\_kernel

Host script results:
| smb\-os\-discovery: 
|   OS: Windows 6\.1 \(Samba 4\.3\.9\-Ubuntu\)
|   Computer name: red
|   NetBIOS computer name: RED\\x00
|   Domain name: \\x00
|   FQDN: red
|\_  System time: 2024\-02\-03T13:18:06\+00:00
| smb\-security\-mode: 
|   account\_used: guest
|   authentication\_level: user
|   challenge\_response: supported
|\_  message\_signing: disabled \(dangerous, but default\)
|\_smb\-vuln\-ms10\-054: false
|\_smb\-vuln\-ms10\-061: false
|\_nbstat: NetBIOS name: RED, NetBIOS user: \<unknown\>, NetBIOS MAC: 000000000000 \(Xerox\)
| smb\-vuln\-cve2009\-3103: 
|   VULNERABLE:
|   SMBv2 exploit \(CVE\-2009\-3103, Microsoft Security Advisory 975497\)
|     State: VULNERABLE
|     IDs:  CVE:CVE\-2009\-3103
|           Array index error in the SMBv2 protocol implementation in srv2\.sys in Microsoft Windows Vista Gold, SP1, and SP2,
|           Windows Server 2008 Gold and SP2, and Windows 7 RC allows remote attackers to execute arbitrary code or cause a
|           denial of service \(system crash\) via an \& \(ampersand\) character in a Process ID High header field in a NEGOTIATE
|           PROTOCOL REQUEST packet, which triggers an attempted dereference of an out\-of\-bounds memory location,
|           aka "SMBv2 Negotiation Vulnerability\."
|           
|     Disclosure date: 2009\-09\-08
|     References:
|       [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-3103](#https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-3103)

|\_      [http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-3103](#http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-3103)

|\_clock\-skew: mean: \-5h00m00s, deviation: 1s, median: \-5h00m01s
| smb2\-security\-mode: 
|   311: 
|\_    Message signing enabled but not required
| smb2\-time: 
|   date: 2024\-02\-03T13:18:06
|\_  start\_date: N/A
| smb\-vuln\-regsvc\-dos: 
|   VULNERABLE:
|   Service regsvc in Microsoft Windows systems vulnerable to denial of service
|     State: VULNERABLE
|       The service regsvc in Microsoft Windows 2000 systems is vulnerable to denial of service caused by a null deference
|       pointer\. This script will crash the service if it is vulnerable\. This vulnerability was discovered by Ron Bowes
|       while working on smb\-enum\-sessions\.
|\_          


**
nmap \-sV \-p\- 192\.168\.0\.172 \-v**
PORT      STATE  SERVICE     VERSION
20/tcp    closed ftp\-data
21/tcp    open   ftp         vsftpd 2\.0\.8 or later
22/tcp    open   ssh         OpenSSH 7\.2p2 Ubuntu 4 \(Ubuntu Linux; protocol 2\.0\)
53/tcp    open   domain      dnsmasq 2\.75
80/tcp    open   http        PHP cli server 5\.5 or later
123/tcp   closed ntp
137/tcp   closed netbios\-ns
138/tcp   closed netbios\-dgm
139/tcp   open   netbios\-ssn Samba smbd 3\.X \- 4\.X \(workgroup: WORKGROUP\)
666/tcp   open   doom?
3306/tcp  open   mysql       MySQL 5\.7\.12\-0ubuntu1
12380/tcp open   http        Apache httpd 2\.4\.18 \(\(Ubuntu\)\)


**nikto \-url **[**http://192.168.0.172**](#http://192.168.0.172)
****
\- Nikto v2\.5\.0
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Target IP:          192\.168\.0\.172
\+ Target Hostname:    192\.168\.0\.172
\+ Target Port:        80
\+ Start Time:         2024\-02\-03 13:30:55 \(GMT\-5\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
\+ Server: No banner retrieved
\+ /: The anti\-clickjacking X\-Frame\-Options header is not present\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)

\+ /: The X\-Content\-Type\-Options header is not set\. This could allow the user agent to render the content of the site in a different fashion to the MIME type\. See: [https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/](#https://www.netsparker.com/web-vulnerability-scanner/vulnerabilities/missing-content-type-header/)

\+ No CGI Directories found \(use '\-C all' to force check all possible dirs\)
\+ /\.bashrc: User home dir was found with a shell rc file\. This may reveal file and path information\.
\+ /\.profile: User home dir with a shell profile was found\. May reveal directory information and system configuration\.
\+ 8110 requests: 9 error\(s\) and 4 item\(s\) reported on remote host
\+ End Time:           2024\-02\-03 13:31:52 \(GMT\-5\) \(57 seconds\)
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
