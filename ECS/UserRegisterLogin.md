## 1.用户

### 1.1用户注册

#### URL: [http://112.74.33.82:8080/userRegister](http://112.74.33.82:8080/userRegister)

#### Method: GET

#### Parameter:

| 参数 | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| userName | true | String | 用户名 |
| passWord | true | String | 密码 |

#### JSON示例

```
{
    "state": 1,
    "msg": "注册成功",
    "data": ""
}
```

```
{
    "state": 0,
    "msg": "用户已存在,请直接登录",
    "data": ""
}
```

### 1.2用户登录

#### URL: [http://112.74.33.82:8080/userLogin](http://112.74.33.82:8080/userLogin)

#### Method: GET

#### Parameter:

| 参数 | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| userName | true | String | 用户名 |
| passWord | true | String | 密码 |

#### JSON示例

```
{
    "state": 0,
    "msg": "用户不存在,请先注册",
    "data": ""
}
```

```
{
    "state": 0,
    "msg": "TODO还需要密码验证",
    "data": ""
}
```



