# S99adguardhome
install

```sh
cd /tmp
curl -s -S -L https://raw.githubusercontent.com/AdguardTeam/AdGuardHome/master/scripts/install.sh | sh -s -- -v
```
save config file 
```sh
wget -O /opt/AdGuardHome/AdGuardHome.yaml \
https://raw.githubusercontent.com/USERNAME/REPO/main/AdGuardHome.yaml
```
add service
```sh
wget -O /opt/etc/init.d/S99adguardhome \
https://raw.githubusercontent.com/USERNAME/REPO/main/S99adguardhome

chmod +x /opt/etc/init.d/S99adguardhome

/opt/etc/init.d/S99adguardhome restart
```
