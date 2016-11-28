# AutoVPN
Author: Bakhtiyar Syed

This is an automatic VPN installer/runner for IIIT-H students.


**Usage:**
>
1. After downloading the zip, extract it.
2. cd AutoVPN/ OR cd AutoVPN-master/ (depending on your mode of download via cloning or direct download.)
3. sudo sh autovpn.sh emailID password

(Your official IIIT-H students/research email and password must be entered in place of emailID and password respectively.)

**Requirements:**
>
None (:

**Constraints:**
>
Works only on Ubuntu(apt-get package) related systems right now.
You need to run the script with root access(sudo).
Also, if you need to close the process running the VPN, just run ps -ef | grep autovpn on your terminal, note the process id of autovpn and kill the process via kill -9 pidnumber.

*Pull requests and suggestions for improvement are most welcome.*



