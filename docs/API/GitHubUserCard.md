---
    title: GitHub签名档
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://api.datas.gq/GitHubUserCard

# GitHub签名档
生成一张GitHub签名档。生成的内容为SVG图像。

## 返回数据
```
Content-Type:image/svg+xml;
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| name | 是 | string | 登录GitHub的名称 | * |
| bg_color | 否 | string | 背景颜色(请使用16进制颜色代码，不含#号) | * |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>