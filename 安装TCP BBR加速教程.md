#  安装TCP BBR加速教程

最后更新于：2017-12-30

Google BBR是一个TCP加速优化工具，可以起到单边加速 TCP 连接的效果，也就是不用客户端的配合，从 4.9 开始，Linux
内核已经用上了该算法。我们可以应用到常规的KVM和XEN架构的VPS、服务器中，用来提升服务器的网络速度。

由于要修改Linux内核，所以建议我们使用在一些非生产环境中的项目，比如搭建的某软件工具据说有可以较大的提高速度。

**1.预先准备工作**

  * 鉴于内核的修改不确定性，如果有其他重要数据的，建议备份。 

**2.一键安装BBR工具**

这里参考一键安装BBR脚本进行安装，该脚本已在  **Vultr 上的 VPS 全部测试通过** ，支持CentOS 6+，Debian 7+，Ubuntu
12+系统。

(1)使用root用户登录，运行以下命令：

> wget –no-check-certificate
https://github.com/teddysun/across/raw/master/bbr.sh  && chmod +x bbr.sh &&
./bbr.sh

安装完成后，脚本会提示需要重启 VPS，输入 y 并回车后重启。

(2)重启完成后，进入 VPS，验证一下是否成功安装最新内核并开启 TCP BBR。

输入命令：

> sysctl net.ipv4.tcp_available_congestion_control

返回值一般为：  
net.ipv4.tcp_available_congestion_control = **bbr cubic reno** 说明BBR已完成安装

输入命令：

> lsmod | grep bbr

返回值有 tcp_bbr 模块即说明 BBR已启动。

