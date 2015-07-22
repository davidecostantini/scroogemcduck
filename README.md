Scrooge McDuck
==============

<img src="https://raw.githubusercontent.com/infomentum/scroogemcduck/master/images/scroogemcduck.jpg" alt=""/>

Scrooge McDuck put files in a safe place (wink)
This tool make standard and encrypted tar backup of files and folder
The encryption is automatically set when a password is specified, the encryption is aes-256-cbc
The encryption use openssl and then send data to tar
--------------


**USAGE**

To execute a backup execute this command:
./scroogemcduck <path_to_backup> <destination_folder> <retention_days> [<pwd>]
pwd is not mandatory, use only if you want to encrypt
Example.
 
Non encrypted backup

	./scroogemcduck /u04/oracle/backups /storage/backup 15

Encrypted backup

	./scroogemcduck /u04/oracle/backups /storage/backup 15 supersecurepwd


**NOTE**
The image and his rights belong to his owner