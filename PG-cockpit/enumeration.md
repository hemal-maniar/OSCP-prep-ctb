**sudo nmap \-sS \-sV \-\-script=default 192\.168\.246\.10
**PORT     STATE SERVICE         VERSION
22/tcp   open  ssh             OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.5 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 98:4e:5d:e1:e6:97:29:6f:d9:e0:d4:82:a8:f6:4f:3f \(RSA\)
|   256 57:23:57:1f:fd:77:06:be:25:66:61:14:6d:ae:5e:98 \(ECDSA\)
|\_  256 c7:9b:aa:d5:a6:33:35:91:34:1e:ef:cf:61:a8:30:1c \(ED25519\)
80/tcp   open  http            Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
|\_http\-server\-header: Apache/2\.4\.41 \(Ubuntu\)
|\_http\-title: blaze
9090/tcp open  ssl/zeus\-admin?
| ssl\-cert: Subject: commonName=blaze/organizationName=d2737565435f491e97f49bb5b34ba02e
| Subject Alternative Name: IP Address:127\.0\.0\.1, DNS:localhost
| Not valid before: 2024\-02\-26T19:08:24
|\_Not valid after:  2124\-02\-02T19:08:24
|\_ssl\-date: TLS randomness does not represent time
| fingerprint\-strings: 
|   GetRequest, HTTPOptions: 
|     HTTP/1\.1 400 Bad request
|     Content\-Type: text/html; charset=utf8
|     Transfer\-Encoding: chunked
|     X\-DNS\-Prefetch\-Control: off
|     Referrer\-Policy: no\-referrer
|     X\-Content\-Type\-Options: nosniff
|     \<\!DOCTYPE html\>
|     \<html\>
|     \<head\>
|     \<title\>
|     request
|     \</title\>
|     \<meta http\-equiv="Content\-Type" content="text/html; charset=utf\-8"\>
|     \<meta name="viewport" content="width=device\-width, initial\-scale=1\.0"\>
|     \<style\>
|     body \{
|     margin: 0;
|     font\-family: "RedHatDisplay", "Open Sans", Helvetica, Arial, sans\-serif;
|     font\-size: 12px;
|     line\-height: 1\.66666667;
|     color: #333333;
|     background\-color: #f5f5f5;
|     border: 0;
|     vertical\-align: middle;
|     font\-weight: 300;
|     margin: 0 0 10px;
|\_    @font\-face \{
1 service unrecognized despite returning data\. If you know the service/version, please submit the following 

**nmap \-sV \-p\- 192\.168\.246\.10 \-v  **
PORT     STATE SERVICE         VERSION
22/tcp   open  ssh             OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.5 \(Ubuntu Linux; protocol 2\.0\)
80/tcp   open  http            Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
9090/tcp open  ssl/zeus\-admin?

nikto \-url http://192\.168\.246\.10
/login\.php: Cookie PHPSESSID created without the httponly flag\. See: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies](#https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)


