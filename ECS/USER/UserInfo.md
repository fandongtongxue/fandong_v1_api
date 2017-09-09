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

### 3.2更改用户信息

#### URL: [http://112.74.33.82:8080/userChangeUserInfo](http://112.74.33.82:8080/userChangeUserInfo)

#### Method: GET

#### Parameter:

| 参数 | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| uid | true | String | 用户Id |
| nickName | true | String | 昵称 |
| introduce | true | String | 简介 |
| icon | true | String | 头像 |

#### JSON示例

```
{
    "msg": "更新用户信息成功",
    "data": "",
    "status": 1
}
```



