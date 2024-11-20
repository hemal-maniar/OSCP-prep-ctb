**sudo nmap \-sS \-sV \-\-script=default 192\.168\.207\.65
**PORT     STATE SERVICE       VERSION
21/tcp   open  ftp           Microsoft ftpd
| ftp\-anon: Anonymous FTP login allowed \(FTP code 230\)
| 04\-29\-20  10:31PM       \<DIR\>          ImapRetrieval
| 07\-11\-22  09:08AM       \<DIR\>          Logs
| 04\-29\-20  10:31PM       \<DIR\>          PopRetrieval
|\_04\-29\-20  10:32PM       \<DIR\>          Spool
| ftp\-syst: 
|\_  SYST: Windows\_NT
80/tcp   open  http          Microsoft IIS httpd 10\.0
| http\-methods: 
|\_  Potentially risky methods: TRACE
|\_http\-title: IIS Windows
|\_http\-server\-header: Microsoft\-IIS/10\.0
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios\-ssn   Microsoft Windows netbios\-ssn
445/tcp  open  microsoft\-ds?
9998/tcp open  http          Microsoft IIS httpd 10\.0
| uptime\-agent\-info: HTTP/1\.1 400 Bad Request\\x0D
| Content\-Type: text/html; charset=us\-ascii\\x0D
| Server: Microsoft\-HTTPAPI/2\.0\\x0D
| Date: Fri, 22 Mar 2024 00:36:13 GMT\\x0D
| Connection: close\\x0D
| Content\-Length: 326\\x0D
| \\x0D
| \<\!DOCTYPE HTML PUBLIC "\-//W3C//DTD HTML 4\.01//EN""[http://www.w3.org/TR/html4/strict.dtd](#http://www.w3.org/TR/html4/strict.dtd)
"\>\\x0D
| \<HTML\>\<HEAD\>\<TITLE\>Bad Request\</TITLE\>\\x0D
| \<META HTTP\-EQUIV="Content\-Type" Content="text/html; charset=us\-ascii"\>\</HEAD\>\\x0D
| \<BODY\>\<h2\>Bad Request \- Invalid Verb\</h2\>\\x0D
| \<hr\>\<p\>HTTP Error 400\. The request verb is invalid\.\</p\>\\x0D
|\_\</BODY\>\</HTML\>\\x0D
|\_http\-server\-header: Microsoft\-IIS/10\.0
| http\-title: Site doesn't have a title \(text/html; charset=utf\-8\)\.
|\_Requested resource was /interface/root
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2\-time: 
|   date: 2024\-03\-22T00:36:17
|\_  start\_date: N/A
| smb2\-security\-mode: 
|   3:1:1: 
|\_    Message signing enabled but not required
**
nmap \-sV \-p\- 192\.168\.207\.65 \-v **
PORT      STATE SERVICE       VERSION
21/tcp    open  ftp           Microsoft ftpd
80/tcp    open  http          Microsoft IIS httpd 10\.0
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios\-ssn   Microsoft Windows netbios\-ssn
445/tcp   open  microsoft\-ds?
5040/tcp  open  unknown
9998/tcp  open  http          Microsoft IIS httpd 10\.0
17001/tcp open  remoting      MS \.NET Remoting services
49664/tcp open  msrpc     	   Microsoft Windows RPC
49665/tcp open  msrpc         Microsoft Windows RPC
49666/tcp open  msrpc         Microsoft Windows RPC
49667/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49669/tcp open  msrpc         Microsoft Windows RPC

