## 1.文件列表

### 1.1图片列表

#### URL:[http://api.fandong.me/api/qiniucloudstorge/php-sdk-master/examples/list\_file\_image.php](http://api.fandong.me/api/qiniucloudstorge/php-sdk-master/examples/list_file_image.php)

#### Method: GET

#### Parameter:

|  | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| uuid | true | String | 设备唯一识别码 |

#### JSON示例

```
{
    "data": {
        "data": [
            {
                "key": "Image_iP1433782551978_2754be50-2df4-4d56-bc28-24b8ca4f462f_by_camera (1).jpeg",
                "hash": "FiB3Sl0kmo54mAgfwgBf4NKeLGz6",
                "fsize": 267800,
                "mimeType": "image/jpeg",
                "putTime": 14863861846941936,
                "type": 0
            }
        ],
        "marker": "eyJjIjowLCJrIjoiSW1hZ2VfaVAxNDMzNzgyNTUxOTc4XzI3NTRiZTUwLTJkZjQtNGQ1Ni1iYzI4LTI0YjhjYTRmNDYyZl9ieV9jYW1lcmEgKDYpLmpwZyJ9"
    },
    "status": 1,
    "error": 0
}
```

### 1.2音乐列表

#### URL:[http://api.fandong.me/api/qiniucloudstorge/php-sdk-master/examples/list\_file\_music.php](http://api.fandong.me/api/qiniucloudstorge/php-sdk-master/examples/list_file_music.php)

#### Method: GET

#### Parameter:

|  | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| uuid | true | String | 设备唯一识别码 |

#### JSON示例

```
{
    "data": {
        "data": [
            {
                "key": "Music_iP1433782551978_2754be50-2df4-4d56-bc28-24b8ca4f462f_by_camera (1).mp3",
                "hash": "FiB3Sl0kmo54mAgfwgBf4NKeLGz6",
                "fsize": 267800,
                "mimeType": "auido/mp3",
                "putTime": 14863861846941936,
                "type": 0
            }
        ],
        "marker": "eyJjIjowLCJrIjoiSW1hZ2VfaVAxNDMzNzgyNTUxOTc4XzI3NTRiZTUwLTJkZjQtNGQ1Ni1iYzI4LTI0YjhjYTRmNDYyZl9ieV9jYW1lcmEgKDYpLmpwZyJ9"
    },
    "status": 1,
    "error": 0
}
```

### 1.3文件列表

#### URL:[http://api.fandong.me/api/qiniucloudstorge/php-sdk-master/examples/list\_file.php](http://api.fandong.me/api/qiniucloudstorge/php-sdk-master/examples/list_file.php)

#### Method: GET

#### Parameter:

|  | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| uuid | true | String | 设备唯一识别码 |

#### JSON示例

```
{
    "data": {
        "data": [
            {
                "key": "File_iP1433782551978_2754be50-2df4-4d56-bc28-24b8ca4f462f_by_camera (1).text",
                "hash": "FiB3Sl0kmo54mAgfwgBf4NKeLGz6",
                "fsize": 267800,
                "mimeType": "application/text",
                "putTime": 14863861846941936,
                "type": 0
            }
        ],
        "marker": "eyJjIjowLCJrIjoiSW1hZ2VfaVAxNDMzNzgyNTUxOTc4XzI3NTRiZTUwLTJkZjQtNGQ1Ni1iYzI4LTI0YjhjYTRmNDYyZl9ieV9jYW1lcmEgKDYpLmpwZyJ9"
    },
    "status": 1,
    "error": 0
}
```

### 1.4视频列表

#### URL:[http://api.fandong.me/api/qiniucloudstorge/php-sdk-master/examples/list\_file\_video.php](http://api.fandong.me/api/qiniucloudstorge/php-sdk-master/examples/list_file_video.php)

#### Method: GET

#### Parameter:

|  | 必选 | 类型 | 说明 |
| :--- | :--- | :--- | :--- |
| uuid | true | String | 设备唯一识别码 |

#### JSON示例

```
{
    "data": {
        "data": [
            {
                "key": "Video_iP1433782551978_2754be50-2df4-4d56-bc28-24b8ca4f462f_by_camera (1).mp4",
                "hash": "FiB3Sl0kmo54mAgfwgBf4NKeLGz6",
                "fsize": 267800,
                "mimeType": "video/mp4",
                "putTime": 14863861846941936,
                "type": 0
            }
        ],
        "marker": "eyJjIjowLCJrIjoiSW1hZ2VfaVAxNDMzNzgyNTUxOTc4XzI3NTRiZTUwLTJkZjQtNGQ1Ni1iYzI4LTI0YjhjYTRmNDYyZl9ieV9jYW1lcmEgKDYpLmpwZyJ9"
    },
    "status": 1,
    "error": 0
}
```



