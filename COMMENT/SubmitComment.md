### 5.1撰写评论

#### URL: [http://fandong.me:8080/comment](http://fandong.me:8080/comment)

#### Method: POST

#### Parameter:

|  | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| uid | true | String | 用户uid |
| objectId | true | String | 对象Id,电视台就是channelId |
| type | true | String | 类型,电视台就是0 |
| comment | true | String | 评论内容 |

#### JSON示例

```
{
    "status": 1,
    "msg": "评论成功",
    "data": ""
}
```



