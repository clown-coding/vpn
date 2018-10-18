
# 优惠购买搬瓦工

搬瓦工VPS相对其它的云服务产商来说，性价比高，使用起来速度快。通过优惠码购买还能再降低最多 %6 的一些费用。目前[搬瓦工官网](https://bwh8.net/aff.php?aff=32874)最低的有 $19.99 / 年，在这基础上使用优惠码可以少一些费用，根据你对配置的需要进行选择服务器，对于个人来说，19刀的服务器就够用了，以下是可以获取优惠码的链接：

| 搬瓦工配置 | 搬瓦工费用 | 优惠链接|
| ------ | ------ | ------ |
|*10G KVM – PROMO* <br>  SSD硬盘: 10 GB RAID-10 <br> RAM内存: 512 MB <br> CPU处理器: 1x Intel Xeon <br> Transfer流量: 500 GB/月 <br> 连接速度: 1 Gigabit <br> Multiple locations | $19.99/年 | [点击进入](https://www.bwh8.net/aff.php?aff=32874&pid=43) |
| *20G KVM – PROMO* <br> SSD硬盘: 20 GB RAID-10 <br>RAM内存: 1024 MB <br>CPU处理器: 2x Intel Xeon <br>Transfer流量: 1 TB/mo <br>连接速度: 1 Gigabit <br>Multiple locations| $49.99/年 | [点击进入](https://www.bwh8.net/aff.php?aff=32874&pid=44)|
| *40G KVM – PROMO* <br> SSD硬盘: 40 GB RAID-10 <br>RAM内存: 2 GB <br>CPU处理器: 3x Intel Xeon <br>Transfer流量: 2 TB/mo <br>连接速度: 1 Gigabit <br>Multiple locations| $99.99/年 | [点击进入](https://www.bwh8.net/aff.php?aff=32874&pid=45) |
| *80G KVM – PROMO* <br> SSD硬盘: 80 GB RAID-10<br>RAM内存: 4 GB<br>CPU处理器: 4x Intel Xeon<br>Transfer流量: 3 TB/mo<br>连接速度: 1 Gigabit<br>Multiple locations| $19.99/月  | [点击进入](https://www.bwh8.net/aff.php?aff=32874&pid=46) |
| *160G KVM – PROMO* <br> SSD硬盘: 160 GB RAID-10<br>RAM内存: 8 GB<br>CPU处理器: 5x Intel Xeon<br>Transfer流量: 4 TB/mo<br>连接速度: 1 Gigabit<br>Multiple locations| $39.99/月 | [点击进入](https://www.bwh8.net/aff.php?aff=32874&pid=47) |
| *3200G KVM – PROMO* <br> SSD硬盘: 320 GB RAID-10<br>RAM内存: 16 GB<br>CPU处理器: 6x Intel Xeon<br>Transfer流量: 5 TB/mo<br>连接速度: 1 Gigabit<br>Multiple locations| $79.99/月 | [点击进入](https://www.bwh8.net/aff.php?aff=32874&pid=48) |

进入之后就可以获取优惠码了，选择完之后**不要急着点击 「Add to Cart」**。

这时候就可以获取隐藏的优惠码了，我们对着这个网页：`鼠标右击-->查看网页源代码`。

接着 `Ctrl + F` 搜索 `code` ，这时候你就会看到 `Try this promo code: xxxx`，这里的`xxxx`就是优惠吗，把它复制下来。

![搬瓦工vps](http://owx1uvd7t.bkt.clouddn.com/banwagong04.png)


页面的 Location 就是选择服务器的地址，到时访问谷歌的时候会显示你当前访问的地址。好了，我们点击「Add to Cart」。

接下来，进入结算页面，我们刚才复制的优惠码就派上用场了，将你刚刚复制的优惠码复制进去然后点击 「Validate Code」，看！是不是优惠了！一般人不知道这种操作:

![搬瓦工优惠码](http://owx1uvd7t.bkt.clouddn.com/vpn5.png)

接着点击「CheckOut」完成付款即可。付款的时候选择 Alipay 就可以使用支付宝付款。

![搬瓦工支付宝支付](http://owx1uvd7t.bkt.clouddn.com/vpn8.png)



# 获取搬瓦工服务器的ip，端口，账号密码

购买完毕后你就拥有一台你自己的服务器了，接着点击Services下的MyServices，可以看到你的服务器：

![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/vpn6.png)

我们点击「KiwiVM Control Panel」进入管理界面：

![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/vpn7.png)

可以看到你服务器的信息:

![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/vpn9.png)

有了<a href="https://bwh1.net/aff.php?aff=32874" target="_blank">搬瓦工</a>服务器的IP地址和端口,我们就可以连接了：

![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/pic1.png)

账号是root，密码可以在这里获取：

![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/pic2.png)

# 使用 SSH 工具连接到搬瓦工服务器

![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/pic3.png)

远程连接工具我一直用的是 [SecureCRT](https://www.vandyke.com/products/securecrt/) , 当然你也可以使用其它的 SSH 工具。
破解版的SecureCRT可以在百度网盘这里获取：

- 链接: https://pan.baidu.com/s/11W4WHjCjmiNw6einQNrcPg
- 提取码: tyux

# 开始快读搭建ss服务器


## 安装 wget ：

    yum install wget

## 执行安装ss：

    wget –no-check-certificate -O shadowsocks.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh

## 获取shadowsocks.sh读取权限

    chmod +x shadowsocks.sh

## 设置ss密码端口和加密方式

当你输入`chmod +x shadowsocks.sh`后就可以设置密码和端口号了：
![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/ss1.png)
设置完密码和端口号之后，我们选择加密方式，这里选择 7：
![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/ss2.png)
接着按任意键进行安装。

## 安装ss完成

等一会之后，就安装完成了，它会给你显示你需要连接vpn的信息：

![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/ss3.png)

可以看到需要连接ss的ip地址，密码，端口，和加密方式。

将这些信息保存起来，那么这时候你就可以使用它们来科学上网啦。

# 使用Shadowsocks

打开 Shadowsocks 客户端，输入ip地址，密码，端口，和加密方式。接着点击确定，右下角会有个小飞机按钮，右键-->启动代理。

![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/ss4.png)

这时候就可以科学上网了。

访问以下 Youtube 和 Google 试试看，速度还可以的：
![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/ss5.png)
![搬瓦工搭建ss](http://owx1uvd7t.bkt.clouddn.com/ss6.png)


# 使用BBR加速器

让访问速度加速，飞起来！使用 BBR 加速工具。

## 安装 BBR

    wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh

## 获取读写权限

    chmod +x bbr.sh

## 启动BBR安装

    ./bbr.sh

接着按任意键，开始安装，坐等一会。安装完成一会之后它会提示我们是否重新启动vps，我们输入 y 确定重启服务器。

重新启动之后，输入 `lsmod | grep bbr` 如果看到 tcp_bbr 就说明 BBR 已经启动了。

再访问一下 Youtube，1080p 超高清，很顺畅不卡顿！

![搬瓦工搭建ss](http://owh7v964r.bkt.clouddn.com/ss7.png)


# 相关文章

- [购买搬瓦工VPS省钱攻略：获取搬瓦工优惠码](https://www.wistbean.com/banwagong-coupon.html)
- [使用搬瓦工快速搭建自己的VPN](https://www.wistbean.com/banwagong-vpn.html)
- [CentOS快速搭建一个属于自己的IPsec/L2TP VPN](https://www.wistbean.com/ipsec,l2tp_vpn.html)


