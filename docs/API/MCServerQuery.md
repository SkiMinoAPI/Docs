---
    title: Minecraft服务器信息查询
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://fs.lolimapis.ml/MCServerQuery/

# Minecraft服务器信息查询
获取Minecraft服务器信息。

## 返回数据
```json
{
    "status": 200,
    "data": {
        "icon": "(Base64Icon)",
        "motd": "(Motd)",
        "server": {
            "host": "(Host)",
            "port":"(Port)"
        },
        "players": {
            "max": (MaxPlayers),
            "online": (OnlinePlayers)
        },
        "version": {
            "version": (Version),
            "protocol": (VersionCode)
        },
        "queryinfo": {
            "Ping":"(Ping)"
        }
    }
}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| host | 是 | string | 服务器域名/IP | * |
| port | 是 | string | 服务器端口 | * |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>
