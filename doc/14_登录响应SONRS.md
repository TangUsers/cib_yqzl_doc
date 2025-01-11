1. ### <a name="_toc496253756"></a><a name="_toc268791599"></a><a name="_toc269981765"></a><a name="_toc239043660"></a>登录响应SONRS 

   |标记|说明|备注|
   | :-: | :-: | :-: |
   |<SONRS>|登录响应消息||
   |<p><STATUS></p><p>`      `<CODE/></p><p>`      `<SEVERITY/></p><p>`      `<MESSAGE/></p><p>`   `</STATUS></p>|<p>交易处理状态</p><p>处理结果码</p><p>处理结果等级(INFO/WARN/ERROR)</p><p>信息描述</p>|必回|
   |<DTSERVER/>|服务端日期时间，YYYY-MM-DD HH:MM:SS|必回|
   |<p><USERKEY/></p><p><TSKEYEXPIRE/></p>|<p>客户端要求生成USERKEY时发送key值</p><p>USERKEY的有效时间(服务器时间) </p>|非必回，仅在GENUSERKEY为”Y”时必回|
   |<LANGUAGE/>|服务器响应信息使用的语言，目前仅提供CHS(中文简体)，可选|非必回|
   |<SESSCOOKIE/>|服务器需要保存会话COOKIE，则发送，否则不发送，客户端在下次请求中应包含|非必回|
   |</SONRS>|||
