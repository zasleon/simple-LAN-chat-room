# simple-LAN-chat-room

局域网 聊天室 C++ VC6.0 simple LAN chat room 分为服务器、客户端 2020.10.13 添加检测服务器负荷超载功能（可调整memberlimit改变服务器自定义负荷上限量）

服务器不断接收新客户端发来的请求并建立连接（没达到服务器负荷上限前），达到负荷上限后忽略后来的客户端请求，直到连接人数下降。

打开dsw就能打开工作区间

打开里层目录exe就能直接运行

只有服务器能显示不同客户端发来的消息，客户端之间互发消息（需要服务器进行转接）功能尚未实现
