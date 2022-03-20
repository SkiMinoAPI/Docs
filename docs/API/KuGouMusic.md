---
    title: 酷狗音乐解析
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://fs.lolimapis.ml/KuGouMusic/

# 酷狗音乐解析
酷狗音乐解析(不含VIP歌曲)。

## 返回数据
Defult:
```
Content-Type:application/mp3;
```
Json:
```json
{
    "status": 200,
    "data": {
        "songhash": "(SongHash)",
        "songid" :(SongID),
        "fileName": "(FileName)",
        "songName": "(SongName)",
        "fileSize": (FileSize),
        "songurl": {
            "defult": "(DefultUrl)",
            "backup":"(BackupUrl)"
        }
    }
}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| hash | 是 | string | 音乐id | * |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>