---
title: 使用shadowscoksR爬坑
---
### 购买服务器 ###
不再赘述,网上一堆介绍的,我购买的是*搬瓦工* 官网:[www.bwh1.net]()
购买完服务器后商家会发来一些列的邮件,里面有你的服务器ip地址,端口号,以及连接服务器的密码.		
就这样子:
![](/Users/yang/Downloads/20180713161244.png)

### 连接连接到服务器	###

1.windows可以下载个XShell 上面要填的就是刚才商家发给你的一些东西.	
2.mac和linux可以直接在终端连接	例如:`ssh -p 231307 root@186.155.121.111`
连接成功后是这样子:		
![](/Users/yang/Downloads/20180713162446.png)

### 安装ssr ###
都比根据地提供的一键傻瓜式安装:
1.`wget -N --no-check-certificate https://softs.fun/Bash/ssr.sh && chmod +x ssr.sh && bash ssr.sh`
备用下载地址（上面的链接无法下载，就用这个):`wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh`

*如果提示:wegt command not found 执行`yum -y install wget`安装一下*

### 连接 ###
安装完ssr后会提供给你连接地址![](/Users/yang/Downloads/20180713163549.png)
下载个shadowsocks客户端就可以愉快的玩耍了		
mac:链接:[https://pan.baidu.com/s/1xyKVKAjf1Uj5nw5DFEOtdA]()  密码:r4bh		
win:链接:[https://pan.baidu.com/s/1ZEmZRn846w7kHdGV3HFA6g]()  密码:thb4