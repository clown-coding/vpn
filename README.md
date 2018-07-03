

## 1.使用搬瓦工搭建自己的VPN

很多人想要使用 VPN ，不过去购买第三方的「VPN账号」除了不稳定外还怕不安全，有些第三方 VPN 会获取用户的数据做一些坏事，还特么限制网速，不能忍！

所以想要自己买一台服务器，然后搭建一个完全属于自己的 VPN ，稳定快速又安全！

那么就在这里教大家使用<a href="https://bwh1.net/aff.php?aff=32874" target="_blank">搬瓦工官网</a>（性价比很高的云服务器提供商）来快速的搭建自己的VPN。而且我还
会告诉大家**怎么花比别人少的钱购买服务器**，下文将会提到怎么获取优惠码，一般人很少知道的！

## 2.使用搬瓦工搭建VPN前的准备

1. 一台可以上网的电脑。

2. 支付宝或者PayPal账号， 搬瓦工支持支付宝付款。


## 3.购买搬瓦工VPS云服务器

### 3.1选择搬瓦工VPS服务器

点击<a href="https://bwh1.net/aff.php?aff=32874" target="_blank">搬瓦工官网</a>进入搬瓦工官网（待会在这里可以从中拿到优惠码）。进入之后可以看到可以购买的VPS云服务器，个人使用的话购买最便宜的就好了，
比如这里有个19.99刀一年就不错:

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn1.png)

不过便宜的很抢手，很快就会被人买光，比如这里 no stock 就说明被人买光了：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn2.png)

### 3.2拿到搬瓦工优惠码

ok，我们点击「Order KVM」:

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn3.png)

当你进到这个页面的时候呢，别急着点击「Add to Cart」添加到购物车，这里面暗藏着一个优惠码，很多人不知道，使用浏览器查看源代码，
chrome浏览器的话按F12，然后搜索「code」，你会发现有一个 「Try this promo code: xxxx 」，这个xxxx就是优惠码，你把他复制下来，待会有用。

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn4.png)

页面的 Location 就是选择服务器的地址，到时访问谷歌的时候会显示你当前访问的地址。好了，我们点击「Add to Cart」。

接下来，进入结算页面，我们刚才复制的优惠码就派上用场了，将你刚刚复制的优惠码复制进去然后点击 「Validate Code」，看！是不是优惠了！一般人不知道这种操作:

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn5.png)

接着点击「CheckOut」完成付款即可。付款的时候选择 Alipay 就可以使用支付宝付款。

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn8.png)

## 4.快速搭建搬瓦工VPN

购买完毕后你就拥有一台你自己的服务器了，接着点击Services下的MyServices，可以看到你的服务器：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn6.png)

我们点击「KiwiVM Control Panel」进入管理界面：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn7.png)

可以看到你服务器的信息:

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn9.png)

接着我们点击 「OpenVPN Server」：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn10.png)

接着点击：「Install and configer OpenVPN Server」，搬瓦工会自动帮我们在服务器安装和配置，不需要自己手动敲命令了：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn11.png)

等一会就搭建好VPN了，就问你快不？

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn12.png)

## 5.使用搬瓦工openVPN

### PC端使用搬瓦工VPN

首先我们下载我们的VPN文件所需的配置文件，点击「Download key Files」下载，然后再下载openVPN的客户端：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn13.png)

接着将配置文件解压到openVPN客户端的config文件夹下：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn14.png)
![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn15.png)

接着再openvpn目录下的bin目录双击打开openvpn-gui，然后Connect连接，连接完成右下角的openVPN会成为绿色状态，然后就可以访问外网了，速度很快：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn16.png)
![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn17.png)
![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn18.png)

### iPhone端使用搬瓦工VPN

同样，手机也需要安装一个openVPN的客户端，不过你在中国区的 AppleStore 下载不到 openVPN 的，你需要注册一个美区的苹果账号，然后搜索 openVPN 下载：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn20.png)

接着电脑端下载 iTunes ，打开 iTunes ，手机用数据线连接电脑，点击文件共享：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn21.png)

将刚刚下载的vpn文件解压，然后添加到OpenVPN客户端：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn22.png)

手机打开OpenVPN APP， 点击 + 这个按钮：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn23.png)

然后就可以连接了：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn24.png)

访问速度杠杠的：

![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn25.png)
![使用搬瓦工搭建VPN](http://owx1uvd7t.bkt.clouddn.com/vpn26.png)

### Android端使用搬瓦工VPN

Android手机使用搬瓦工openVpn同上，下载openVpn App ，然后把配置文件传上去就行了。



## 相关文章

[利用搬瓦工VPS自建高速丝滑VPN](https://www.yfmingo.cn/2016/11/05/bandwagonhost_vpn/)

[在搬瓦工中搭建个人vpn](http://www.gengzhibo.com/2017/02/05/vpn/)

[搬瓦工VPS搭建VPN轻松访问Google等](https://blog.csdn.net/qq_34594236/article/details/77131436)



