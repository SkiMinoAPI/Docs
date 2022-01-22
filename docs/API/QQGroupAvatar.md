---
    title: QQ群头像获取
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://api.datas.gq/QQGroupAvatar

# QQ群头像获取
获取某个QQ群的头像。

## 返回数据
Defult: 
```
Content-Type:image/jpeg;
```
Json: 
```json
{"qqgcode":"(QQGroupCode)","size":(Size),"avatar":"https:\/\/p.qlogo.cn\/gh\/(QQGroupCode)\/(QQGropuCode)\/(Size)"}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| qgc | 是 | string | 需要查询的QQ群号 | * |
| size | 否 | string | 图像质量 | 0 , 40 , 100 , 140 , 640 |
| json | 否 | isset | 请求json数据 |  |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>