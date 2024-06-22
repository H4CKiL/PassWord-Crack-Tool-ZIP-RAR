created By @H4CK_iL

In order to run the script properly, specific modules must be installed.

Please install:

pip install rarfile
pip install zipfile

and if there is a 'NameError:' please not that all of the methods are installed

all methods that im use already imported in the script and no need to reimpoet them!

import rarfile
import os
import zipfile
import threading
import time

[!] for use a password need first add a password list to the PassWord.txt file!

you can find a lists here:

https://github.com/danielmiessler/SecLists/tree/master/Passwords/Common-Credentials

for sortcut:

top 100 - https://raw.githubusercontent.com/danielmiessler/SecLists/master/Passwords/Common-Credentials/10-million-password-list-top-100.txt
top 1K - https://raw.githubusercontent.com/danielmiessler/SecLists/master/Passwords/Common-Credentials/10-million-password-list-top-1000.txt
top 10K - https://raw.githubusercontent.com/danielmiessler/SecLists/master/Passwords/Common-Credentials/10-million-password-list-top-10000.txt
top 100K - https://raw.githubusercontent.com/danielmiessler/SecLists/master/Passwords/Common-Credentials/10-million-password-list-top-100000.txt
top 1M - https://raw.githubusercontent.com/danielmiessler/SecLists/master/Passwords/Common-Credentials/10-million-password-list-top-1000000.txt

