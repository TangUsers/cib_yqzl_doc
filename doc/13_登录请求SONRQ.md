1. ### <a name="_toc496253755"></a>登录请求SONRQ

|标记|说明|备注|
| :-: | :-: | :-: |
|`<SONRQ>`|登录请求消息||
|`<DTCLIENT/>`|客户端日期时间，YYYY-MM-DD_HH:MM:SS|必输(“_”表示空格)|
|  `<CID/>`|企业网银客户号，10位数字字符|必输|
|  `<USERID/>`|登录用户名，最长：20位|必输|
|  `<USERPASS/>`|登录密码，最长：30位|<p>必输</p><p>提供登录密码采用明文和密文两种方式，两者兼容；如果采用密文方式，需使用银行提供的加密包cibFoxDesUtil.jar</p>|
|  `<USERKEY/>`|<p>USERKEY与(USERID和USERPASS)不同时出现，</p><p>由服务器在上一次请求响应中提供，建议使用(USERID和USERPASS)</p>|必输|
|  `<GENUSERKEY/>`|是否需要服务器产生USERKEY,，填Y、N|必输|
|  `<LANGUAGE/>`|希望服务器响应信息使用的语言，目前仅支持CHS(中文简体) |非必输|
|  `<APPID/>`|客户端应用程序编码，五个字符|非必输|
|  `<APPVER/>`|客户端应用程序版本nnnn |非必输|
|`</SONRQ>`|||
