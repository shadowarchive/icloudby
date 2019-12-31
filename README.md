## Commands:

Paste this into the first terminal window:

( 1 ):
* ./tcprelay.py -t 44:2222

Paste this into the second terminal window:

( 1 ):
* ssh root@localhost -p 2222

( 2 ):
* mount -o rw,union,update /

(3):
* echo "" >> /.mount_rw

( 4 ):
* mv /Applications/Setup.app /Applications/Setup.app.crae

( 5 ):
* uicache --all

( 6 ):
* killall backboardd

( C ) - This method was developed by AppleTech752, AppleDemo, and Exploit3d.
