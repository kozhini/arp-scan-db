Dataset for arp-scan

Openwrt instalation

```
opgk update
opkg install arp-scan arp-scan-database
```
put the file to /etc/arp-scan/ because embaddet txt has wrong destination

```
wget -O /etc/arp-scan/mac-vendor.txt https://raw.githubusercontent.com/kozhini/arp-scan-db/main/mac-vendor.txt
```
