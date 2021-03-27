# Demo
# 实践题
用C++实现一个服务程序（就叫calcserver），要求如下：
* calcserver从客户端接收两个int，计算和，并返回给客户端（返回的和也是int)。
* 一个客户端连接上来后，进行若干多次请求，然后断开连接。
* calcserver最少支持10000个客户端同时工作，并且能在毫秒级处理请求，返回结果。
* calcserver支持用-p指定监听端口号；使用TCP连接。
* calcserver每隔10秒输出统计信息：当前连接数，这10秒内平均每秒处理的次数。
* 在主流笔记本上运行，4 core 8 thread, 8G memory.