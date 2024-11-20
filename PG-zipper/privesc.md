cat /opt/backup\.sh
cat /opt/backup\.sh
#\!/bin/bash
password=\`cat /root/secret\`
cd /var/www/html/uploads
rm \*\.tmp
7za a /opt/backups/backup\.zip \-p$password \-tzip \*\.zip \> /opt/backups/backup\.log

-  cat backup\.log
Open archive: /opt/backups/backup\.zip
\-\-
Path = /opt/backups/backup\.zip
Type = zip
Physical Size = 5161

Scanning the drive:
10 files, 3804 bytes \(4 KiB\)

Updating archive: /opt/backups/backup\.zip

Items to compress: 10


Files read from disk: 10
Archive size: 5161 bytes \(6 KiB\)

Scan WARNINGS for files and folders:

WildCardsGoingWild: No more files
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-
Scan WARNINGS: 1