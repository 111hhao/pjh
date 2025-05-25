第十五关：
在Linux中，可以使用多种工具与网络服务进行通信：
telnet：一种早期的网络协议，用于通过网络提供双向交互式文本通信
nc（netcat）：一个功能强大的网络工具，被称为"网络的瑞士军刀"
curl：用于传输数据的命令行工具
nc localhost 30000：
nc：netcat命令
localhost：目标主机（本地主机）
30000：目标端口
echo "4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e" | nc localhost 30000：
echo "4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e"：输出密码
|：管道操作符，将echo命令的输出作为nc命令的输入
nc localhost 30000：连接到本地主机的30000端口
第16关：
openssl s_client 是 OpenSSL 工具包中的一个强大命令行工具，用于建立 SSL/TLS 客户端连接。它允许用户连接到 SSL/TLS 服务器，显示证书信息，并与服务器交互。
基本语法：openssl s_client -connect 主机名:端口 [选项]
事例：
openssl s_client -connect localhost:30001：
openssl：OpenSSL命令行工具
s_client：用于创建SSL/TLS客户端连接的子命令
-connect localhost:30001：指定要连接的主机和端口
echo "BfMYroe26WYalil77FoDi9qh59eK5xNr" | openssl s_client -connect localhost:30001 -quiet：
echo "BfMYroe26WYalil77FoDi9qh59eK5xNr"：输出密码
|：管道操作符，将echo命令的输出作为openssl命令的输入
-quiet：减少输出信息，只显示必要的内容