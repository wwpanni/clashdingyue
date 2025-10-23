# 订阅转换服务地址
```sh
www.jjgo.top:25500/sub
```
# 模板地址
```sh
https://git.wwok.top/https://raw.githubusercontent.com/wwpanni/clashdingyue/refs/heads/main/clash.ini
```
# 转换前端
https://clash.jjgo.top:44433/
# XMRth订阅链接
https://www.xmrth.lol/user
# 红杏订阅链接
https://hongxingyun.xyz/
# 便宜不限时间节点 光速机场
https://www.gscloud.sbs

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
