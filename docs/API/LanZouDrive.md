---
    title: 蓝奏云直链解析
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://fs.lolimapis.ml/LanZouDrive/

# 蓝奏云直链解析
获取蓝奏云直链。

## 返回数据
Defult:
```
Content-Type:文件类型;
```
Json:
```json
{
    "status": 200,
    "data": {
        "name": "(FileName)",
        "author": "(Author)",
        "size": "(FileSize)",
        "url": "(FileUrl)"
    }
}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| url | 是 | string | 文件分享链接 | * |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>