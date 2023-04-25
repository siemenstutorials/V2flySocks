# V2flySocks
# File Path
````bash
installed: /usr/local/bin/v2ray
installed: /usr/local/bin/v2ctl
installed: /usr/local/share/v2ray/geoip.dat
installed: /usr/local/share/v2ray/geosite.dat
installed: /usr/local/etc/v2ray/config.json
installed: /var/log/v2ray/
installed: /var/log/v2ray/access.log
installed: /var/log/v2ray/error.log
installed: /etc/systemd/system/v2ray.service
installed: /etc/systemd/system/v2ray@.service
````

# install v2ray
```bash
apt install curl
````
```bash
bash <(curl -L https://raw.githubusercontent.com/siemenstutorials/V2flySocks/master/v2fly.sh)
````
# install dat
```bash
bash <(curl -L https://raw.githubusercontent.com/siemenstutorials/V2flySocks/master/install_dat.sh)
````
# remove v2ray
```bash
bash <(curl -L https://raw.githubusercontent.com/siemenstutorials/V2flySocks/master/v2fly.sh) --remove
````

# Config.json
wget -P /usr/local/etc/v2ray/ https://raw.githubusercontent.com/siemenstutorials/V2flySocks/master/config.json

# Control 
```bash
service v2ray status
service v2ray stop
service v2ray restart
````

