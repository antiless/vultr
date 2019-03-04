# 通过SSH管理服务器

最后更新于：2018-01-01

在这篇文章中，我们演示开通VPS主机之后，获取需要的远程登入账户信息，利用SSH客户端，从而对Linux服务器进行管理的过程。

 **1.前期准备工作** 

请先参照 [ 《图文购买教程》 ](https://vultr.gitbook.io/docs/shou-ba-shou-tu-wen-gou-mai-jiao-cheng) ，购买合适的VPS，并获取到当前VPS信息。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_ssh_1.jpg)

这里我们可以看到当前服务器的IP、ROOT密码（点击箭头的眼睛图标可以看到）。然后我们通过相关的SSH工具管理服务器。

**2.Windows用户登录VPS**

推荐使用XShell，请安装最新版本。XShell官网下载：

[http://www.netsarang.com/products/xsh\_overview.html](http://www.netsarang.com/products/xsh_overview.html)

下载需要填个邮箱，然后它会把下载链接发到邮箱。按照要求安装成功后运行XShell，新建连接即可。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_ssh_2.jpg)

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_ssh_3.jpg)

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_ssh_4.jpg)

这里我们可以登入进来。直接在这个界面输入命令安装系统或者安装其他工具都可以。

 **2.Linux用户登录VPS** 

打开终端，输入命令：

> ssh -p 端口号 用户名@IP地址

如：

> ssh -p 25636 root@188.155.133.111

接着按照提示输入密码即可。

 **3.Mac用户登录VPS** 

可以打开终端进行登录，方法同Linux用户；也可以安装SSH客户端，如shuttle等。

 **4.手机登录VPS** 

下载一个SSH客户端，安卓用户可以安装JuiceSSH，iPhone用户可以安装iTerminal等等。

