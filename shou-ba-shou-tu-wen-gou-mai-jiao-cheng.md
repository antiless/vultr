# \[手把手\] Vultr 图文购买教程

最后更新于：2018-01-20

本节我们详细讲解如何购买Vultr主机，整个流程下来你会对购买国外VPS有一个基本认识，之后购买其他VPS流程也是类似的。

**需要注意的一点是：我们一定要自己注册帐号， 千万不要找人代购 ，因为代购存在很大的风险，VPS可能被植入后门程序，十分危险，而且被主机商发现会被封号处理。** 

注册注册 [ Vultr ](http://t.cn/EfPiJLF) 账户还是很简单的，基本上3-5分钟就可以搞定。下面就给大家详细讲解 [ Vultr ](http://t.cn/EfPiJLF) 的购买流程。

## 1.注册Vultr账号

打开 [ Vultr官网 ](http://t.cn/EfPiJLF) ，输入邮箱和密码，点击“Create Account” 即可。 ![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen1.png)

## 2.账户激活

新用户注册后就自动跳转到充值页面，如下图所示。可选择不同的充值方式，我们推荐使用支付宝，当然信用卡、Paypal、比特币也是OK的。

注意：Vultr为避免帐号滥用，帐号在使用前需要进行激活，激活条件是： **最低充值10美元** 。10美元买$2.5可以用4个月，没有时间限制，条件不算苛刻。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen2-1.png)

点击Pay with Alipay后，跳转到支付宝的付款页面，又是熟悉的画面，自动换成人民币完成充值。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen3.png)

##  **3.创建VPS服务器实例**  

点击左侧菜单的Servers，进入创建VPS界面，或者在任意页面直接点击右侧+号，进入创建VPS界面。可见下面两张图的提示。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen4-1.png)

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen5.png)

## **3.1选择节点位置**

目前我们首选日本直连机房，其次是美国西海岸的机房（加州和洛杉矶）。

因为东京节点离我们物理距离较近，而且是中国直连线路，整体效果优秀。Ping值也好些，ping值大概在80~120ms左右波动。

因此本节我们以东京节点为例。详细的机房介绍可以到 [ 《机房测速》 ](http://t.cn/EfJuLad) 一节里仔细阅读。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen6-2.png)

## **3.2选择操作系统**

Vultr基本覆盖了几乎所有主流操作系统，包括Linux、Windows\(需支付正版费用，十分贵\)。同时还提供了自定义ISO安装，可谓业界良心。但正常Windows镜像无法在Vultr安装，这点需要注意。

（想免费安装Windows版本？加入我们2000人QQ群，立即安装！群号：）

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen7.png)

## **3.3选择套餐**

根据CPU核数、内存、流量的不同，我们可以选择多个方案，这些都根据需求的用途决定的，后期我们也可以进行项目方案的升级。

当前$套餐经常断货，能不能刷出来完全靠运气，可以先买一个2.5套餐经常断货，能不能刷出来完全靠运气，可以先买一个$5的先玩玩，后续有新上货信息，我们也会在2000人QQ群第一时间同步给大家。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen8.png)

## **3.4其他选项**

有IPv6，自动备份，DDoS防护，机器标签等，大家可以按需要选择。

建议开启IPv6就OK了，其余的初级玩家不用开启。另外DDoS防护是区分机房的，美国本土机房基本都有这个选项，日本的没有。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen9.png)

## **3.5** **Deploy Now**

**点击“** **Deploy Now** **” 进行安装 VPS服务器，通常一两分钟就能完成整个VPS服务器的创建，请耐心等待。**

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen10.png)

## **4. 查看服务器信息**

**安装好后可以进入信息面板，点击Server Details。如果服务器显示Installing状态，则代表安装中，请等待一下，如看到Runing就可以使用。**

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen11.png)

可以看到有 IP，用户名root，密码\(点击查看按钮或复制按钮\)等信息，恭喜你，VPS就已经购买成功了。

![](https://www.vultrgo.com/wp-content/uploads/2017/12/vultr_tuwen12.png)

那么如何连接和管理我们的服务器呢？请见下一节： [ 《SSH连接到服务器》 ](http://t.cn/EfJuie7)

