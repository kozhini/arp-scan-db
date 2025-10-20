Dataset for arp-scan

Openwrt installation

```
opkg update && opkg install arp-scan arp-scan-database
```
put the file to /etc/arp-scan/ because embedded txt has wrong destination

```
mkdir -p /etc/arp-scan
wget -O /etc/arp-scan/mac-vendor.txt https://raw.githubusercontent.com/kozhini/arp-scan-db/main/mac-vendor.txt
```
