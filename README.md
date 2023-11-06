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
反馈群: QQ - 786921130


## 下载
[Github下载](https://github.com/StareAbyss/FoodsVsMouses_AutoAssistant/releases)  
[百度网盘(可能版本落后)](https://pan.baidu.com/s/11_3l076upWYJCZnupowUEQ?pwd=STAR)

## 预览
![image](https://github.com/StareAbyss/FoodsVsMouses_AutoAssistant/assets/112901226/75ab8ec8-689e-4d31-a60d-e68939f48930)

## 主要功能 Main

    主要功能
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
    │   └─ 自定义任务列表
    │
    ├─ 自动放卡战斗
    │   ├─ 模仿人类思考方式的算法实现, 从目标阵容和卡片与位置重要性角度进行合理放卡.
    │   ├─ 单人双人均可支持.
    │   ├─ 可高度自定义的战斗方案, 攻略各种高难副本(魔塔139, 雷城街区钟楼音乐节日已包含于默认方案), 或根据个人box创建独属于您自己的完美方案~
    │   ├─ 一文件一份战斗方案, 便于分享抄作业, 分享您的奇思妙想.
    │   ├─ 默认配置简单平民, 上手容易, 可完成: 三岛和海底大多数副本(含公会任务), 单人魔塔1-125, 双人魔塔1-80, 魔塔密室, 勇士本(钢铁侠), 火山遗迹(双人大力神, 单人雷神), 跨服单人巫毒11.
    │   ├─ 自动使用武器技能.
    │   └─ 2P 角色的自动拾取.
    │
    ├─ 其他特性
    │   └─ 带一个不瞎眼的GUI界面(大概)
    │
    ├─ 自动日常(开发中...)
    │   ├─ 每日签到
    │   ├─ 美食活动免费许愿
    │   ├─ 每日vip签到&礼卷领取
    │   └─ 每日免费塔罗抽取
    │
    └─ 未来计划
        └─ 自动登录和自动启动

## 用户使用必读

<details>
<summary>使用要求</summary>
    
#### 1.浏览器
目前仅支持 **<360游戏大厅>** **<2P>** **<多窗口模式>**。必须点击右上角按钮拆成两个窗口否则无法正常识别!  开更多窗口不会造成影响。 

#### 2.角色
P2必须加P1为好友, 且为 **<唯一>** 好友(P1不受限)。  
最好保证P1和P2 **<等级>** 足够进入大多数副本, 且点掉首次进入副本前的 **<橙色图标>** , 否则部分功能在顺序执行时会卡死或报错退出。  
游戏内设定 **<仅接受来自好友>** 的邀请, 否则会被某些乱七八糟的邀请扰乱流程。  
会自动设定关卡密码, 防止有人进入扰乱。  
一般由2P邀请1P, 以保证1P的加好友自由, 跨服由1P创建房间2P加入, 因为不需要好友

#### 3.卡组(默认卡组)
本软件支持自定义的战斗布阵, 下图布阵为软件自带战斗方案
其中默认方案或花瓶卡组是用于通勤, 可通杀大多数关卡, 包括所有公会任务和情侣任务, 火山遗迹, 勇士, 单人魔塔125, 双人魔塔上限未知, 跨服巫毒11(或更高)
下图不是指定特定卡, 而是类似的功能的卡都可以

<details>
<summary>默认卡组(含默认-堵门)</summary>

用于通勤, 可通杀大多数关卡, 包括所有公会任务和情侣任务, 火山遗迹, 勇士, 单人魔塔125, 双人魔塔上限未知, 跨服巫毒11(或更高)  
1P

| 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 | 11 | 12 |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| 木盘 | 麦芽 | 小火 | 海星 | 糖葫 | 瓜皮 | 狮子 | 油灯 | 布丁 | 空格 | 气泡 | 咖粉 |

2P   

| 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 | 11 | 12 |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| 木盘 | 麦芽 | 小火 | 海星 | 糖葫 | 瓜皮 | 狮子 | 油灯 | 空格 | 气泡 | 咖粉 |

</details>

<details>
<summary>花瓶卡组</summary>

摆烂, 什么都不干,一般可以是1P默认,2P花瓶, 作用同默认卡组 

| 1  | 2  | 3  | 4  | 5  | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
|:---|:---|:---|:---|:---|:--|:--|:--|:--|:---|:---|:---|
| 木盘 | 麦芽 | 空格 | 气泡 | 咖粉 |   |   |   |   |    |    |    |
</details>

<details>
<summary>单人魔塔139卡组</summary>

1P

| 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 | 11 | 12 |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| 木盘 | 麦芽 | 小火 | 海星 | 糖葫 | 瓜皮 | 冰沙 | 狮子 | 辣粉 | 清明 | 瓜皮 | 瓜皮 |

</details>

<details>
<summary>街区 + 钟楼 + 音乐节日</summary>

请不要用猫枪, 会导致瓦力鼠爆炸

1P   

| 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 | 11 | 12 |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| 木盘 | 麦芽 | 小火 | 海星 | 糖葫 | 瓜皮 | 冰沙 | 辣粉 | 清明 | 鼠夹 | 布丁 | 咖粉 |

2P   

| 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 | 11 | 12 |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| 木盘 | 麦芽 | 小火 | 海星 | 糖葫 | 瓜皮 | 冰沙 | 辣粉 | 清明 | 鼠夹 | 咖粉 |

</details>

#### 4.练度(默认卡组)
没说明则可以任意配置, 可采取上位替代

    木盘: 必须1转, 1P|2P均是.不可替代.
    麦芽+咖粉: 可以用魔法软糖替代. 推荐1转减费.
    小火: 推荐2转. 人形太阳神或者其他变态产火卡随意. 
    海星: 1P推荐 12星+技能7+2转. 2P 能上岸就行
    糖葫: 9星+技能5.
    狮子: 9星.
    瓜皮: 9星+1转+技能7, 没有问题也不是很大, 但容错更高.

</details>



<details>
<summary>部署步骤</summary>

#### 1. 下载最新版本zip
脚本所在目录前的所有目录内 **<不能有任何中文路径>** !

#### 2. 游戏内角色配置
根据上文要求 更改卡组 好友等 ...


#### 3. 启动
启动 **<main文件夹中的main.exe>**
可以为它创建快捷方式
</details>



<details>
<summary>其他须知</summary>
    
1. 本软件采用通用 **<全自动>** 进图组队+战斗, 执行期间 **<务必不要把鼠标移入游戏区域>** 内将干扰功能, 会导致难以想象的错误.   
2. 本软件支持自定义战斗方案; 默认战斗战斗以 **<1P为战斗力>** , 2P为辅助. 做任务的卡在需要时, 将自动从已有的绑定卡片中添加.    
3. 本软件组队以 **<2P为队长>** , 进行双人模式的组队操作.    
4. 本软件不对背包爆满的问题做预设, 请自行 **<保证背包格子充足>**.   
</details>



<details>
<summary>地图代号说明</summary>
    
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
            
</details>



<details>
<summary>自定义说明</summary>
在config目录中:  
    opt_customize_todo.json 为 自定义任务定义.  
    opt_battle_plan 为 战斗方案.  
    
#### 自定义任务
支持范围包括 NO CS OR EX  
需要设定参数请参见文件内

#### 战斗方案
设定需要摆的阵形

    {
        "阵容名称"：
        {
            "tips": str,
            "id": int,
            "name": str,
            "location": [str,...]
            },
    }
    
阵容名称 - 用于调用该方案, 界面中的1P方案、2P方案、自定义任务中的战斗正是对应此处的名称.    
tips - 只是提示文字, 没有其他意义.  
id - 对应卡组的第N个卡, 1和2是木盘和麦芽, 不可改动, 否则会破坏自动计算放承载卡的功能.  
name - 卡片的英文名称, 用于Ban卡.  
</details>

## 免责声明
本软件使用 AGPL 3.0 协议开源、免费，仅供学习交流使用。若您遇到商家使用本软件进行代练并收费，可能是设备与时间等费用，产生的问题及后果与本软件无关.  

本软件处于 **<开发测试阶段>** , 执行过程中建议 **<关注执行情况>** , 若执行中因bug导致任何问题, 请立刻 **<刷新游戏窗口>** , 本人不负任何法律责任.   
为防止潜在的问题发生, 建议为您的角色 **<设定二级密码>** 且在本次登录中 **<不输入它>** 做兜底. 且建议将 **<不绑卡片挂在拍卖行>**.  


## 开发者部署
<details>
<summary>展开阅读...</summary>
如要拿到本地使用, 请解压 resource.zip 放到项目根目录级. 

    root
     ├─ function(打包后为main)
     │   ├─ common 包含各种工具类, 后台进行 截图/找图/按键/点击等
     │   ├─ script 主要功能函数 以common.py和farm_no_ui.py为主 其他未实现
     │   │   ├─ common.py 战斗中的通用封装函数
     │   │   ├─ common_action.py 一轮战斗和邀请的封装函数
     │   │   ├─ load_ui_file.py MainWindow类, 读取ui, 书写少量通用函数.
     │   │   ├─ load_opt.py 继承MainWindow, todo_ui.josn 和 opt数组 和 ui界面的数据传输.
     │   │   └─ battle_with_ui.py 继承MainWindow, 根据opt进行战斗, 包含不同战斗模式下的不同参数和步骤.
     │   ├─ get_root_path.py 根据exe和pycharm运行环境 获取root路径
     │   └─ main.py 主函数
     ├─ resource
     │   ├─ logs 战利品记录
     │   ├─ picture 图片资源
     │   └─ ui .ui文件
     └─ todo_ui.josn

路径做了简单处理 再pycharm和打包exe后都可以轻松运行.  
Link Start!
</details>

## 致谢
#### 开源库
* 图像识别库：[opencv](https://github.com/opencv/opencv.git)
