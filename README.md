# FAA_FoodsVsMouses_AutoAssistant

一款名叫中国页游《美食大战老鼠》的自动助手, 一键完成所有日常任务。  
An automatic assistant for a Chinese webpage game called Foods Vs Mouses, Complete all daily tasks with one click.

本软件基于图像识别 + 自动放卡完成战斗, 不支持任何作弊功能(秒杀或更多)。  
This software is based on image recognition, and does not support any cheating function (flash killing and more).

本软件尚处于开发阶段, 已实现功能见下。  
This software is still in the development stage and its functions have been implemented as shown below.

该工具开发初衷是圆梦十年前的童年愿望 (悲)    
The original intention of developing this tool is to fulfill a childhood wish ten years ago (XP)

联系我: QQ - 815204388  
[推荐]反馈交流群: QQ - 786921130

# 下载

[Github下载](https://github.com/StareAbyss/FoodsVsMouses_AutoAssistant/releases) 
[QQ交流群群文件]

# 预览

![BE(7{WB{E %6JNR@G}C 53X](https://github.com/StareAbyss/FoodsVsMouses_AutoAssistant/assets/112901226/6f7278f1-3f24-46bf-9f68-1b1aa7a2f3ed)

# 主要功能 Main

    主要功能
        │
        ├─ 自动日常
        │   ├─ 自动登录刷新防卡
        │   ├─ 每日签到
        │   ├─ 美食活动免费许愿
        │   ├─ 每日vip签到&礼卷领取
        │   └─ 每日免费塔罗抽取
        │
        ├─ 流水线刷本
        │   ├─ 双人 公会任务 + 领取
        │   ├─ 双人 情侣任务 + 领取
        │   ├─ 双人 悬赏 + 领取
        │   ├─ 单人 魔塔
        │   ├─ 双人 魔塔
        │   ├─ 单人魔塔密室
        │   ├─ 单人&双人 跨服
        │   ├─ 单人&双人 勇士本
        │   ├─ 单人&双人 火山遗迹
        │   ├─ 单人&双人 单本连刷
        │   └─ 自定义任务列表 - 目前测试功能支持美食大赛无脑从头刷到尾, 具体请加入反馈交流群.
        │
        ├─ 自动放卡战斗
        │   ├─ 模仿人类思考方式的算法实现, 从目标阵容和卡片与位置重要性角度进行合理放卡.
        │   ├─ 单人双人均可支持.
        │   ├─ 上手轻松, 可高度自定义的战斗方案, 攻略各种高难副本(魔塔139, 雷城街区钟楼音乐节日已包含于默认方案), 或根据个人box创建独属于您自己的完美方案~
        │   ├─ 一文件一份战斗方案, 便于分享抄作业, 分享您的奇思妙想.
        │   ├─ 默认配置简单平民, 上手容易
        │   ├─ 自动使用武器技能.
        │   └─ 2P 角色的自动拾取.
        │
        ├─ 其他特性
        │   └─ 带一个不瞎眼的GUI界面(大概)
        │
        └─ 未来计划
            └─ 自动启动

# 用户使用必读

## 浏览器

* 目前仅支持 **<Windows7及以上>** **<360游戏大厅>** **<2P>** **<多窗口模式>**
* 4399渠道可以稳定使用, QQ渠道仅支持非刷新的操作(刷新会导致需要重新登陆, 暂时无解)
* 必须点击右上角按钮拆成两个窗口否则无法正常识别!  开更多窗口不会造成影响
* 窗口滚动条贴到最上+最左, 否则刷新时会自动调整导致坐标错位.

## 角色

* P2必须加P1为好友, 且为 **<唯一>** 好友(P1不受限)
* 最好保证P1和P2 **<等级>** 足够进入大多数副本, 且点掉首次进入副本前的 **<橙色图标>** , 否则部分功能在顺序执行时会卡死或报错退出
* 游戏内设定 **<仅接受来自好友>** 的邀请, 否则会被某些乱七八糟的邀请扰乱流程
* 会自动设定关卡密码, 防止有人进入扰乱
* 一般由2P邀请1P, 以保证1P的加好友自由
* 跨服由1P创建房间2P加入, 因为一般默认1P练度高, 但需要自行更改 resource/picture/common/cross_server_1P的图片

## 软件中重要信息的填写

* 窗口名和游戏名称
    * **<填写错误 会直接导致软件闪退, 是唯一启动即闪退的可能>**
    * 360游戏大厅在添加游戏时, 你所填写的游戏名称, 为软件中需要填写的游戏名称
    * 360游戏大厅在添加小号时, 你所填写的角色名字, 为软件中需要填写的1P和2P的窗口名
    * 360游戏大厅中第一个启动的角色, 其窗口名需要空置, 请保持每次启动360游戏大厅时第一个开启的角色是相对固定的 
    * 具体可以参考下图
        * 将鼠标悬停在windows任务栏中的360游戏大厅的窗口上, 启动1P和2P时可以看到. 为 角色名称 | 游戏名称 或 游戏名称
        * 其中 仅有游戏名称, 为第一个启动的角色, 对应在软件中, 其窗口名空置
        * 其中 角色名称 | 游戏名称, 为之后启动的角色, 对应在软件中, 填写角色名称
    ![image](https://github.com/StareAbyss/FoodsVsMouses_AutoAssistant/assets/112901226/80dea34e-5c84-43ce-932b-838c168bbdbd)


* 角色等级
    * 用于在任务需要完成高等级解锁的副本, 但角色等级不足时, 直接跳过对应任务, 防止卡死, 请如实填写

* 屏幕缩放
    * 用于保证点击的缩放位置正确
    * win10 win11 用户, 桌面右键显示设置, 缩放和布局, 缩放中的数值, 记住它 然后在软件中进行选择       
    * 填错不会有报错和卡死, 但运行会异常, 请认真检查

## 卡组(默认卡组)

本软件支持自定义的可分享的战斗布阵方案  
下图布阵为软件自带的默认战斗方案

* 默认卡组(含默认-堵门)

    默认设置为[卡组1]    
    用于通勤, 可通杀大多数关卡, 包括: 所有公会任务 / 所有情侣任务 / 大多数悬赏第12关 / 火山遗迹 / 勇士 / 单人魔塔125 / 双人魔塔上限未知 / 跨服巫毒11(或更高)   
    如果需要完成 **<需要携带某卡片>** 的公会任务, 必须使用该卡组, 或仿照卡组, 使用木盘+麦芽开头, 空格+气泡收尾的卡组   

    |    | 1   | 2   | 3   | 4   | 5    | 6   | 7   | 8   | 9   | 10 | 11 | 12  |
    |:---|:----|:----|:----|:----|:-----|:----|:----|:----|:----|:---|:---|:----|
    | 1P | 木盘子 | 麦芽糖 | 小火炉 | 海星类 | 专业防空 | 瓜皮类 | 喷壶类 | 油灯类 | 布丁类 | 空格 | 气泡 | 咖啡粉 |
    | 2P | 木盘子 | 麦芽糖 | 小火炉 | 海星类 | 专业防空 | 瓜皮类 | 喷壶类 | 油灯类 | 布丁类 | 空格 | 气泡 | 咖啡粉 |
    
    注: 卡组2P不使用布丁, 但为了使2P单独作为1P作战使用默认方案时能摆放布丁, 故带上


* 花瓶卡组

    摆烂, 什么都不干, 一般可以是1P默认, 2P花瓶, 作用同默认卡组

    |    | 1   | 2   | 3  | 4  | 5   | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
    |:---|:----|:----|:---|:---|:----|:--|:--|:--|:--|:---|:---|:---|
    | NP | 木盘子 | 麦芽糖 | 空格 | 气泡 | 咖啡粉 |   |   |   |   |    |    |    |


* 高难卡组

    默认设置为[卡组2]  
    用于攻克部分难度较高的关卡, 例如 街区 钟楼 音乐节日, 双人魔塔,
    如在雷城使用该卡组, 请不要用猫枪, 会导致瓦力鼠爆炸

    |    | 1   | 2   | 3   | 4   | 5    | 6   | 7   | 8    | 9    | 10   | 11  | 12  |
    |:---|:----|:----|:----|:----|:-----|:----|:----|:-----|:-----|:-----|:----|:----|
    | 1P | 木盘子 | 麦芽糖 | 小火炉 | 海星类 | 专业防空 | 瓜皮类 | 冰淇淋 | 辣椒粉类 | 辣椒粉类 | 辣椒粉类 | 布丁类 | 咖啡粉 |
    | 2P | 木盘子 | 麦芽糖 | 小火炉 | 海星类 | 专业防空 | 瓜皮类 | 冰淇淋 | 辣椒粉类 | 辣椒粉类 | 辣椒粉类 | 咖粉  |     |


* 单人魔塔139卡组

    默认设置为[卡组3]

    |    | 1   | 2   | 3   | 4   | 5    | 6   | 7   | 8   | 9    | 10   | 11  | 12  |
    |:---|:----|:----|:----|:----|:-----|:----|:----|:----|:-----|:-----|:----|:----|
    | 1P | 木盘子 | 麦芽糖 | 小火炉 | 海星类 | 专业防空 | 瓜皮类 | 冰淇淋 | 喷壶类 | 辣椒粉类 | 辣椒粉类 | 瓜皮类 | 瓜皮类 |

* 单人魔塔149卡组

    默认设置为[卡组3]

    |    | 1   | 2   | 3   | 4   | 5    | 6   | 7   | 8   | 9   | 10   | 11   | 12   | 13 |
    |:---|:----|:----|:----|:----|:-----|:----|:----|:----|:----|:-----|:-----|:-----|:---|
    | 1P | 布丁类 | 冰淇淋 | 小火炉 | 海星类 | 专业防空 | 喷壶类 | 瓜皮类 | 瓜皮类 | 瓜皮类 | 辣椒粉类 | 辣椒粉类 | 辣椒粉类 |
* 
* 悬赏卡组

    默认设置为[卡组4]  
    具体卡组请打开opt自行查看或加入反馈群, 每轮悬赏均有变化


* 雪山卡组

    默认设置为[卡组5]  
    用于攻克雪山, 因为比较特别的需要海盐粉.

    |    | 1   | 2   | 3   | 4   | 5    | 6   | 7   | 8   | 9   | 10  | 11 | 12 |
    |:---|:----|:----|:----|:----|:-----|:----|:----|:----|:----|:----|:---|:---|
    | 1P | 木盘子 | 麦芽糖 | 小火炉 | 海星类 | 专业防空 | 瓜皮类 | 冰淇淋 | 喷壶类 | 海盐粉 | 咖啡粉 |    |    |
    | 2P | 木盘子 | 麦芽糖 | 小火炉 | 海星类 | 专业防空 | 瓜皮类 | 冰淇淋 | 喷壶类 | 海盐粉 | 咖啡粉 |    |    |


* 生煎锅速刷卡组

    默认设置为[卡组6]  
    用于简单副本的速刷, 例如神殿/深渊

    |    | 1   | 2   | 3   | 4   | 5    | 6   | 7   | 8   | 9   | 10   | 11  | 12  |
    |:---|:----|:----|:----|:----|:-----|:----|:----|:----|:----|:-----|:----|:----|
    | 1P | 木盘子 | 麦芽糖 | 小火炉 | 生煎锅 | 专业防空 | 瓜皮类 | 喷壶类 | 油灯类 | 冰淇淋 | 投掷增益 | 防漏卡 | 咖啡粉 |    |
    | 2P | 木盘子 | 麦芽糖 | 小火炉 | 生煎锅 | 专业防空 | 瓜皮类 | 喷壶类 | 油灯类 | 冰淇淋 | 咖啡粉  |     |
    
    防漏卡: 可以选择海星, 散点追踪(雪球兔/冰神), 群体轰炸(龙虾炮/火箭猪), 单体追踪(一转章鱼烧/忍忍鸡) 等卡片.

## 练度(默认卡组)

* 指定卡
  * 木盘子: **<必须1转>**, 1P|2P均是. 不可替代.
  * 麦芽糖+咖啡粉: 可以用魔法软糖替代. 推荐1转减费.
  * 气泡: 推荐9星, 否则可能会出现部分关卡中途大批量破裂拖慢进度.
  * 小火炉: 1P推荐2转. 1转会在部分难度较高关卡翻车.
  * 冰淇淋: 推荐9星. 
  * 海盐粉: 推荐9星. 推荐白嫖1转减费.
* 可替换
  * 海星类: 炭烧海星1P推荐12星+技能7+2转.1转会在部分难度较高关卡翻车. 2P能上岸就行.
  * 专业防空: 糖葫芦9星+技能5. 
  * 喷壶类: 需要5x5范围, 低配狮子座9星即可. 
  * 布丁类: 樱桃反弹布丁/狗布丁/牛布丁 等...
  * 瓜皮类: 包含 瓜皮护罩/处女座/赫拉/生日帽/扑克牌护罩 等...
  * 辣椒粉类: 包含 爆炸汪/辣椒粉/肉松清明粿, 均为廉价或赠送卡, 可以用 老鼠夹子\面粉袋\10周年烟花\产火充足情况下的其他炸弹卡 替代.
  * 油灯类: 任意全图照明卡, 包含 一转油灯/肉松清明粿/防萤草 等...

## 部署步骤

* 下载最新版本zip并解压
    * 脚本所在目录前的所有目录内不能有任何中文路径 (最新版本待测试, 目前来看中文路径似乎不影响运行了...)
    * 不要随意移动内部的文件, 如果你不知道你正在做什么.
* 根据上文要求 更改卡组 好友等 ...
* 启动 **点此一键启动.bat**, 可以为它创建快捷方式到桌面以方便启动.

## 其他须知

* 本软件采用通用 **<全自动>** 进图组队+战斗, 由于鼠标唯一的特性, 执行期间:
    * 请 **<不要运行任何会抢占鼠标的应用>** , 包括但不限于: FPS/鼠标转动视角的游戏, 被远程控制等...
    * 可以放在后台进行游戏, 但 **<请不要最小化窗口>** , 会导致图像无法被获取.
* 做任务的卡在需要时, 将自动从对应的已有的 **<绑定卡片>** 中添加.
* 请 **<保证背包格子充足>** 后启动. 背包不足时, 会继续战斗, 可以通过保留物品数量为1防止某些战利品被卡掉,
  但无法保障签到或领取奖励等操作成功.
* 本软件出入开发测试阶段, 防bug损失建议:
    * **<设定二级密码 + 使用中不输入>**
    * **<有一定的礼卷防翻牌异常>**
    * **<高星不绑卡挂拍卖/提前转移>**
* 软件会自动截图记录战利品储存于软件根目录logs文件夹中, 若不需要或占用了过大储存, 可以将图片删除

## 地图代号说明

地图代号包含: 地图类型-地图序号-关卡序号

常用案例:  
神殿:`NO-1-7`    
深渊:`NO-1-14`   
城堡:`NO-2-5`  
港口:`NO-2-10`   
火山:`NO-2-15`   
花园:`NO-4-5`

    NO: Normal 普通关卡 包括三岛+海岛+遗迹 总选择2区
        1: 美味岛
        2: 火山岛
        3: 火山遗迹
        4: 浮空岛
        5: 旋涡
            从1开始, 根据地图顺序递增
            外论：
                漫游关卡为 NO-1-15 NO-2-16 NO-4-16
                勇士挑战为 NO-2-17 仅支持钢铁侠
    MT: Magic Tower 魔塔蛋糕 通过地图进入
        1: 单人
            直接填入层数(1-155)
        2: 双人
            直接填入层数(1-100)
        3: 密室
            1为炼金房(1-4)
    CS: Cross Server 跨服副本(不支持组队)
        1: 古堡
        2: 天空
        3: 地狱
        4: 水火
        5: 巫毒
        6: 冰封
            1-8：所有地图
    OR: Offer a Reward 悬赏副本
        1: 美味
        2: 火山
        3: 浮空
            0: 保证每一个关卡都有三个参数 占位
    EX: Extra 番外副本
        1: 营地
        2: 沙漠
        3: 雪山
        4: 雷城

# 自定义和部分自动战斗实现的说明

在config目录中:  
opt_customize_todo.json 为 <自定义战斗序列> 的配置文件.  
opt_battle_plan 为 <战斗方案>的配置文件夹.

### 文件名

请使用 **<数字-任务中文文本.json>** 作为文件名.  
由于本软件记忆系统默认排序下的序数(索引)作为配置文件以保存, 因此为保证默认方案的顺序不被打乱, **<首位数字 强烈建议
大于默认的所有方案>**

### 自定义战斗序列

支持范围包括 NO CS OR EX 中的副本.
    
    [
        {
            "stage_id": "NO-1-7", // str,地图
            "max_times": 2, // int, 战斗次数
            "deck": 1, // int, 使用第几个格子的卡组,
            "is_group": true, // bool, 是否组队
            "battle_plan_1p": 0, // int, 使用的战斗方案的index序号, 名称排序从0开始从上到下
            "battle_plan_2p": 0, // int, 使用的战斗方案的index序号, 名称排序从0开始从上到下
            "task_card": "None", // str, 任务需要的卡片, "None"为无, 有则填写 <非转职完整中文卡片名称-转职编号>,
            仅会选取对应转职阶段的卡片自动加入卡组并使用, 例: 炭烧海星-1 代表一转炭烧海星, 以此类推
            "list_ban_card": [], // list[str,str,...], 静止携带的卡片, 空列表即为不ban, 携带则填写 <非转职完整中文卡片名称,不写转职编号>. 会自动ban掉所有转职衍生卡. 例: [小火炉, 炭烧海星,狮子座精灵]
            "dict_exit": {
                "other_time": [0], // 完成战斗后, 如果不是该副本最后一次作战, 之后的退出动作编号
                "last_time": [3]  // 完成战斗后, 如果是该副本最后一次作战, 之后的退出动作编号
            }
        },
        ...
    [

## 退出动作编号

    0-不退出(推荐在非最后一次作战后使用)
    1-右下回退到上一级 
    2-右上红叉  
    3-直接到竞技岛(推荐在最后一次作战后使用)
    4-悬赏任务专用的最后一次作战后使用
    5-美食大赛领取, 会先到竞技岛,然后领取已完成的所有美食大赛奖励并关闭界面

## 战斗方案

### 配置文件解析

    {
      "player": [战斗网格str,...] // 战斗开始时放玩家角色的位置, 可以为多个
      "card": [
          {
              "tips": str,  //  只是提示文字, 可以不写
              "id": int,  //  对应卡组的第N个卡, 1和2是木盘和麦芽不可占用, 否则会破坏自动计算放承载卡的功能. 
              "name": str,  // <非转职完整中文卡片名称, 不写转职编号>, 用于ban卡, 一般可以乱填, 但必须有该字段.
              "location": [战斗网格str,...] // 该卡需要放的位置, 一般为多个, 若为[]空值, 即不放卡
              "ergodic" : bool, // 见下文
              "queue": bool, // 见下文
          },
      ... // 更多字典, 更多卡片
      ]
    }

### 战斗网格str :"x-y"

* xy均为从1开始,
* 以左上角为"1-1", 左下角为"1-7", 右下角为"9-7", 以此类推
* 由于任务用卡片在卡组中的位置为根据card中list的长度 + 2(两种承载卡) 计算.

### 任务卡的自动放卡机制

* 软件会自动根据任务读取所需的任务卡, 在运行时放置于右手第一个空格, 并以 **配置方案中最大id + 1** 作为其顺序位置
* 如有需携带不使用的卡, 可以将其location字段值设置为[], 即可不破坏自动使用任务卡功能

###  ergodic 和 queue 选项

ergodic(遍历); queue(队列) 代表了自动战斗放卡实现的两种思想.    

自动放卡一轮大约7s, 实际时间会根据总计需要的点击次数智能计算, 间隔为 最长有效放卡耗时 + 7s

* 遍历, 代表了是否需要补充卡片的思想.    
不遍历代表不需要补充卡片, 每一轮只要每个位置放一次就好.     
反之代表需要补充卡片, 每一轮放卡都会以从上到下的顺序将其他该卡目标部署的位置点击一遍, 查看是否可以放下.    

* 队列, 代表了是否有优先级的思想.      
队列的操作, 具体来说是让location列表, 每一次放卡后, 将其第一位放到末尾.       
不队列该卡片, 意味着该卡的从上到下顺序有优先级意义, 会从前到后进行放置保证战略要地发挥作用.            
队列该卡片, 意味着该卡均匀且广泛的布局更为重要, 且可以防止由于地图机制导致一直在错误的位置放卡损卡.     

将之组合, 可以得到玩家一般游戏过程中的四种常见策略(其中一种无意义)   
![image](https://github.com/StareAbyss/FoodsVsMouses_AutoAssistant/assets/112901226/99156bc9-fd39-4fe9-abe2-f42e4c1652cf)

### 关于承载卡的放置

* 在配置文件中录入了绝大部分关卡的承载卡需求情况.
* 当读取到对应关卡的承载卡配置时, 会自动将卡组的第一张卡认为是木盘子, 第二张卡认为是麦芽糖, 加入战斗方案, 自动放置.
* 当该战斗为组队进行时, 1P和2P会分辨承担奇数和偶数位的承载卡放置任务.
* 这是自定义的作战方案一般以第三张卡书写的开始的原因, 因为1/2被木盘子和麦芽糖默认占用了. 如果强行占用该位置,
  会导致该功能失效, 出现意想不到的错误.
* 是为了配置方案的通用性做出的规范和牺牲.

# 免责声明

* 本软件使用 AGPL 3.0 协议开源、免费，仅供学习交流使用。若您遇到商家使用本软件进行代练并收费，可能是设备与时间等费用，产生的问题及后果与本软件无关.
* 本软件处于 **<开发测试阶段>** , 执行过程中建议 **<关注执行情况>** , 若执行中因bug导致任何问题, 请立刻 **<刷新游戏窗口>
  ** + **<叉掉退出软件>**, 本人不负任何法律责任.
* 再次说明 防bug损失建议:
    * **<设定二级密码 + 使用中不输入>**
    * **<有一定的礼卷防翻牌异常>**
    * **<高星不绑卡挂拍卖/提前转移>**

# 开发者部署

## 项目结构

    root
     │
     ├─ config 配置文件 使用json格式
     │   │
     │   ├─ battle_plan 内含大量默认的战斗方案. 也可以自行添加自定义战斗方案
     │   ├─ opt_customize_from_csv.py 用于将csv格式的战斗方案转化为对应的json格式, 美食大赛用
     │   ├─ opt_customize_todo.csv csv格式的自定义战斗方案
     │   ├─ opt_customize_todo.json 在执行自定义战斗时, 将读取此方案
     │   ├─ opt_customize_todo_example.json 自定义战斗方案的模板文件
     │   ├─ opt_main.py 对应ui的主要配置文件
     │   └─ opt_stage_info.json 大部分常见关卡的信息, 在战斗时会读取用于去除对障碍的无效点击/铲除地图自带卡/放承载卡.
     │
     ├─ function(打包后为main)
     │   │
     │   ├─ common 包含各种工具类, 后台进行 截图/找图/按键/点击等
     │   ├─ script 主要功能函数 以common.py和farm_no_ui.py为主 其他未实现
     │   │   │
     │   │   ├─ ui
     │   │   │   ├─ ui_0_load_ui_file.py MainWindow类, 读取ui, 封装少量通用函数.
     │   │   │   ├─ ui_1_load_opt.py 继承MainWindow, todo_ui.josn 和 opt数组 和 ui界面的数据传输.
     │   │   │   └─ ui_2_battle_with_ui.py 在ui类中多线程调用FAA类中的各项核心功能.
     │   │   │
     │   │   ├─ service
     │   │   │   │
     │   │   │   ├─ in_battle 战斗中相关函数的封装
     │   │   │   │   ├─ round_of_battle_calculation.py 完成流程: 通过配置文件, 生成对应的战斗中操作配置
     │   │   │   │   ├─ round_of_battle.py 完成流程: 完成战斗到结束战斗的全流程, 核心功能
     │   │   │   │   └─ round_of_game.py 完成流程:房间界面->选卡战斗->战斗结算->房间界面
     │   │   │   │
     │   │   │   ├─ common.py 游戏中单一角色完成的各种通用封装函数.
     │   │   │   └─ common_multiplayer.py 游戏中两个角色完成的各种通用封装函数.
     │   │   │
     │   │   └─ scattered 散乱的杂项函数 
     │   │       ├─ get_channel_name.py 根据输入的1p2p名称和游戏名称, 获取窗口名称
     │   │       ├─ get_handle.py 根据窗口名称和需要的窗口层级, 获取对应句柄
     │   │       ├─ get_battle_plan_list.py 获取opt中的战斗方案名称列表, 返回为list
     │   │       └─ get_house_id.py 获取作战房间的房间号, 可用但暂未使用
     │   │
     │   ├─ get_paths.py 根据exe和pycharm运行环境 获取root路径. 并保存了大多数资源文件的路径到paths全局变量以便调用.
     │   └─ main.py 主函数 
     │
     ├─ logs 战利品记录图保存位置
     │
     ├─ resource 资源文件
     │   │
     │   ├─ logo 图标资源
     │   ├─ picture 图片资源文件
     │   │   │
     │   │   ├─ card 卡片图片, 用于在ban卡和添加任务卡时, 寻找点击
     │   │   ├─ common 一些通用的界面图片
     │   │   ├─ map 大地图中各个地区的图片
     │   │   ├─ number 用于识图房间号, 暂时无用
     │   │   ├─ stage 各个关卡的图片, 用于选择正确的关卡
     │   │   ├─ stage_ready_cheack 房间界面左下的地图图片, 原用于识别当前所在关卡, 现废弃
     │   │   ├─ task_guild 公会任务相关图片, 其中带序号的文件夹代表从上到下第几个任务
     │   │   ├─ task_spouse 情侣任务相关图片, 其中带序号的文件夹代表从左到右第几个任务
     │   │   └─ get_new_picture.py 用于截图获取房间界面左下角的地图图片, 现废弃
     │   │   
     │   └─ ui .ui文件
     │
     └─ todo_ui.josn

路径做了简单处理 再pycharm和打包exe后都可以轻松运行.  
Link Start!

# 致谢

## 开源库

* 图像识别库：[opencv](https://github.com/opencv/opencv.git)
