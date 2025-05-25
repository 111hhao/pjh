第14关：ssh -i 命令详解：
ssh -i 命令用于指定 SSH 连接时使用的私钥文件，这是 SSH 密钥认证的核心命令选项。
基本语法：
ssh -i <私钥文件路径> [用户名@]主机名 [命令]
参数说明
-i <私钥文件路径>: 指定用于身份验证的私钥文件
用户名@主机名: 连接的目标用户和主机
命令: 可选，连接后在远程主机上执行的命令
例子：ssh -i sshkey.private bandit14@localhost：
ssh：SSH客户端命令
-i sshkey.private：指定要使用的私钥文件
bandit14@localhost：以bandit14用户身份登录到本地主机
