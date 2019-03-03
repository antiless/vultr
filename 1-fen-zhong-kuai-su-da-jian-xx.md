---
description: 快速搭建 SS 服务
---

# 1 分钟快速搭建 Shadowsocks

> ### 前提
>
> 你已经根据 [通过SSH管理服务器](http://t.cn/EfJuie7) 的步骤连接上服务器

**搭建服务 三步走**

1 . 安装 在CentOS中运行下面两条命令就完成了shadowsocks的安装了：

```text
yum install python-setuptools && easy_install pip
pip install shadowsocks
```

2 . 配置 完成之后创建一个配置文件 /etc/shadowsocks.json，写入以下内容：

```text
{ 
        "server":"0.0.0.0",            #服务器IP地址
        "server_port":8388,                 #服务监听端口
        "local_port":1080,                  #本地连接端口
        "password":"barfoo",               #加密传输使用到的密码
        "timeout":600,                      #连接超时时间
        "method":"aes-256-cfb"             #加密算法
}
```

3 . 启动、停止 运行下面的命令来启动和停止后台服务：

```text
ssserver -c /etc/shadowsocks.json -d start
ssserver -c /etc/shadowsocks.json -d stop
```

**然后你就可以使用上面的配置连接shadowsocks了。**

1. 客户端如何用？

各个平台使用的客户端都有差异，但是用到的信息就这些： － 服务器IP: 不是上面的0.0.0.0，是你申请的VPS，会提供一个ip。打开网站，登录，找到它 － 端口\(port\): 8388 － 协议类型: aes-256-cfb 一般默认就这个，不用换。但还是要看一眼。 － 密码\(password\): barfoo 连接，欢呼。

