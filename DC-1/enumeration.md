**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.0\.119
**
Nmap scan report for 192\.168\.0\.119
Host is up \(0\.00039s latency\)\.
Not shown: 997 closed tcp ports \(reset\)
PORT    STATE SERVICE VERSION
22/tcp  open  ssh     OpenSSH 6\.0p1 Debian 4\+deb7u7 \(protocol 2\.0\)
| vulners: 
|   cpe:/a:openbsd:openssh:6\.0p1: 
|       PRION:CVE\-2015\-5600     8\.5     [https://vulners.com/prion/PRION:CVE-2015-5600](#https://vulners.com/prion/PRION:CVE-2015-5600)

|       CVE\-2015\-5600   8\.5     [https://vulners.com/cve/CVE-2015-5600](#https://vulners.com/cve/CVE-2015-5600)

|       SSV:92672       7\.8     [https://vulners.com/seebug/SSV:92672](#https://vulners.com/seebug/SSV:92672)
\*EXPLOIT\*
|       PRION:CVE\-2017\-5850     7\.8     [https://vulners.com/prion/PRION:CVE-2017-5850](#https://vulners.com/prion/PRION:CVE-2017-5850)

|       EDB\-ID:41278    7\.8     [https://vulners.com/exploitdb/EDB-ID:41278](#https://vulners.com/exploitdb/EDB-ID:41278)
\*EXPLOIT\*
|       1337DAY\-ID\-26918        7\.8     [https://vulners.com/zdt/1337DAY-ID-26918](#https://vulners.com/zdt/1337DAY-ID-26918)
\*EXPLOIT\*
|       SSV:61450       7\.5     [https://vulners.com/seebug/SSV:61450](#https://vulners.com/seebug/SSV:61450)
\*EXPLOIT\*
|       PRION:CVE\-2020\-16088    7\.5     [https://vulners.com/prion/PRION:CVE-2020-16088](#https://vulners.com/prion/PRION:CVE-2020-16088)

|       PRION:CVE\-2017\-1000372  7\.5     [https://vulners.com/prion/PRION:CVE-2017-1000372](#https://vulners.com/prion/PRION:CVE-2017-1000372)

|       PRION:CVE\-2014\-1692     7\.5     [https://vulners.com/prion/PRION:CVE-2014-1692](#https://vulners.com/prion/PRION:CVE-2014-1692)

|       EDB\-ID:42271    7\.5     [https://vulners.com/exploitdb/EDB-ID:42271](#https://vulners.com/exploitdb/EDB-ID:42271)
\*EXPLOIT\*
|       CVE\-2014\-1692   7\.5     [https://vulners.com/cve/CVE-2014-1692](#https://vulners.com/cve/CVE-2014-1692)

|       PRION:CVE\-2019\-19726    7\.2     [https://vulners.com/prion/PRION:CVE-2019-19726](#https://vulners.com/prion/PRION:CVE-2019-19726)

|       MSF:EXPLOIT\-OPENBSD\-LOCAL\-DYNAMIC\_LOADER\_CHPASS\_PRIVESC\-        7\.2     [https://vulners.com/metasploit/MSF:EXPLOIT-OPENBSD-LOCAL-DYNAMIC_LOADER_CHPASS_PRIVESC-](#https://vulners.com/metasploit/MSF:EXPLOIT-OPENBSD-LOCAL-DYNAMIC_LOADER_CHPASS_PRIVESC-)
\*EXPLOIT\*
|       EDB\-ID:47803    7\.2     [https://vulners.com/exploitdb/EDB-ID:47803](#https://vulners.com/exploitdb/EDB-ID:47803)
\*EXPLOIT\*
|       EDB\-ID:47780    7\.2     [https://vulners.com/exploitdb/EDB-ID:47780](#https://vulners.com/exploitdb/EDB-ID:47780)
\*EXPLOIT\*
|       1337DAY\-ID\-39095        7\.2     [https://vulners.com/zdt/1337DAY-ID-39095](#https://vulners.com/zdt/1337DAY-ID-39095)
\*EXPLOIT\*
|       PRION:CVE\-2015\-6564     6\.9     [https://vulners.com/prion/PRION:CVE-2015-6564](#https://vulners.com/prion/PRION:CVE-2015-6564)

|       CVE\-2015\-6564   6\.9     [https://vulners.com/cve/CVE-2015-6564](#https://vulners.com/cve/CVE-2015-6564)

|       PRION:CVE\-2017\-1000373  6\.4     [https://vulners.com/prion/PRION:CVE-2017-1000373](#https://vulners.com/prion/PRION:CVE-2017-1000373)

|       SSV:61911       5\.8     [https://vulners.com/seebug/SSV:61911](#https://vulners.com/seebug/SSV:61911)
\*EXPLOIT\*
|       PRION:CVE\-2014\-2653     5\.8     [https://vulners.com/prion/PRION:CVE-2014-2653](#https://vulners.com/prion/PRION:CVE-2014-2653)

|       PRION:CVE\-2014\-2532     5\.8     [https://vulners.com/prion/PRION:CVE-2014-2532](#https://vulners.com/prion/PRION:CVE-2014-2532)

|       CVE\-2014\-2653   5\.8     [https://vulners.com/cve/CVE-2014-2653](#https://vulners.com/cve/CVE-2014-2653)

|       CVE\-2014\-2532   5\.8     [https://vulners.com/cve/CVE-2014-2532](#https://vulners.com/cve/CVE-2014-2532)

|       SSV:60656       5\.0     [https://vulners.com/seebug/SSV:60656](#https://vulners.com/seebug/SSV:60656)
\*EXPLOIT\*
|       PRION:CVE\-2019\-8460     5\.0     [https://vulners.com/prion/PRION:CVE-2019-8460](#https://vulners.com/prion/PRION:CVE-2019-8460)

|       PRION:CVE\-2010\-5107     5\.0     [https://vulners.com/prion/PRION:CVE-2010-5107](#https://vulners.com/prion/PRION:CVE-2010-5107)

|       CVE\-2018\-15919  5\.0     [https://vulners.com/cve/CVE-2018-15919](#https://vulners.com/cve/CVE-2018-15919)

|       CVE\-2010\-5107   5\.0     [https://vulners.com/cve/CVE-2010-5107](#https://vulners.com/cve/CVE-2010-5107)

|       SSV:90447       4\.6     [https://vulners.com/seebug/SSV:90447](#https://vulners.com/seebug/SSV:90447)
\*EXPLOIT\*
|       PRION:CVE\-2016\-0778     4\.6     [https://vulners.com/prion/PRION:CVE-2016-0778](#https://vulners.com/prion/PRION:CVE-2016-0778)

|       CVE\-2016\-0778   4\.6     [https://vulners.com/cve/CVE-2016-0778](#https://vulners.com/cve/CVE-2016-0778)

|       PRION:CVE\-2015\-5352     4\.3     [https://vulners.com/prion/PRION:CVE-2015-5352](#https://vulners.com/prion/PRION:CVE-2015-5352)

|       CVE\-2020\-14145  4\.3     [https://vulners.com/cve/CVE-2020-14145](#https://vulners.com/cve/CVE-2020-14145)

|       CVE\-2015\-5352   4\.3     [https://vulners.com/cve/CVE-2015-5352](#https://vulners.com/cve/CVE-2015-5352)

|       PRION:CVE\-2016\-0777     4\.0     [https://vulners.com/prion/PRION:CVE-2016-0777](#https://vulners.com/prion/PRION:CVE-2016-0777)

|       CVE\-2016\-0777   4\.0     [https://vulners.com/cve/CVE-2016-0777](#https://vulners.com/cve/CVE-2016-0777)

|       PRION:CVE\-2015\-6563     1\.9     [https://vulners.com/prion/PRION:CVE-2015-6563](#https://vulners.com/prion/PRION:CVE-2015-6563)

|       CVE\-2015\-6563   1\.9     [https://vulners.com/cve/CVE-2015-6563](#https://vulners.com/cve/CVE-2015-6563)

|\_      PACKETSTORM:140944      0\.0     [https://vulners.com/packetstorm/PACKETSTORM:140944](#https://vulners.com/packetstorm/PACKETSTORM:140944)
\*EXPLOIT\*
| ssh\-hostkey: 
|   1024 c4d659e6774c227a961660678b42488f \(DSA\)
|   2048 1182fe534edc5b327f446482757dd0a0 \(RSA\)
|\_  256 3daa985c87afea84b823688db9055fd8 \(ECDSA\)
80/tcp  open  http    Apache httpd 2\.2\.22 \(\(Debian\)\)
| http\-csrf: 
| Spidering limited to: maxdepth=3; maxpagecount=20; withinhost=192\.168\.0\.119
|   Found the following possible CSRF vulnerabilities: 
|     
|     Path: [http://192.168.0.119:80/](#http://192.168.0.119:80/)

|     Form id: user\-login\-form
|     Form action: /node?destination=node
|     
|     Path: [http://192.168.0.119:80/user/password](#http://192.168.0.119:80/user/password)

|     Form id: user\-pass
|     Form action: /user/password
|     
|     Path: [http://192.168.0.119:80/user/register](#http://192.168.0.119:80/user/register)

|     Form id: user\-register\-form
|     Form action: /user/register
|     
|     Path: [http://192.168.0.119:80/node?destination=node](#http://192.168.0.119:80/node?destination=node)

|     Form id: user\-login\-form
|     Form action: /node?destination=node
|     
|     Path: [http://192.168.0.119:80/user](#http://192.168.0.119:80/user)

|     Form id: user\-login
|     Form action: /user
|     
|     Path: [http://192.168.0.119:80/user/](#http://192.168.0.119:80/user/)

|     Form id: user\-login
|\_    Form action: /user/
| http\-enum: 
|   /rss\.xml: RSS or Atom feed
|   /robots\.txt: Robots file
|   /UPGRADE\.txt: Drupal file
|   /INSTALL\.txt: Drupal file
|   /INSTALL\.mysql\.txt: Drupal file
|   /INSTALL\.pgsql\.txt: Drupal file
|   /: Drupal version 7 
|   /README: Interesting, a readme\.
|   /README\.txt: Interesting, a readme\.
|   /0/: Potentially interesting folder
|\_  /user/: Potentially interesting folder
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
| http\-vuln\-cve2014\-3704: 
|   VULNERABLE:
|   Drupal \- pre Auth SQL Injection Vulnerability
|     State: VULNERABLE \(Exploitable\)
|     IDs:  CVE:CVE\-2014\-3704
|         The expandArguments function in the database abstraction API in
|         Drupal core 7\.x before 7\.32 does not properly construct prepared
|         statements, which allows remote attackers to conduct SQL injection
|         attacks via an array containing crafted keys\.
|           
|     Disclosure date: 2014\-10\-15
|     References:
|       [https://www.sektioneins.de/en/advisories/advisory-012014-drupal-pre-auth-sql-injection-vulnerability.html](#https://www.sektioneins.de/en/advisories/advisory-012014-drupal-pre-auth-sql-injection-vulnerability.html)

|       [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2014-3704](#https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2014-3704)

|       [http://www.securityfocus.com/bid/70595](#http://www.securityfocus.com/bid/70595)

|\_      [https://www.drupal.org/SA-CORE-2014-005](#https://www.drupal.org/SA-CORE-2014-005)

|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
|\_http\-server\-header: Apache/2\.2\.22 \(Debian\)
|\_http\-generator: Drupal 7 \([http://drupal.org](#http://drupal.org)
\)
|\_http\-title: Welcome to Drupal Site | Drupal Site
| vulners: 
|   cpe:/a:apache:http\_server:2\.2\.22: 
|       SSV:60905       4\.3     [https://vulners.com/seebug/SSV:60905](#https://vulners.com/seebug/SSV:60905)
\*EXPLOIT\*
|\_      CVE\-2013\-1896   4\.3     [https://vulners.com/cve/CVE-2013-1896](#https://vulners.com/cve/CVE-2013-1896)

| http\-robots\.txt: 36 disallowed entries \(15 shown\)
| /includes/ /misc/ /modules/ /profiles/ /scripts/ 
| /themes/ /CHANGELOG\.txt /cron\.php /INSTALL\.mysql\.txt 
| /INSTALL\.pgsql\.txt /INSTALL\.sqlite\.txt /install\.php /INSTALL\.txt 
|\_/LICENSE\.txt /MAINTAINERS\.txt
111/tcp open  rpcbind 2\-4 \(RPC #100000\)
| rpcinfo: 
|   program version    port/proto  service
|   100000  2,3,4        111/tcp   rpcbind
|   100000  2,3,4        111/udp   rpcbind
|   100000  3,4          111/tcp6  rpcbind
|   100000  3,4          111/udp6  rpcbind
|   100024  1          39086/udp   status
|   100024  1          42728/udp6  status
|   100024  1          53474/tcp   status
|\_  100024  1          54239/tcp6  status
MAC Address: 00:0C:29:B4:7B:60 \(VMware\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

Service detection performed\. Please report any incorrect results at [https://nmap.org/submit/](#https://nmap.org/submit/)
\.
Nmap done: 1 IP address \(1 host up\) scanned in 190\.83 seconds