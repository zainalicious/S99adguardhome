# S99adguardhome
install

```sh
cd /tmp
curl -s -S -L https://raw.githubusercontent.com/AdguardTeam/AdGuardHome/master/scripts/install.sh | sh -s -- -v
```
save config file 
```sh
wget -O /usrdata/opt/AdGuardHome/AdGuardHome.yaml \
https://raw.githubusercontent.com/USERNAME/REPO/main/AdGuardHome.yaml
```
add service
```sh
wget -O /usrdata/opt/etc/init.d/S99adguardhome \
https://raw.githubusercontent.com/USERNAME/REPO/main/S99adguardhome

chmod +x /usrdata/opt/etc/init.d/S99adguardhome

/usrdata/opt/etc/init.d/S99adguardhome start
```
