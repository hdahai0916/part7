# part4

- ##### HTTP 是什么？解决了什么问题？
http是一种数据通信协议。解决了不同系统之间资源传输的问题。
- ##### 请你对常见的状态码进行了解并进行总结
1xx：信息，继续。
2xx：成功。
3xx：重定向或缓存。
4xx：客户端错，通常是请求方问题。
5xx：服务器错，通常是服务端或上游问题。

## task1
![1](./image/1.png)
- ##### 请求使用的 Method 是什么？
GET
- ##### 请求 Header 中有哪些信息？
Host：服务器域名
Accept：客户端可以接收的文件类型。
Accept-Encoding：客户端支持的压缩算法
Accept-Language：客户端偏好的语言
Connection：是否保持tcp连接
Cookie：服务器给的，用来识别身份和跟踪会话。
User-Agent：客户端浏览器类型。
- ##### 服务器返回了什么内容？
![2](./image/2.png)
![3](./image/3.png)
返回了响应头和响应体。
响应头里有响应的相关信息，比如`Content-Type`内容的格式，`Set-Cookie`服务器设置的cookie。
响应体里是html文件。
- ##### 一次 HTTP 请求通常包含哪些部分？分别有什么作用？
- #####


