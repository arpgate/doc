# Doc

Requirements:

Raspberry Pi 2 Model B
8Gb micro SD card
=======

Arpgate

connect your home

Requirements:

Raspberry Pi 2 Model B 8Gb micro SD card

Installation of Ubuntu Trusty Tahr 14.04 on Rasspberry PI: https://wiki.ubuntu.com/ARM/RaspberryP

Install Puppet: http://stdout.no/puppet-on-raspberry-pi

Upcoming:
We are working on a Puppet script to install the following Arpgate components:

- Golang
- SQLite 3  
- nmap
- iptables
- HAproxy
- Nginx
- isc-dhcp-server
- TFTPD-HPA
- Bind 9
- Snort
- MQTT
- StrongSwarm

We will make a download for the SD card image available once the puppet build is completed

Guides to copy the image to the SD card:

Linux: http://www.raspberrypi.org/documentation/installation/installing-images/linux.md

Mac: http://www.raspberrypi.org/documentation/installation/installing-images/mac.md

Windows: http://www.raspberrypi.org/documentation/installation/installing-images/windows.md


The arpgate UI
==============

The ui will be based on bootstrap: http://devoops.me/themes/devoops/
https://github.com/devoopsme/devoops.

The UI connects using JQuery to our arpgate/manage REST services and the MQTT broker.







=======
Upcoming: We are working on a Puppet script to install the following Arpgate components:

Golang
Nginx
HAproxy
nmap
iptables
isc-dhcp-server
TFTPD-HPA
Snort
MQTT
StrongSwarm
SQLLite3
>>>>>>> 415a3bca1315a6ea0062708654ebb2edccbac327

