Weeman - http server for phishing
Weeman

DISCLAIMER
Usage of Weeman for attacking targets without prior mutual consent is illegal. Weeman developer not responsible to any damage caused by Weeman.

About
HTTP server for phishing in python. Weeman has support for most of the (bigest) websites.

Usually you will want run Weeman with DNS spoof attack. (see dsniff, ettercap).

Weeman will do the following steps:
Create fake html page.
Wait for clients
Grab the data (POST).
Try to login the client to the original page smiley
Requirements
Python <= 2.7.
Python BeautifulSoup 4
Install BeautifulSoup
Archlinux - sudo pacman -S python2-beautifulsoup4
Ubuntu/Linuxmint - sudo apt-get install python-bs4
For another OS: - sudo pip install beautifulsoup4
Platforms
Linux (any)
Mac (Not tested)
Windows (Not tested)
[!] If weeman runs on your platform (Mac/Windows), please let me know.

Usage
Just type help

Run server:
For port 80 you need to run Weeman as root!

Host to clone (Ex: www.social-networks.local)

set url http://localhost

"<"form action = "TAKE THIS URL">"(View the site source and take the URL)
set action_url http://localhost/sendlogin

The port Weeman server will listen
set port 2020

Start the server
run

The settings will be saved for the next time you run weeman.py.

Get Weeman
            git clone git://github.com/Hypsurus/weeman
Copyright 2015 (C) Hypsurus hypsurus@mail.ru.

License GPLv3+: GNU GPL version 3 or later http://gnu.org/licenses/gpl.html.
