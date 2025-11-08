
# 转换前端
https://clash.jjgo.top/
# 69云订阅链接
国内 https://china.69yun69.com
国外 https://69yun69.com
# XMRth订阅链接
https://www.xmrth.lol/user


# pc端软件 clash-party
https://github.com/mihomo-party-org/clash-party

# 安卓软件 Clash Meta for Android
https://github.com/MetaCubeX/ClashMetaForAndroid


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
