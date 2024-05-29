# 微信京东淘宝优惠监控机器人
最后更新于2024.05.01



重要的事说一遍

一，微信对发送频率有限制，一定要等机器人对指令回复了再发送下一条指令，同时发多条指令机器人只执行第一条指令

二，降价信息有时效性，有时半夜程序发降价信息第二天早上你看价格还没变，一般是因为京东半夜降价早上涨价

三，价格监控的爬虫是用的IP代理池，京东偶有部分区域特价会造成误报
四，偶尔如超过5分钟没有回复再重新发下指令

五，降价信息和优惠信息仅作购物参考，静等消息，大件一次省千八百不成问题

六，如想在电脑上接收信息，可以安装微信pc版

七，微信版淘宝天猫链接暂不支持监控，由于某些不可描述的原因微信对淘宝天猫链接比较敏感，Telegram版后期会加入淘宝天猫价格监控功能

微信版简单使用教程:

扫下面二维码或加监控微信号





主要命令就两条“@价格监控”和“@优惠监控”

“@价格监控”是监控京东商品价格的指令







“@优惠监控”是监控京东天猫淘宝优惠信息的指令





微信版详细使用教程:

所有对机器人的交互均以指令进行
指令格式:@+指令名称+指令内容
例
@价格监控2739568
“@”开头表示这是一个指令
“价格监控”是指令的名称
“2739568”是指令的内容
以下是可用指令使用教程
如某个出现某个指令错误
来看下这个教程
一般是指令有变化
新指令不断开发中

@价格监控
使用此命令可以监控京东商品的价格变化
如有降价第一时间微信通知你
降价信息通知完毕后会删除这条监控
再次监控重新发价格监控指令即可
例:
@价格监控 2739568
“2739568”是京东产品Id

关于取消价格监控：
监控后不能取消

监控单个产品最长时间为两年

如果两年内产品没降价

系统回自动删除监控

特殊用法:
直接发送京东商品链接
如 https://item.jd.com/2739568.html 等
程序自动识别大部分格式的京东链接

小技巧:
大家知道京东有一个保价功能
就是你买了7-30天内如果降价
京东会补偿你差价
那么我们还可以在购买后再监控一下
如果再降价
就可以到”京东后台 -> 客户服务 -> 价格保护”申请补全差价
申请降价补偿后效果截图




在微信里打开短链接后
如果价格没变
一定要点微信页面右上角的四个方块图标
再点“在浏览器中打开”
才是最终价格
有时还可以领券
也可以到电脑端看下
总之京东很调皮的
多试几个方法
降价信息仅作为购物参考
据网友反应有几种收到降价信息后点开京东没降价的情况

时效性,京东喜欢搞秒杀和半夜降价,有时候秒杀仅仅5分钟
地域性,京东会对某个地区单独做降价
大数据杀熟,这个不解释,详情自己搜索
@价格监控低于
例:
@价格监控2739568低于2000
“2739568”是京东的商品ID
“2000”是你期望降到的价格
此条指令的意思就是“监控京东商品ID2739568的价格低于2000元的时候提醒”

@优惠监控
使用此命令可以监控最新的京东，天猫，淘宝优惠信息
有你订阅的关键字第一时间发微信给你
对接 https://www.nox.cn 上的京东，天猫，淘宝优惠信息

取消订阅再次发送相同监控内容就可以

例：
@优惠监控小米
“小米” 是你想监控的关键字
小米家产品众多
监控”小米”单个关键字
只要跟”小米”相关的优惠都会发送给你
不够准确
那么我们来监控和“小米 手机”相关的优惠
给监控号发”@优惠监控小米 手机“
注意“小米”和“手机”之间加空格
多个关键字用空格连接

关键词没有先后顺序

"@优惠监控 小米 手机"和"@优惠监控 手机 小米"相同

不要写成”@优惠监控小米手机”
这样和小米手机相关的优惠才会发送给你
关键词越多信息就越准确


@关键字列表

返回你订阅的优惠关键字列表

@帮助
返回使用教程的链接

@京东优惠
返回京东优惠信息的链接：https://www.nox.cn/13895

 

@更新列表
返回最近本程序的更新进度
