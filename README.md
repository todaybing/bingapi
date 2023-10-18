# 必应壁纸 API接口文档 bingapi

必应壁纸api,提供全量的必应壁纸接口数据。

## 接口提供方官网
https://www.todaybing.com/

## Api Endpoint
https://www.todaybing.com/api/v2

## 全球必应壁纸feeds
---
#### 接口说明

| URL | request | version | status |
| :--- | :--- | :--- | :--- |
| [https://www.todaybing.com/api/feeds](https://www.todaybing.com/api/feeds) | GET | 1.0 | true |

#### 接口返回示例

``` 
{"code":200,"data":[{"articleUrl":"https:\/\/www.todaybing.com\/detail\/Cq0vB5TP.html","area":"cn","image":"https:\/\/imgs.todaybing.com\/334815de06e0584ef7467b3d707e86d7.jpg","copyright":"\u00a9 Ian Shive","title":"\u79d1\u8fea\u4e9a\u514b\u56fd\u5bb6\u91ce\u751f\u52a8\u7269\u4fdd\u62a4\u533a\uff0c\u79d1\u8fea\u4e9a\u514b\u5c9b\uff0c\u963f\u62c9\u65af\u52a0\u5dde\uff0c\u7f8e\u56fd ","date":"2023-10-18"},{"articleUrl":"https:\/\/www.todaybing.com\/global\/au3DTZyp20.html","area":"au","image":"https:\/\/imgs.todaybing.com\/8988029f615ecbbed6f82c1c4aeb1408.jpg","copyright":"\u00a9 Ian Shive","title":"Kodiak National Wildlife Refuge","date":"2023-10-19"},{"articleUrl":"https:\/\/www.todaybing.com\/global\/jpF8Y0SeNb.html","area":"jp","image":"https:\/\/imgs.todaybing.com\/8c6c42bd302508be596007cc92e8ba75.jpg","copyright":"\u00a9 Ian Shive","title":"\u30b3\u30c7\u30a3\u30a2\u30c3\u30af\u56fd\u7acb\u91ce\u751f\u751f\u7269\u4fdd\u8b77\u533a","date":"2023-10-18"},{"articleUrl":"https:\/\/www.todaybing.com\/global\/de5YVUQiGR.html","area":"de","image":"https:\/\/imgs.todaybing.com\/94c5a698c6d56581e6ba25d05791e43d.jpg","copyright":"\u00a9 Ian Shive","title":"Kodiak National Wildlife Refuge","date":"2023-10-18"},{"articleUrl":"https:\/\/www.todaybing.com\/global\/frVaRpFMG7.html","area":"fr","image":"https:\/\/imgs.todaybing.com\/174c33cc4d91fbc359e8b461f10992e3.jpg","copyright":"\u00a9 Ian Shive","title":"Refuge faunique national de Kodiak","date":"2023-10-18"},{"articleUrl":"https:\/\/www.todaybing.com\/global\/caREzbEiHv.html","area":"ca","image":"https:\/\/imgs.todaybing.com\/b8daed18e35f23a5aec25f609dbb8435.jpg","copyright":"\u00a9 Ian Shive","title":"Kodiak National Wildlife Refuge","date":"2023-10-19"},{"articleUrl":"https:\/\/www.todaybing.com\/global\/gbtFt80RkS.html","area":"gb","image":"https:\/\/imgs.todaybing.com\/ad6d36515ed3107727d25555f2e9ca25.jpg","copyright":"\u00a9 AWL Images","title":"Canary Wharf underground station","date":"2023-10-18"},{"articleUrl":"https:\/\/www.todaybing.com\/global\/inFSnrG3SA.html","area":"in","image":"https:\/\/imgs.todaybing.com\/fcad76fbed4092d980233de4aed08c54.jpg","copyright":"\u00a9 Ian Shive","title":"Kodiak National Wildlife Refuge","date":"2023-10-18"},{"articleUrl":"https:\/\/www.todaybing.com\/global\/us373y4THj.html","area":"us","image":"https:\/\/imgs.todaybing.com\/dba259bbff0edcde3f04d5be0c853844.jpg","copyright":"\u00a9 Ian Shive","title":"Kodiak National Wildlife Refuge","date":"2023-10-19"}],"copyright":"COPYRIGHT \u00a9 2021 www.todaybing.com and its suppliers. All rights reserved."}

```

---


#### 接口详细说明 

``` 
返回全球必应元数据 feeds,包含壁纸数据
```

---

## 今日全球壁纸
---
#### 接口说明

| URL | request | version | status |
| :--- | :--- | :--- | :--- |
| [https://www.todaybing.com/api/today/{$area}](https://www.todaybing.com/api/today/{$area}) | GET | 1.0 | true |


#### 请求参数说明

| 请求参数 | 类型 | 必填 | 参数说明 | 示例 |
| :--- | :--- | :--- | :--- | :--- |
| cn | String | true | 1:返回必应壁纸中国区当日高清壁纸 |[https://www.todaybing.com/api/today/cn](https://www.todaybing.com/api/today/cn) |
| de | String | true | 1:返回必应壁纸德国区当日高清壁纸 |[https://www.todaybing.com/api/today/de](https://www.todaybing.com/api/today/de) |
| fr | String | true | 1:返回必应壁纸法国区当日高清壁纸 |[https://www.todaybing.com/api/today/fr](https://www.todaybing.com/api/today/fr) |
| in | String | true | 1:返回必应壁纸印度区当日高清壁纸 |[https://www.todaybing.com/api/today/in](https://www.todaybing.com/api/today/in) |
| jp | String | true | 1:返回必应壁纸日本区当日高清壁纸 |[https://www.todaybing.com/api/today/jp](https://www.todaybing.com/api/today/jp) |
| gb | String | true | 1:返回必应壁纸英国区当日高清壁纸 |[https://www.todaybing.com/api/today/gb](https://www.todaybing.com/api/today/gb) |
| en | String | true | 1:返回必应壁纸国际区当日高清壁纸 |[https://www.todaybing.com/api/today/en](https://www.todaybing.com/api/today/en) |



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










