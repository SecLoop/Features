GET / HTTP/1.1
Host: oa.xxxxx.com
Cache-Control: max-age=0
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/75.0.3770.90 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Cookie: rememberMe=1			
Connection: close




HTTP/1.1 302 Found
Date: Thu, 22 Aug 2019 03:19:02 GMT
Content-Length: 0
Connection: close
Set-Cookie: acw_tc=2f624a3e15664439421161501e2038aacfcaa7472c857547507ea89dbc2129;path=/;HttpOnly;Max-Age=2678401
Set-Cookie: rememberMe=deleteMe; Path=/; Max-Age=0; Expires=Wed, 21-Aug-2019 03:19:02 GMT
Set-Cookie: sessionid=8eb47974-c142-4beb-82e6-b923559a036e; Path=/; HttpOnly


//将请求包的Cookie的值修改为rememberMe=1,观察返回包是否有rememberMe字段，如果有就可以判断使用了Shiro组件。或者请求头自带rememberMe

Shiro 在 Java 的权限及安全验证框架中占用重要的一席之地

//利用方式(反序列化,一般使用的默认密钥)
