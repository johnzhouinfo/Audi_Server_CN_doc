
 - HTTP请求头说明


|参数名|值|是否有值|说明|
|:-------|:----:|:-:|-----|
|Platform    |是 | 登录平台     1：奥迪平台  |1 |
|X-User-Agent  |否 | 客户端类型/客户端系统版本/设备型号 |ios/8.1/iPhone 7 Plus  |
|Access-Token|否 |访问接口携带令牌，用于判别身份,除部分接口外，请全部携带|eyJhbGciOiJIUzUxMiJ9.eyJqdGkiOiI4MzI0Y2MyYi01NDBkLTQxNTMtOGM1YS1lM2U5ODIyNDU2MzAiLC <br>JzdWIiOiIyMDAwMDI5IiwiaXNzIjoiaHR0cDovL2Nsb3VkLnZpdmFjaGUuY291tLmNuIiwiaWF0Ij  <br>oxNTY1N1zcxODQyLCJleHAiOjE1NjU3NzkwNDJ9.NXjvNY7U158hGtqm9U5he6S-mqGFr_6suUFW3rpv-<br>pMjeZCDx42mIDMOJAajlCJji01FxuVCkBBtKbWWB1CD3Vw|
|Refresh-Token|否 |用于获取Access_Token，仅在获取token接口中使用|eyJhbGciOiJIUzUxMiJ9.eyJqdGkiOiI4MzI0Y2MyYi01NDBkLTQxNTMtOG<br>M1YS1lM2U5ODIyNDU2MzAiLCJzdWIiOiIyMDA<br>wMDI5IiwiaXNzIjoiaHR0cDovL2Nsb3VkLnZpdmFjaGUuY29tLmNuIiwiaW1F0IjoxNTY1ODQ<br>0MzY4LC1JleHAiOjE1Njg0MzYzNjh9.FYmYd9zoXLImV5HybgKRmOiYnSwMXSMT1cyw3YerAe2FrKAKmwphK<br>6mg9iFHctK1MAWy_pS0eb9bLeKGAsk_2g |


平台编码说明

|编码|说明|
|:-------|-----|
|1|奥迪平台|


X-User-Agent  设置说明

| 客户端类型| 内容 |说明|
|:-------|:----:|-----|
|ios|ios/10.1/Iphone7 PLUS|ios/ios系统版本号/手机型号|
|android|android/10.1/Redmi 3|android/android系统版本号/手机型号|
|wechat|wechat/4.4; ios/4.5/Redmi 3|wechat/微信版本号; ios或者android/android或者ios系统版本/手机型号|
