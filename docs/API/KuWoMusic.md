---
    title: 酷我音乐解析
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://fs.lolimapis.ml/KuWoMusic/

# 酷我音乐解析
酷我音乐解析(含VIP歌曲)。

## 返回数据
Defult:
```
Content-Type:application/aac;
```
Json:
```json
{
    "status": 200,
    "data": {
        "songid": "(SongID)",
        "songurl": "(SongUrl)"
    }
}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| id | 是 | string | 音乐id | * |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>