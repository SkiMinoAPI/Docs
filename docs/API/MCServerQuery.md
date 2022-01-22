---
    title: Minecraft服务器信息查询
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://api.datas.gq/MCServerQuery

# Minecraft服务器信息查询
获取Minecraft服务器信息。

## 返回数据
Defult:
```json
{
    "status": "OK",
    "platform": null,
    "motd": {
        "ingame": "(Motd)"
    },
    "host": {
        "host": "(Host)",
        "port": "(port)"
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
        "agreement": "Ping",
        "processed": "(QueryPing)"
    }
}
```
Image:
```
Content-Type:image/jpeg;
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| host | 是 | string | 服务器域名/IP | * |
| port | 是 | string | 服务器端口 | * |
| image | 否 | isset | 请求图像 |  |
| sn | 否 | string | 在图像上添加文字，仅请求图像有效 | * |
| theme | 否 | string | 选择一个主题，仅请求图像有效 | dark , light |
| font | 否 | string | 为卡片文字选择外部字体，请使用 :enand: 替代字符 & | * |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>