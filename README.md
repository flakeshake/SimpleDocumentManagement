# SimpleDocumentManagement

--- IMPORTANT NOTE --- 

This script installs a samba Server for user "pi", if you have Samba allready installed you can have trouble.
If you dont want the samba Part from this script just delete the content in the script.


This script should install a complete Document Management System on a Raspberry Pi ( Wheezy ) or other Debian based Systems. This script takes only care of the installationprocess from other tools.
At the end, i hope,  you can access all your scanned documents via webbrowser (http://IP:8080) . 

All your documents should now have fulltext search possibility.

Know Issus:  German "Umlaute" Ä / Ü / Ö etc doesent work well.  

At this point i want to say Thanks! to:

Jan Karres (http://www.jankarres.de) for the scripts (index.sh , run.sh, clean.sh and the Webrecoll.py)
this script based on his work http://jankarres.de/2014/03/raspberry-pi-dokumentenverwaltung-mit-ocr-einrichten

also i want to say thanks to the developer of Recoll and the Github User Koniu for his Webrecoll Projekt (https://github.com/koniu/recoll-webui) and Github User fritz-hh for his work on OCRmyPDF (https://github.com/fritz-hh/OCRmyPDF/).

I am sorry that i have to use old versions of some scripts.


Realy Realy Realy IMPORTANT NOTE:


If all works fine (i hope so), you can access all your Documents via WEB.

Take care that you never releaser your Stuff to the Internet!


How to install:

sudo apt-get install git

git clone https://github.com/juxreal/SimpleDocumentManagment

Chmod -x SDM.sh

./SDM.sh
