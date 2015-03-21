# htb.init-openwrt
Modified htb.init shell script for OpenWRT

this is a modified version of htb.init script version 0.8.5 to work around with interface listing and naming in OpenWRT 
these modifications are : 
- interface listing method changed form using "ip" command to "ifconfig"
- fixed error "<interface> has invalid class ID!" on the interface that contain dash "-" on it's name eg : br-lan, 3g-modem

make sure you have installed bash, tc and ip on your openwrt box
