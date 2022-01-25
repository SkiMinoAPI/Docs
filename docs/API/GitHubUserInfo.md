---
    title: GitHub用户信息获取
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://api.datas.gq/GitHubUserInfo

# GitHub用户信息获取
获取某个GitHub用户的信息。

## 返回数据 
```json
{
    "status": 200,
    "data": {
        "user": {
            "idname": "(IDName)",
            "name": "(Name)",
            "id": (ID),
            "url": "(Url)"
        },
        "avatar": "(AvatarUrl)",
        "public_repos": (PublicRepos),
        "followers": (Followers),
        "following": (Following),
        "time": {
            "created_at": "(CreatedTime)",
            "updated_at": "(UpdatedTime)"
        }
    }
}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| name | 是 | string | 需要查询的用户的名称 | * |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>