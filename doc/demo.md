# 经典对联

经典中华文化对联句子

## 接口文档

接口地址： `https://apis.xxx.com/duilian/index`

返回格式： JSON

请求方式： GET

请求示例：`https://apis.xxx.com/duilian/index`

接口备注：无

## 请求参数：

| 参数 | 类型   | 必填 | 说明    |
| ---- | ------ | ---- | ------ |
| key  | string | 是   | APIKEY |


## 返回参数说明：

| 参数   | 类型   | 类型    | 说明       |
| ------ | ------ | ------- | ---------- |
| code   | int    | 200     | 状态码     |
| msg    | string | success | 错误信息   |
| result | object | {}      | 返回结果集 |
|content |string| 风声雨声读书声声声入耳，家事国事天下事事事关心|对联内容|


## 返回示例：

### JSON返回示例


```json
{
  "code": 200,
  "msg": "success",
  "result": {
    "content": "风声雨声读书声声声入耳，家事国事天下事事事关心"
  }
}
```

