# 必应壁纸 API接口文档 bingapi

必应壁纸api,提供全量的必应壁纸接口数据。

## 接口提供方官网
https://www.todaybing.com/

## Api Endpoint
https://www.todaybing.com/api/v2
## 今日全球壁纸
---
#### 接口说明

| URL | request | version | status |
| :--- | :--- | :--- | :--- |
| [https://www.todaybing.com/api/today/{$area}](https://www.todaybing.com/api/today/{$area}) | GET | 1.0 | true |

#### 请求参数说明

| 请求参数 | 类型 | 必填 | 参数说明 | 示例 |
| :--- | :--- | :--- | :--- | :--- |
| cn | String | true | 1:返回必应壁纸中国区当日高清壁纸 |[1](https://www.todaybing.com/api/today/cn) |
| de | String | true | 1:返回必应壁纸德国区当日高清壁纸 |
| fr | String | true | 1:返回必应壁纸法国区当日高清壁纸 |
| in | String | true | 1:返回必应壁纸印度区当日高清壁纸 |
| jp | String | true | 1:返回必应壁纸日本区当日高清壁纸 |
| gb | String | true | 1:返回必应壁纸英国区当日高清壁纸 |
| en | String | true | 1:返回必应壁纸国际区当日高清壁纸 |



#### 返回参数说明

| 返回参数 | 参数类型 | 参数说明 |
| :--- | :--- | :--- |
| status | Integer | 200：成功|
| ... | ... | ... |

#### 接口详细说明 

``` 
特别说明描述

```

---

#### 备注
``` 
关于其它错误返回值与错误代码，参见 [Code码说明](#Link)

```
---

## 获取今日壁纸数据
---
#### 接口说明

| URL | request | version | status |
| :--- | :--- | :--- | :--- |
| [https://www.todaybing.com/api/v2](https://www.todaybing.com/api/v2) | POST/GET | 1.0 | true |

#### 请求参数说明

| 请求参数 | 类型 | 必填 | 参数说明 | 示例 |
| :--- | :--- | :--- | :--- | :--- |
| type | String | true | 1:请求今日壁纸详情 2:请求直接返回今日壁纸 |1 |

#### 返回参数说明

| 返回参数 | 参数类型 | 参数说明 |
| :--- | :--- | :--- |
| status | Integer | 200：成功|
| ... | ... | ... |

#### 返回示例JSON

```json
{
    "status": 200,
    "msg":"ok",
    "data": {
        "date": "20210101",
        
    }
}
```

#### code码说明

| code | msg | desc |
| :--- | :--- | :--- |
| 200 | success |  |

#### 接口详细说明 

``` 
特别说明描述

```

---

#### 备注
``` 
关于其它错误返回值与错误代码，参见 [Code码说明](#Link)

```
---
#### Author

| Coder   | 创建时间 | 更新时间 |联系方式 |
| :---     | :---| :--- | :--- |
| todaybing  | 2021.1.15 |2022.06.06  |admin@todaybing.com  |










