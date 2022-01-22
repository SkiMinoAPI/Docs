---
    title: 网易云音乐解析
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://api.datas.gq/163Music

# 网易云音乐解析
网易云音乐解析(部分VIP歌曲解析异常)。

## 返回数据
Defult:
```
Content-Type:application/mp3;
```
Json:
```json
{"status":200,"data":{"songid":"(SongID)","songurl":"(SongUrl)","songlyric":"(SongLyric)"}}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| id | 是 | string | 音乐id | * |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>