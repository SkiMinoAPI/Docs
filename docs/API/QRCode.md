---
    title: QRCode生成
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://api.datas.gq/QRCode

# QRCode生成
通过Url生成相应的QRCode。

## 返回数据
```
Content-Type:image/jpeg;
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| url | 是 | string | QRCode指向的链接。请使用 :enand: 替代字符 & | * |
| size | 否 | string | QRCode的大小 | 0-40 |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>