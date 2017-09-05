## 2.密码

### 2.1修改密码

#### URL: [http://112.74.33.82:8080/userChangePassWord](http://112.74.33.82:8080/userChangePassWord)

#### Method: GET

#### Parameter:

| 参数 | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| userName | true | String | 用户名 |
| oldPassWord | true | String | 原密码 |
| newPassWord | true | String | 新密码 |

#### JSON示例

```
{
    "data": "",
    "state": 1,
    "msg": "修改密码成功"
}
```

```
{
    "data": "",
    "state": 0,
    "msg": "原密码错误"
}
```



