第17关：
1、Nmap（Network Mapper）是一个开源的网络探测和安全审计工具，由Gordon Lyon（也称为Fyodor）创建。它被网络管理员、系统管理员和安全专业人员广泛用于：
网络发现（找出网络上的主机）
端口扫描（确定开放的端口）
服务识别（确定运行的服务及其版本）
操作系统检测（确定目标系统的操作系统）
脚本扫描（使用NSE脚本进行更深入的分析）
Nmap可以在Linux、Windows、macOS等多种操作系统上运行，并提供命令行和图形界面（Zenmap）两种使用方式。
基本语法：nmap [扫描类型] [选项] {目标规范}

2、使用ssh-keygen
ssh-keygen是生成SSH密钥对的标准工具，可在Linux、macOS和Windows（通过Git Bash或WSL）上使用
基本用法：
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
这个命令会生成一个4096位的RSA密钥对，并添加一个注释（通常是电子邮件地址）