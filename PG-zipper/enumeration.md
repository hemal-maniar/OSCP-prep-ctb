**sudo nmap \-sS \-sV \-\-script=default 192\.168\.246\.229
**PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.3 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 c1:99:4b:95:22:25:ed:0f:85:20:d3:63:b4:48:bb:cf \(RSA\)
|   256 0f:44:8b:ad:ad:95:b8:22:6a:f0:36:ac:19:d0:0e:f3 \(ECDSA\)
|\_  256 32:e1:2a:6c:cc:7c:e6:3e:23:f4:80:8d:33:ce:9b:3a \(ED25519\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
|\_http\-server\-header: Apache/2\.4\.41 \(Ubuntu\)
|\_http\-title: Zipper
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**nmap \-sV \-p\- 192\.168\.246\.229 \-v**
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.3 \(Ubuntu Linux; protocol 2\.0\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

/uploads              \(Status: 301\) \[Size: 320\] \[\-\-\> [http://192.168.246.229/uploads/\]](#http://192.168.246.229/uploads/])

/upload\.php           \(Status: 200\) \[Size: 0\]
/style                \(Status: 200\) \[Size: 155\]
/home\.php             \(Status: 200\) \[Size: 3151\]
/index\.php            \(Status: 200\) \[Size: 3151\]

upload\.php

\<?php
if \($\_FILES \&\& $\_FILES\['img'\]\) \{

if \(\!empty\($\_FILES\['img'\]\['name'\]\[0\]\)\) \{

$zip = new ZipArchive\(\);
$zip\_name = getcwd\(\) \. "/uploads/upload\_" \. time\(\) \. "\.zip";

// Create a zip target
if \($zip\-\>open\($zip\_name, ZipArchive::CREATE\) \!== TRUE\) \{
$error \.= "Sorry ZIP creation is not working currently\.\<br/\>";
\}

$imageCount = count\($\_FILES\['img'\]\['name'\]\);
for\($i=0;$i\<$imageCount;$i\+\+\) \{

if \($\_FILES\['img'\]\['tmp\_name'\]\[$i\] == ''\) \{
continue;
\}
$newname = date\('YmdHis', time\(\)\) \. mt\_rand\(\) \. '\.tmp';

// Moving files to zip\.
$zip\-\>addFromString\($\_FILES\['img'\]\['name'\]\[$i\], file\_get\_contents\($\_FILES\['img'\]\['tmp\_name'\]\[$i\]\)\);

// moving files to the target folder\.
move\_uploaded\_file\($\_FILES\['img'\]\['tmp\_name'\]\[$i\], '\./uploads/' \. $newname\);
\}
$zip\-\>close\(\);

// Create HTML Link option to download zip
$success = basename\($zip\_name\);
\} else \{
$error = '\<strong\>Error\!\! \</strong\> Please select a file\.';
\}
\}