### 4.1发表动态

#### URL: [http://112.74.33.82:8080/statusPublish](http://112.74.33.82:8080/statusPublish)

#### Method: POST

#### Parameter:

| 参数 | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| imgUrls | false | String | 图片地址数组字符串 |
| content | true | String | 状态正文 |
| location | true | String | 状态位置 |
| uid | true | String | 发表状态的用户id |

#### JSON示例

```
{
    "status": 1,
    "data": "",
    "msg": "动态发布成功"
}
```





