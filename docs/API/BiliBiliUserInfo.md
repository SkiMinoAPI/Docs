---
    title: BiliBili用户信息获取
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://api.datas.gq/BiliBiliUserInfo

# BiliBili用户信息获取
获取某位BiliBili用户的信息。

## 返回数据
```json
{"status":200,"data":{"uid":(uid),"name":"(Name)","cover":"(Cover)","sex":"(Sex)","birthday":"(Birthday)","level":[(Level),(Type)],"topcover":"(TopCover)","introduction":"(Introduction)","vip":{"type":(Type),"due_date":(DueDate),"label":{"text":"(Text)","label_theme":"(Theme)","text_color":"(Color)","bg_style":(Style),"bg_color":"(Color)","border_color":"(Color)"},"nickname_color":"(Color)","role":(Role),"vipicon":"(Icon)"},"fans":{"badge":(Badge),"medal":{"name":(MedalName),"show":(Show),"wear":(Wear)},"follower":(Follower),"following":(Following),"black":(Black)},"work":{"quantity":(Quantity),"submission":(Submission),"cinema":(Cinema),"article":(Article),"playlist":(PlayList),"photoalbum":(PhotoAlbum),"audio":(Audio),"pugv":(Pugv),"season_num":(SeasonNum)},"official":{"role":(Role),"title":"(Title","honourinfo":{"pendant":"(Pendant)","nameplate":"(NamePlate)"}},"live":{"title":"(Title)","url":"(LiveUrl)","cover":"(LiveCover)","online":(OnLineTime),"id":(LiveID)}}}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| uid | 是 | string | 用户uid | * |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>