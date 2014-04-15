## 下記の gist を /etc/motd に貼り付けることで可能です
※debian系なら /etc/motd.tail にどうぞ

### favicon type
![alt zabbix-ico.jpg](https://github.com/dot-motd/zabbix/raw/master/images/zabbix-ico.jpg)

[gist:zabbix-ico.txt](https://gist.githubusercontent.com/makocchi-git/9936457/raw/0921640be3495ce3c6d998043815c90573f7c298/zabbix-ico.txt)

### logo
![zabbix-logo.jpg](https://github.com/dot-motd/zabbix/raw/master/images/zabbix-logo.jpg)

[gist:zabbix-logo.txt](https://gist.githubusercontent.com/makocchi-git/9936457/raw/deb0d3323f1ccef4ca07aefd74d38168fc0b7563/zabbix-logo.txt)

### logo (min)
![zabbix-logo-min.jpg](https://github.com/dot-motd/zabbix/raw/master/images/zabbix-log-min.jpg)

[gist:zabbix-logo-min.txt](https://gist.githubusercontent.com/makocchi-git/9936457/raw/a9f82ae810fba4b45cdcb648bfa443944c312297/zabbix-logo-mini.txt)

### こんな感じでどうぞ
```bash
$ curl -s <gistのurl> | sudo tee -a /etc/motd
```
