# superPet
QQ空间小游戏——超级萌宠界面化

采用pyqt5将超级萌宠主要功能简化实现，
直接运行main.py文件即可

> 经测试超级萌宠登录参数改了，登不上去，但是功能部分接口没有问题。作者写这个软件主要还是练习pyqt，界面虽然简陋，但问题不大。作者能力有限找不到登录接口，有能力的可以自行修改登录接口。
## 主要功能如下：
### 一、主界面部分：
    1.登录——采用cookies登录、扫码或账密登录（移植腾讯授权登录）
    2.任务表格——右键可进行操作
        a.刷新——刷新个人信息、任务状态、元气列表
        b.做任务——个别任务不能完成
        c.领奖励
    3.每日一键操作
        a.判断并签到
        b.检查捕捉状态、脱离被捕并洗澡
        c.互动点击(每日5次)
        d.企鹅店员（每日10次）
        e.小程序打卡
        d.收取元气
        f.喂食——速食——喂食
    4.好友互动——打开好友列表界面
    5.商城——打开商城界面
    6.收钱——收取储蓄罐金币
    7.喂食——优先投喂背包可以通过广告免费食物，再投喂剩余食物，最后金币购买收益大的食物
    8.领取元气
    9.道具——使用喂食加速卡、爆米花喂食卡、肥皂
    10.日志——打开输出日志文本
    11.登出
### 二、好友互动部分：
    1.抓捕
    2.送礼物——目前仅能送亲密草
    3.偷金币
    4.偷元气
    5.一键偷——遍历好友偷金币元气
### 三、元气商城部分：
    1.一键商店
        a.砍价——内置商品id。当元气值大于10万，不能砍价（官方问题）
        b.看广告（每日20次，共200元气）
        c.幸运抽奖（每日10次）
    2.砍价——需先输入商品id，可在商品信息中查看
    3.兑奖——同砍价
    4.历史订单——仅能查看第一页
    5.商品信息——含有id、价格等信息


PS:作者刚学完pyqt想来实践以下，刚好结合超级萌宠来练习练习，如有错误，敬请提出。
