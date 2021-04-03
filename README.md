# EXPLOSION-惠惠爆裂魔法语音
“エクスプロージョン（Explosion）！”
和[惠惠](http://wpa.qq.com/msgrd?v=3&uin=3403478643&site=qq&menu=yes)每天练习爆裂魔法吧！ ~~~老项目了只是之前一直没上传，闲着没事传一下~~~
## 安装
1.直接下载/克隆该项目，把文件放在hoshino/modules文件夹里, 在hoshino/config/\_bot_.py里添加explosion

`MODULES_ON = {'explosion' #爆裂魔法}`

2.在此处/Releases下载语音资源包，并将语音资源放在**C:\Resources\explorion-voice\explosion**下（或者也可以在插件的**第57行，第127，134，141，148，155，162，169，176，183，190行**自己改文件路径---~~~问就是菜还懒，就这么凑活用吧~~）

[Baidu 码=2279](https://pan.baidu.com/s/1Z755sE06_5YuO9nsW60oMw)	·	[Lanzou 码=9wzs](https://wwe.lanzous.com/b010cizah)	·	[Ali(待开启分享功能)]()
## 指令表
>（无需@）[exo, 爆裂魔法, 来一发, 爆烈魔法, 暴烈魔法]	-	和惠惠随机练习一发爆裂魔法

>（需@）[补魔]	-	补充魔力（重置日上限）

>[帮助爆裂魔法]	-	查看帮助说明

## 注意
1.在到达日上限时的提示说明引入了bot的呢称。若您的呢称设置的不止一个，请在插件的第**18，20行**修改为您的bot呢称
>`bot_name = hoshino.config.NICKNAME  #获取bot的呢称(当NICKNAME仅有一个时使用)`

>`EXCEED_NOTICE = f'{bot_name}今天已经使用了{_max}次爆裂魔法哦~~~明天再使用爆裂魔法吧!'  #到上限的提示语，如果不用bot_name可以直接换成名字`

2.可以在插件的**第16行**修改每日魔法上限
>`_max = 2  #每日的魔法上限次数`

3.若不做其它修改，语音文件的目录结构应该是这样的：
>C:/
>>Resources
>>>explorion-voice
>>>>explosion
>>>>>施法吟诵1-10.mp3

其它说明在插件的注释里写的很详细。

