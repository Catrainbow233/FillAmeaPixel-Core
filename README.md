# FillAmeaPixel-Core 2.0
Stable Fast Multithread 
Minecraft PE Servers


GenisysPro - FillAmeaPixel  核心



这是一款优化核心 对于小游戏服务器和生存服务器相当合适



目前Bug: Players don't fall out of the world naturally, you'll want to handle PlayerMoveEvent as needed to kill them.



这个优化核心在实体方面进行了优化

经过测试获得结果

矿车移动速度流畅 接近于单机模式[下坡有点抖,]

TNT点燃后下降速度 接近于单机  [如果30个TNT同时爆炸会有5秒卡一下的效果]

支持所有附魔

支持铁毡

支持红石[需扩展]

支持地狱

末影珍珠移动速度 ＝ 单机模式

支持所有药水

无吞方块[速搭]

无回弹

优化了控制台显示

纯中文提示















核心API版本: 3.0.0

协议版本: 150

支持的MinecraftPE: 1.10-1.19

可以输入/ver查看

支持php:  7.0    7.2





支持的插件:

PocketMine-MP Plugins [❌]

Genisys Plugins [兼容少部分]

GenisysPro Plugins[兼容75％]

SteadFast LBSG Plugins [√]

Nebzz Plugin  [兼容少部分]




Creating the FillAmeaPixel.phar File
To build the FillAmeapixel server phar file please follow the instructions below.

Download the FillAmeaPixel master from GitHub, then unzip the master then move the src folder into your server directory, then deleted the old .phar file if you still have it in the server directory.

Download the PocketMine DevTools Plugin then move the plugin into your server directory plugins folder.

Start the server if you don't know how to start the server follow your Starting/Stopping Server instructions above.

Then run makeserver in the server terminal, then it will drop the phar file in its plugin directory.








有问题可以反馈到admin@fapixel.net

Screenshot_20191001-191035.png
