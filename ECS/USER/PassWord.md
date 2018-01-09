## 2.密码

### 2.1修改密码

#### URL: [http://fandong.me:8080/userChangePassWord](http://fandong.me:8080/userChangePassWord)

#### Method: POST

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
    "status": 1,
    "msg": "修改密码成功"
}
```

```
{
    "data": "",
    "status": 0,
    "msg": "原密码错误"
}
```



