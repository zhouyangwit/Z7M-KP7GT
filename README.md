# 笔记本型号：Z7M-KP7GT，理论上这efi适合于该笔记本的10.13.x和10.14.x，说出来你可能不信，卡塔玲娜我还在用百度云以80kb/s的速度下载中，也不知道有生之年啃得下来不。

# 具体配置如下：  
     CPU：i7 7700HQ  
     显卡：GTX1050ti（显然是多余的，黑苹果表示啃不动这显卡）  
     声卡：ALC269（注入ID29，声音输入输出都没问题）  
     网卡：博通BCM94352z（原厂为因特尔无线网卡，这个无解，只能说好好学习，天天向上，有一天可以自己去写驱动就好了）

# 本EFI特色：  
    1、得益于这个牛x的无线网卡，稍微配置了下，接力、隔空投送均无问题，Facetime什么的，慢慢试序列号吧，这是命；  
    2、CPU完美变频，16档变频，从1000到3400，不要问我为啥不是100一档，这个我只能说你行你上；  
    3、开启核显加速，你只需要知道开启了，不要问我啥是核显加速，咱也不懂，咱也不敢回答；


# 依然存在的问题：  
1、睡眠睡死的问题，修改了DSDT后，现在我的笔记本上是没问题了，但是换个笔记本就不知道了，毕竟玄学；  
2、风扇起飞问题，众所周知，得益于这款笔记本的优秀的公模，单铜管压i7CPU，在macOS系统上，不限制CPU频率的话，我是真的害怕这笔记本哪天会飞走，所以，孩子们还是装个TurboBoost软件，然后限制一下Turbo吧，效果要好很多，CPU常年控制在50度左右；  
3、外接显示器黑屏问题，这是HDMI通病，因为这款笔记本HDMI显示输出是独显负责，10.14独显啃不动，所以，你懂的；解决方法如下：先插好HDMI，然后再开机，等电脑进入系统后，可以把笔记本盖子关上了，不然会花屏；  
4、在使用的过程中出现过几次重启，感觉这个不是bug吧，本着死不承认的原则，这不是我的问题，对，这就不是我的问题；




作者：程序界的小学生  
作者的话：看我的名字就知道我是小学生了，所以大家喜欢的话，就下载用，不喜欢的话，你们能拿我咋滴？

