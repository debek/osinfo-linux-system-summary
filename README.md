# osinfo

This script show info about Your sytem after every login or in manual use.

Example of output:
- Hostname / IP.......:  base / XXX.XXX.XX.XXX 
 - Release.............:  CentOS Linux 7 (Core) 
 - Users...............:  Currently 1 user(s) logged on: ddebny 
 - Users with su ......:  Currently 0 user(s) using su -:  
===========================================================================
 - Current user........:  ddebny 
 - Load................:  0.02, 0.04, 0.05 
 - Memory used.........:  2790 MB / 7821 MB (4233 MB) remaining 
 - Processes...........:  182 running 
 - System uptime.......:  14 days 7 hours 48 minutes 0 seconds 
 - Disk space /........:  14G of 39G (24G) remaining

How install:
export PATH=$PATH:/opt/bin

Copy script to /opt/bin/osinfo
chmod +x /opt/bin/osinfo

Add this line to file:
vim /root/bash_profile
osinfo
