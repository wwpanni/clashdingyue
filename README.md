# 转换模板
```sh
https://raw.githubusercontent.com/wwpanni/clashdingyue/refs/heads/main/clash.ini
```
# 转换前端
https://clash.jjgo.top/
# 69云订阅链接
国内 https://china.69yun69.com
国外 https://69yun69.com
# XMRth订阅链接
https://www.xmrth.lol/user

# 规则集选择地址
https://github.com/MetaCubeX/meta-rules-dat/tree/meta/geo/geosite 


# pc端软件安卓软件 FIClash
[https://github.com/mihomo-party-org/clash-party](https://github.com/chen08209/FlClash)



# 订阅转换服务搭建
docker compose
```compose
version: '3.1' 
services:
    "subconverter":
        image: asdlokj1qpi23/subconverter:latest
        container_name: "subconverter"
        restart: always
        ports:
            - '25500:25500'

    "subweb":
        image: junjie11/subweb:latest
        container_name: "subweb"
        restart: always
        ports:
            - '8888:80'
```
