---
    title: QQ用户头像获取
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://api.datas.gq/QQUserAvatar

# QQ头像获取
获取某个QQ用户的头像。

## 返回数据
Defult: 
```
Content-Type:image/jpeg;
```
Json: 
```json
{"qqcode":"(QQCode)","size":(Size),"avatars":{"t0":"https:\/\/q.qlogo.cn\/headimg_dl?img_type=jpg&dst_uin=(QQCode)&spec=(Size)","t1":"https:\/\/q1.qlogo.cn\/g?b=qq&nk=(QQCode)&s=(Size)","t2":"https:\/\/q2.qlogo.cn\/headimg_dl?dst_uin=(QQCode)&spec=(Size)","t3":"https:\/\/q4.qlogo.cn\/g?b=qq&nk=(QQCode)&s=(Size)"}}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| qc | 是 | string | 需要查询的QQ号 | * |
| t | 否 | string | 接口，请求json时无效 | 0 , 1 , 2 , 3 , 4 |
| size | 否 | string | 图像质量 | 0 , 40 , 100 , 140 , 640 |
| json | 否 | isset | 请求json数据 |  |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>