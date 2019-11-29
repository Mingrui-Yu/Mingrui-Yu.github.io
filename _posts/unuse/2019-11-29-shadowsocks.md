---
title: ubuntu中配置shadowsocks
description:
categories: Tutorial/Ubuntu
tags: 
- ubuntu
- shadowsocks
---


安装shadowsocks3.0:
```
sudo pip3 install https://github.com/shadowsocks/shadowsocks/archive/master.zip -U
```

配置：
```
sudo nano /etc/shadowsocks.json
```
内填入：

```
{
    "server":"服务器的ip",
    "server_port":xxxxx,
    "local_address":"127.0.0.1",
    "local_port":1080,
    "password":"密码",
    "timeout":300,
    "method":"aes-256-gcm"
}
```

之后配置网络代理：ubuntu设置-网络-网络代理-手动：在Socks中填入127.0.0.1和1080。
