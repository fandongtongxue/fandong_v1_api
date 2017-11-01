### 5.2获取评论列表

#### URL: [http://112.74.33.82:8080/commentList](http://112.74.33.82:8080/commentList)

#### Method: GET

#### Parameter:

|  | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| objectId | true | String | 对象id\(电视台就是channelId\) |
| type | true | String | 类型:0:电视台 |

#### JSON示例

```
{
    "status": 1,
    "msg": "获取评论列表成功",
    "data": {
        "commentList": [
            {
                "comment": "Eeee",
                "createTime": "Tue, 31 Oct 2017 21:25:58 +0800",
                "id": 1,
                "channelId": 1,
                "uid": 58
            },
            {
                "comment": "Wewqwqeq",
                "createTime": "Tue, 31 Oct 2017 21:42:41 +0800",
                "id": 2,
                "channelId": 1,
                "uid": 58
            }
        ]
    }
}
```



