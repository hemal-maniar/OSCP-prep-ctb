-  went to robot\.txt
User\-agent: \*
Disallow: /textpattern/textpattern

dont forget to add \.zip extension to your dir\-brute
;\)

-  added \.zip to dir\-brute

**gobuster dir \-u **[**http://192.168.0.30**](#http://192.168.0.30)
**\-w /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt \-t 100 \-x zip**
===============================================================
Gobuster v3\.6
by OJ Reeves \(@TheColonial\) \& Christian Mehlmauer \(@firefart\)
===============================================================
\[\+\] Url:                     [http://192.168.0.30](#http://192.168.0.30)

\[\+\] Method:                  GET
\[\+\] Threads:                 100
\[\+\] Wordlist:                /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt
\[\+\] Negative Status codes:   404
\[\+\] User Agent:              gobuster/3\.6
\[\+\] Extensions:              zip
\[\+\] Timeout:                 10s
===============================================================
Starting gobuster in directory enumeration mode
===============================================================
/index                \(Status: 200\) \[Size: 750\]
/db                   \(Status: 200\) \[Size: 53656\]
/robots               \(Status: 200\) \[Size: 110\]
/spammer              \(Status: 200\) \[Size: 179\]
/spammer\.zip          \(Status: 200\) \[Size: 179\]
/server\-status        \(Status: 403\) \[Size: 293\]
