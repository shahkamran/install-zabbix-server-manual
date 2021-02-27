# install-zabbix-server-manual
Manually Install Zabbix Server


ssh me@zabbix_server

wget https://repo.zabbix.com/zabbix/5.3/ubuntu/pool/main/z/zabbix-release/zabbix-release_5.3-1%2Bubuntu20.04_all.deb

sudo dpkg -i zabbix-release_5.3-1+$(lsb_release -sc)_all.deb

