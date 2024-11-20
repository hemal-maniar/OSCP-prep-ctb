**sudo nmap \-sS \-sV \-\-script=default,vuln 192\.168\.164\.89**
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8\.2p1 Ubuntu 4ubuntu0\.1 \(Ubuntu Linux; protocol 2\.0\)
| ssh\-hostkey: 
|   3072 91ba0dd43905e31355578f1b4690dbe4 \(RSA\)
|   256 0f35d1a131f2f6aa75e81701e71ed1d5 \(ECDSA\)
|\_  256 aff153ea7b4dd7fad8de0df228fc86d7 \(ED25519\)
80/tcp open  http    Apache httpd 2\.4\.41 \(\(Ubuntu\)\)
|\_http\-phpself\-xss: ERROR: Script execution failed \(use \-d to debug\)
|\_http\-stored\-xss: Couldn't find any stored XSS vulnerabilities\.
| http\-wordpress\-users: 
| Username found: admin
|\_Search stopped at ID #25\. Increase the upper limit if necessary with 'http\-wordpress\-users\.limit'
| http\-enum: 
|   /wp\-login\.php: Possible admin folder
|   /robots\.txt: Robots file
|   /readme\.html: Wordpress version: 2 
|   /: WordPress version: 5\.4\.2
|   /wp\-includes/images/rss\.png: Wordpress version 2\.2 found\.
|   /wp\-includes/js/jquery/suggest\.js: Wordpress version 2\.5 found\.
|   /wp\-includes/images/blank\.gif: Wordpress version 2\.6 found\.
|   /wp\-includes/js/comment\-reply\.js: Wordpress version 2\.7 found\.                                                  
|   /wp\-login\.php: Wordpress login page\.                                                                            
|   /wp\-admin/upgrade\.php: Wordpress login page\.                                                                    
|\_  /readme\.html: Interesting, a readme\.                                                                            
|\_http\-server\-header: Apache/2\.4\.41 \(Ubuntu\)                                                                        
| http\-csrf:                                                                                                        
| Spidering limited to: maxdepth=3; maxpagecount=20; withinhost=192\.168\.164\.89                                      
|   Found the following possible CSRF vulnerabilities:                                                              
|                                                                                                                   
|     Path: [http://192.168.164.89:80/](#http://192.168.164.89:80/)

|     Form id: search\-form\-1                                                                                        
|     Form action: [http://192.168.164.89/](#http://192.168.164.89/)

|                                                                                                                   
|     Path: [http://192.168.164.89:80/](#http://192.168.164.89:80/)

|     Form id: search\-form\-2                                                                                        
|     Form action: [http://192.168.164.89/](#http://192.168.164.89/)

|                                                                                                                   
|     Path: [http://192.168.164.89:80/index.php/2020/07/](#http://192.168.164.89:80/index.php/2020/07/)

|     Form id: search\-form\-1
|     Form action: [http://192.168.164.89/](#http://192.168.164.89/)

|     
|     Path: [http://192.168.164.89:80/index.php/2020/07/](#http://192.168.164.89:80/index.php/2020/07/)

|     Form id: search\-form\-2
|     Form action: [http://192.168.164.89/](#http://192.168.164.89/)

|     
|     Path: [http://192.168.164.89:80/index.php/author/admin/](#http://192.168.164.89:80/index.php/author/admin/)

|     Form id: search\-form\-1
|     Form action: [http://192.168.164.89/](#http://192.168.164.89/)

|     
|     Path: [http://192.168.164.89:80/index.php/author/admin/](#http://192.168.164.89:80/index.php/author/admin/)

|     Form id: search\-form\-2
|\_    Form action: [http://192.168.164.89/](#http://192.168.164.89/)

|\_http\-dombased\-xss: Couldn't find any DOM based XSS\.
| http\-robots\.txt: 1 disallowed entry 
|\_/secret\.txt
|\_http\-generator: WordPress 5\.4\.2
|\_http\-title: OSCP Voucher \&#8211; Just another WordPress site
Service Info: OS: Linux; CPE: cpe:/o:linux:linux\_kernel

**gobuster dir \-u **[**http://192.168.164.89/**](#http://192.168.164.89/)
**\-w /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt
nikto \-url **[**http://192.168.164.89**](#http://192.168.164.89)
**\-C all
**