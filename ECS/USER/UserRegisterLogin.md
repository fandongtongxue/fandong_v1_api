## 1.用户

### 1.1用户注册

#### URL: [http://112.74.33.82:8080/userRegister](http://112.74.33.82:8080/userRegister)

#### Method: POST

#### Parameter:

| 参数 | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| userName | true | String | 用户名 |
| passWord | true | String | 密码 |

#### JSON示例

```
{
    "status": 1,
    "data": {
        "uid": "17"
    },
    "msg": "注册成功"
}
```

```
{
    "status": 0,
    "msg": "用户已存在,请直接登录",
    "data": ""
}
```

### 1.2用户登录

#### URL: [http://112.74.33.82:8080/userLogin](http://112.74.33.82:8080/userLogin)

#### Method: POST

#### Parameter:

| 参数 | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| userName | true | String | 用户名 |
| passWord | true | String | 密码 |

#### JSON示例

```
{
    "status": 0,
    "msg": "用户不存在,请先注册",
    "data": ""
}
```

```
{
    "status": 0,
    "msg": "密码错误",
    "data": ""
}
```

```
{
    "status": 1,
    "data": {
        "uid": "17"
    },
    "msg": "登录成功"
}
```



