# opnsense-dhcpwidget
DHCP Leases list widget for opnsense 24.7+

No warranties. Works for me! May need to be reinstalled on upgrade? Unsure.

### Installation:
- Put [Leases.xml](https://raw.githubusercontent.com/wogglenet/opnsense-dhcpwidget/refs/heads/main/usr/local/opnsense/www/js/widgets/Metadata/Leases.xml) in /usr/local/opnsense/www/js/widgets/Metadata
- Put [Leases.js](https://raw.githubusercontent.com/wogglenet/opnsense-dhcpwidget/refs/heads/main/usr/local/opnsense/www/js/widgets/Leases.js) in /usr/local/opnsense/www/js/widgets/
```shell
pkg install wget
```
```shell
wget -qO /usr/local/opnsense/www/js/widgets/Leases.js https://raw.githubusercontent.com/wogglenet/opnsense-dhcpwidget/refs/heads/main/usr/local/opnsense/www/js/widgets/Leases.js
wget -qO /usr/local/opnsense/www/js/widgets/Metadata/Leases.xml https://raw.githubusercontent.com/wogglenet/opnsense-dhcpwidget/refs/heads/main/usr/local/opnsense/www/js/widgets/Metadata/Leases.xml
```
- Add widget through Opnsense dashboard GUI