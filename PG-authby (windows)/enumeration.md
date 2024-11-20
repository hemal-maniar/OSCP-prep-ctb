**sudo nmap \-sS \-sV \-\-script=default 192\.168\.199\.46**
PORT     STATE SERVICE            VERSION
21/tcp   open  ftp                zFTPServer 6\.0 build 2011\-10\-17
| ftp\-anon: Anonymous FTP login allowed \(FTP code 230\)
| total 9680
| \-\-\-\-\-\-\-\-\-\-   1 root     root      5610496 Oct 18  2011 zFTPServer\.exe
| \-\-\-\-\-\-\-\-\-\-   1 root     root           25 Feb 10  2011 UninstallService\.bat
| \-\-\-\-\-\-\-\-\-\-   1 root     root      4284928 Oct 18  2011 Uninstall\.exe
| \-\-\-\-\-\-\-\-\-\-   1 root     root           17 Aug 13  2011 StopService\.bat
| \-\-\-\-\-\-\-\-\-\-   1 root     root           18 Aug 13  2011 StartService\.bat
| \-\-\-\-\-\-\-\-\-\-   1 root     root         8736 Nov 09  2011 Settings\.ini
| dr\-xr\-xr\-x   1 root     root          512 Mar 28 23:22 log
| \-\-\-\-\-\-\-\-\-\-   1 root     root         2275 Aug 08  2011 LICENSE\.htm
| \-\-\-\-\-\-\-\-\-\-   1 root     root           23 Feb 10  2011 InstallService\.bat
| dr\-xr\-xr\-x   1 root     root          512 Nov 08  2011 extensions
| dr\-xr\-xr\-x   1 root     root          512 Nov 08  2011 certificates
|\_dr\-xr\-xr\-x   1 root     root          512 Jan 23  2023 accounts
3389/tcp open  ssl/ms\-wbt\-server?
|\_ssl\-date: 2024\-03\-28T16:23:17\+00:00; \+1s from scanner time\.
| rdp\-ntlm\-info: 
|   Target\_Name: LIVDA
|   NetBIOS\_Domain\_Name: LIVDA
|   NetBIOS\_Computer\_Name: LIVDA
|   DNS\_Domain\_Name: LIVDA
|   DNS\_Computer\_Name: LIVDA
|   Product\_Version: 6\.0\.6001
|\_  System\_Time: 2024\-03\-28T16:23:12\+00:00
| ssl\-cert: Subject: commonName=LIVDA
| Not valid before: 2023\-01\-22T09:37:27
|\_Not valid after:  2023\-07\-24T09:37:27
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

**nmap \-sV \-Pn \-p\- \-v 192\.168\.199\.46**
PORT     STATE SERVICE            VERSION
21/tcp   open  ftp                zFTPServer 6\.0 build 2011\-10\-17
242/tcp  open  http               Apache httpd 2\.2\.21 \(\(Win32\) PHP/5\.3\.8\)
3145/tcp open  zftp\-admin         zFTPServer admin
3389/tcp open  ssl/ms\-wbt\-server?
