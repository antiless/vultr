# 3分钟快速安装宝塔面板

最后更新于：2017-12-29

宝塔\(bt.cn\)为国产知名面板程序，可以通过Web界面：一键LAMP/LNMP、创建网站FTP、数据库、SSL；安全管理，计划任务，文件管理，PHP多版本共存及切换，一键开启Tomcat环境等诸多功能。

该面板对新人十分友好，可以在几分钟内完成面板的搭建，本文详细介绍如何安装宝塔面板。

## 1. SSH连接到VPS服务器

如果你不清楚什么是SSH，请先学习《 [ SSH连接到服务器 ](http://t.cn/EfJuie7) 》

## 2. 执行命令安装宝塔面板

CentOS安装命令：

> yum install -y wget && wget -O install.sh [http://download.bt.cn/install/install.sh](http://download.bt.cn/install/install.sh) && sh install.sh

Ubuntu/Deepin安装命令：

> wget -O install.sh [http://download.bt.cn/install/install-ubuntu.sh](http://download.bt.cn/install/install-ubuntu.sh) && sudo bash install.sh

Debian安装命令：

> wget -O install.sh [http://download.bt.cn/install/install-ubuntu.sh](http://download.bt.cn/install/install-ubuntu.sh) && bash install.sh

Fedora安装命令:

> wget -O install.sh [http://download.bt.cn/install/install.sh](http://download.bt.cn/install/install.sh) && bash install.sh

根据提示输入 “y” 或者自定义目录，新手不了解的情况下最好不要动。

等待完成安装过程，出现“安装成功”字样则说明成功安装。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/1504426645_7433.png)

## 3.登录面板后台

根据安装成功的提示信息，使用对应的用户名和密码访问面板后台。通常是 [http://IP:8888/](http://IP:8888/) ，成功登录后可以将用户名和密码进行修改，避免黑客进行攻击。

* 可以在Web面板中实现对系统的监控、管理。在面板设置中可以绑定域名、更改用户名和登录密码等操作。
* 可以一键安装LAMP或者LNMP组件，管理网站，端口设置。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/1504426698_4405.png)

## 4.安装Web运行环境

这里我们以当前最为流程的Web架构进行演示，即LNMP\(Linux + Nginx + MySQL + PHP\)或LAMP\(Linux + Apache + MySQL + PHP\)，这里我们推荐使用LNMP，目前从各方面来看均优于Apache。

稍等几分钟即可完成全部安装，建议使用极速安装，速度快，新手友好。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/zt-pic4.png)

