## 1.检查

### 1.1检查是否已提交

#### URL:[http://fandong.me/api/QiniuServer/vendor/qiniu/php-sdk/examples/check.php](http://fandong.me/api/QiniuServer/vendor/qiniu/php-sdk/examples/check.php)

#### Method: GET

#### Parameter:

|  | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| uuid | true | String | 设备唯一识别码 |

#### JSON示例

```
{
    "data": {
        "accessKey": "JkFGFDvaJ2WDZlvPSnoasdsaasdXmbY8qnw7nMBh",
        "secretKey": "6U5lamt5ei2bgmar3FsdasaasdNgF0WHJ",
        "bucket": "fandongasdsdt-cloud"
    },
    "status": 1,
    "error": 0
}
```

### 1.2提交

#### URL:[http://fandong.me/api/QiniuServer/vendor/qiniu/php-sdk/examples/submit.php](http://fandong.me/api/QiniuServer/vendor/qiniu/php-sdk/examples/submit.php)

#### Method: GET

#### Parameter:

|  | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| uuid | true | String | 设备唯一识别码 |
| accessKey | true | String | 七牛云accessKey |
| secretKey | true | String | 七牛云secretKey |
| bucket | true | String | 七牛云bukcet |

#### JSON示例

```
{
    "data": "提交成功",
    "status": 1,
    "error": "0"
}
```

### 1.3重新提交

#### URL:[http://fandong.me/api/QiniuServer/vendor/qiniu/php-sdk/examples/resubmit.php](http://fandong.me/api/QiniuServer/vendor/qiniu/php-sdk/examples/resubmit.php)

#### Method: GET

#### Parameter:

|  | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| uuid | true | String | 设备唯一识别码 |
| accessKey | true | String | 七牛云accessKey |
| secretKey | true | String | 七牛云secretKey |
| bucket | true | String | 七牛云bukcet |

#### JSON示例

```
{
    "data": "提交成功",
    "status": 1,
    "error": "0"
}
```



