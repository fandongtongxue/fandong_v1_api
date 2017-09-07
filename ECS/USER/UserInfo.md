## 3.用户信息

### 3.1获取用户信息

#### URL: [http://112.74.33.82:8080/userInfo](http://112.74.33.82:8080/userInfo)

#### Method: GET

#### Parameter:

| 参数 | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| uid | true | String | 用户Id |

#### JSON示例

```
{
    "data": {
        "userInfo": [
            {
                "nickName": "111",
                "introduce": "Nothing to say",
                "id": 1,
                "icon": "http://ov2uvg3mg.bkt.clouddn.com/USER_DEFAULT_ICON.jpg",
                "uid": 6
            }
        ]
    },
    "status": 1,
    "msg": "获取用户信息成功"
}
```



