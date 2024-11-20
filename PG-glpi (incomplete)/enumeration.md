**sudo nmap \-sS \-sV \-\-script=default 192\.168\.196\.242
**PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.5 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 98:4e:5d:e1:e6:97:29:6f:d9:e0:d4:82:a8:f6:4f:3f \(RSA\)
|   256 57:23:57:1f:fd:77:06:be:25:66:61:14:6d:ae:5e:98 \(ECDSA\)
|\_  256 c7:9b:aa:d5:a6:33:35:91:34:1e:ef:cf:61:a8:30:1c \(ED25519\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
|\_http\-server\-header: Apache/2\.4\.41 \(Ubuntu\)
|\_http\-title: Authentication \- GLPI
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**nmap \-sV \-p\- 192\.168\.196\.242 \-v
**PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.5 \(Ubuntu Linux; protocol 2\.0\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

/index\.php            \(Status: 200\) \[Size: 9017\]
/templates            \(Status: 301\) \[Size: 322\] \[\-\-\> [http://192.168.196.242/templates/\]](#http://192.168.196.242/templates/])

/files                \(Status: 301\) \[Size: 318\] \[\-\-\> [http://192.168.196.242/files/\]](#http://192.168.196.242/files/])

/pics                 \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.196.242/pics/\]](#http://192.168.196.242/pics/])

/public               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.242/public/\]](#http://192.168.196.242/public/])

/bin                  \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.196.242/bin/\]](#http://192.168.196.242/bin/])

/plugins              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.242/plugins/\]](#http://192.168.196.242/plugins/])

/css                  \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.196.242/css/\]](#http://192.168.196.242/css/])

/ajax                 \(Status: 301\) \[Size: 317\] \[\-\-\> [http://192.168.196.242/ajax/\]](#http://192.168.196.242/ajax/])

/install              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.242/install/\]](#http://192.168.196.242/install/])

/lib                  \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.196.242/lib/\]](#http://192.168.196.242/lib/])

/status\.php           \(Status: 200\) \[Size: 115\]
/src                  \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.196.242/src/\]](#http://192.168.196.242/src/])

/front                \(Status: 301\) \[Size: 318\] \[\-\-\> [http://192.168.196.242/front/\]](#http://192.168.196.242/front/])

/js                   \(Status: 301\) \[Size: 315\] \[\-\-\> [http://192.168.196.242/js/\]](#http://192.168.196.242/js/])

/marketplace          \(Status: 301\) \[Size: 324\] \[\-\-\> [http://192.168.196.242/marketplace/\]](#http://192.168.196.242/marketplace/])

/vendor               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.242/vendor/\]](#http://192.168.196.242/vendor/])

/config               \(Status: 301\) \[Size: 319\] \[\-\-\> [http://192.168.196.242/config/\]](#http://192.168.196.242/config/])

/inc                  \(Status: 301\) \[Size: 316\] \[\-\-\> [http://192.168.196.242/inc/\]](#http://192.168.196.242/inc/])

/sound                \(Status: 301\) \[Size: 318\] \[\-\-\> [http://192.168.196.242/sound/\]](#http://192.168.196.242/sound/])

/LICENSE              \(Status: 200\) \[Size: 35148\]
/locales              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.196.242/locales/\]](#http://192.168.196.242/locales/])

/phpinfo\.php          \(Status: 200\) \[Size: 79458\]
/caldav\.php           \(Status: 401\) \[Size: 354\]
