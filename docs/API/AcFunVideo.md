---
    title: AcFun视频直链解析
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://api.datas.gq/AcFunVideo

# AcFun视频直链解析
AcFun视频直链解析(非番剧)。
由于AcFun有pkey验证，请自行获取pkey

## 返回数据
```json
{"status":200,"data":{"videoid":"(VideoID)","author":{"name":"(Name)","id":"(ID)"},"videourl":"(Url)?pkey=(pkey)"}}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| url | 是 | string | 视频链接地址 | * |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>