
# Auto install Shadowsocks Server

one-click install
===============================
wget --no-check-certificate -O shadowsocks-all.sh https://rahttps://raw.githubusercontent.com/Makebignew/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

========================================================
To uninstall

./shadowsocks-all.sh uninstall

==========================================
Command List

Shadowsocks-Python ：
/etc/init.d/shadowsocks-python start | stop | restart | status

ShadowsocksR ：
/etc/init.d/shadowsocks-r start | stop | restart | status

Shadowsocks-Go ：
/etc/init.d/shadowsocks-go start | stop | restart | status

Shadowsocks-libev ：
/etc/init.d/shadowsocks-libev start | stop | restart | status

====================================================================
Configuration File

Shadowsocks-Python ：
/etc/shadowsocks-python/config.json

ShadowsocksR ：
/etc/shadowsocks-r/config.json

Shadowsocks-Go ：
/etc/shadowsocks-go/config.json

Shadowsocks-libev ：
/etc/shadowsocks-libev/config.json


Copyright (C) 2014-2019 Teddysun
