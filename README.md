<p align="center">
<picture>
<img width="300" height="120"  alt="XPanel" src="https://github.com/iPmartNetwork/iPmartnetwork/blob/main/iPmart.png">
</picture>
  </p> 
</div>

<p align="center">
<h1 align="center"/>Breadcrumbsmulti-v2ray</h1>
<h6 align="center">V2RAy Multi<h6>
</p>




## Feature
- Support Xray manage, different commands (v2ray/xray) enter different core management
- V2ray && Iptables Traffic Statistics
- Command line to manage
- Multiple user && port manage
- Cloudcflare cdn mode
- Support pure ipv6 VPS
- Support Docker
- Dynamic port
- Ban bittorrent
- Range port
- TcpFastOpen
- Vmess/VLESS/Socks5/MTproto share link
- Support protocol modify:
  - TCP
  - Fake http
  - WebSocket
  - mkcp
  - mKCP + srtp
  - mKCP + utp
  - mKCP + wechat-video
  - mKCP + dtls
  - mKCP + wireguard
  - HTTP/2
  - Socks5
  - MTProto
  - Shadowsocks
  - Quic
  - VLESS_TCP
  - VLESS_TLS
  - VLESS_WS
  - VLESS_REALITY
  - Trojan

## How To Use
new install
```
bash <(curl -Ls https://raw.githubusercontent.com/iPmartNetwork/multi-v2ray/main/v2ray.sh)
```

keep profile to update
```
bash <(curl -Ls https://raw.githubusercontent.com/iPmartNetwork/multi-v2ray/main/v2ray.sh) -k
```

uninstall
```
bash <(curl -Ls https://raw.githubusercontent.com/iPmartNetwork/multi-v2ray/main/v2ray.sh) --remove
```

## Command Line
```bash
v2ray/xray [-h|help] [options]
    -h, help             get help
    -v, version          get version
    start                start V2Ray
    stop                 stop V2Ray
    restart              restart V2Ray
    status               check V2Ray status
    new                  create new json profile
    update               update v2ray to latest
    update [version]     update v2ray to special version
    update.sh            update multi-v2ray to latest
    add                  add new group
    add [protocol]       create special protocol, random new port
    del                  delete port group
    info                 check v2ray profile
    port                 modify port
    tls                  modify tls
    tfo                  modify tcpFastOpen
    stream               modify protocol
    cdn                  cdn mode
    stats                v2ray traffic statistics
    iptables             iptables traffic statistics
    clean                clean v2ray log
    log                  check v2ray log
    rm                   uninstall core
```

## Docker Run
default will create random port + random header(srtp | wechat-video | utp | dtls) kcp profile(**if use xray replace image to jrohy/xray**)  
```
docker run -d --name v2ray --privileged --restart always --network host jrohy/v2ray
```

custom v2ray config.json:
```
docker run -d --name v2ray --privileged -v /path/config.json:/etc/v2ray/config.json --restart always --network host jrohy/v2ray
```

check v2ray profile:
```
docker exec v2ray bash -c "v2ray info"
```

**warning**: if u run with centos, u should close firewall first
```
systemctl stop firewalld.service
systemctl disable firewalld.service
```



## حمایت از ما :hearts:
حمایت های شما برای ما دلگرمی بزرگی است<br> 
<p align="left">
<a href="https://plisio.net/donate/kB7QU7f7" target="_blank"><img src="https://plisio.net/img/donate/donate_light_icons_mono.png" alt="Donate Crypto on Plisio" width="240" height="80" /></a><br>
	
|                    TRX                   |                       BNB                         |                    Litecoin                       |
| ---------------------------------------- |:-------------------------------------------------:| -------------------------------------------------:|
| ```TJbTYV1fFo2485sYMyajxGPLFzxmNmPrNA``` |  ```0x4af3de9b303a8d43105e284823d95b4c600961a3``` | ```MPrkzFiNtw4Rg67bbZB6gCxa9LV87orABM``` |	

</p>	







# تلگرام

[@ipmart_network](https://t.me/ipmart_network)


[@ipmart Channel](https://t.me/ipmartch)





<p align="center">
<picture>
<img width="160" height="160"  alt="XPanel" src="https://github.com/iPmartNetwork/iPmart-SSH/blob/main/images/logo.png">
</picture>
  </p> 





