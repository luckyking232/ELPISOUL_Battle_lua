系统概览
这是一个完整的游戏战斗系统，采用模块化设计，涵盖了战斗逻辑、显示、UI控制、数据管理等各个方面。系统采用事件驱动架构，支持回合制或实时战斗。

文件详细说明
📄 BattleAction.lua
描述: 战斗动作处理核心模块，负责管理战斗单元的各种状态和行为
主要功能:

初始化战斗变量和状态

处理战斗前准备、Buff效果、基础状态

管理移动、攻击、死亡、复活等战斗动作

处理技能触发和特殊效果

控制模型翻转和时间缩放

核心函数: DealAttack(), DealMove(), DealDead(), DealRevive()

📄 BattleActionDisplay.lua
描述: 战斗动作显示模块，负责视觉效果和动画播放
主要功能:

初始化显示系统和动画资源

播放各种战斗动画（移动、攻击、死亡、眩晕等）

管理特效、音效、语音播放

处理Buff图标和文字显示

控制模型变换和状态显示

核心函数: PlayAttack(), PlayDead(), PlayMove(), PlayBuffEffect()

📄 BattleAxisWindow.lua
描述: 战斗时间轴/技能轴UI窗口，显示战斗进度和技能时间线
主要功能:

显示波次列表和回合信息

创建和管理技能时间线

处理头像、手动技能、爆发技能显示

提供技能提示和选择功能

核心函数: CreateWaveList(), CreateHead(), ClickUniqueSkillBtn()

📄 BattleBackground.lua
描述: 战斗背景管理模块
主要功能:

初始化战斗背景

清理背景资源

📄 BattleBuff.lua - BattleBuffMgr.lua
描述: Buff系统系列模块，负责战斗中的状态效果管理
主要功能:

创建和管理各种Buff效果

Buff的添加、移除、结算

监听器机制处理Buff触发

Buff免疫和状态检测

全局Buff数值计算

核心模块:

BattleBuff: 基础Buff对象

BattleBuffEffect: Buff效果处理

BattleBuffMgr: Buff管理器，核心逻辑

📄 BattleBullet.lua & BattleBomb.lua
描述: 投射物和炸弹系统
主要功能:

创建和管理子弹、炸弹对象

处理投射物的逻辑和显示

📄 BattleBurst.lua & BattleBurstSkill.lua
描述: 爆发技能系统
主要功能:

管理爆发技能状态

处理爆发技能的创建和执行

📄 BattleCamp.lua
描述: 阵营管理模块
主要功能:

创建阵营对象

处理阵营能量充能

📄 BattleChoose.lua
描述: 目标选择系统，负责战斗中的目标筛选和选择逻辑
主要功能:

获取范围信息和目标类型

根据各种条件筛选目标单位

处理技能和Buff的目标选择

随机选择和特殊条件选择

核心函数: GetTargetUnitList(), GetSkillTargetUnitList(), GetNearestUnit()

📄 BattleConst.lua
描述: 战斗常量定义文件
主要功能: 定义战斗中使用的各种常量值

📄 BattleControl.lua
描述: 战斗流程控制模块
主要功能:

初始化战斗控制

管理战斗进程更新

处理暂停、继续、停止等控制命令

时间缩放和特殊技能暂停

📄 BattleData.lua & BattleDataCount.lua
描述: 战斗数据管理和计算模块
主要功能:

初始化战斗数据

随机数生成和管理

伤害计算和Buff效果计算

战斗评分更新

📄 BattleDataWindow.lua
描述: 战斗数据统计UI窗口
主要功能:

显示伤害统计和战斗数据

更新单位信息和技能信息

提供数据切换和查看功能

📄 BattleFinishWindow.lua & BattleFinishFailWindow.lua
描述: 战斗结束界面
主要功能:

显示战斗结果（胜利/失败）

更新经验值和奖励信息

提供重试和数据查看功能

📄 BattleGrid.lua
描述: 战斗网格系统
主要功能:

创建和管理战斗网格

处理位置和移动相关的网格逻辑

📄 BattleHurtNum.lua
描述: 伤害数字显示系统
主要功能:

显示伤害数字、Buff文字、表情

管理数字显示池

控制显示效果和动画

📄 BattleInfoWindow.lua & BattleLoadingWindow.lua
描述: 战斗信息界面和加载界面
主要功能:

显示战斗基本信息

处理加载过程和动画

📄 BattleManuallySkill.lua
描述: 手动技能管理系统
主要功能:

创建手动技能对象

处理手动技能的目标选择

📄 BattleMgr.lua
描述: 战斗管理器，战斗系统的入口和核心控制器
主要功能:

初始化整个战斗系统

开始和关闭战斗

发送战斗结束消息

打开结束界面

核心函数: InitBattle(), StartBattle(), CloseBattle()

📄 BattleOperation.lua
描述: 战斗操作处理模块
主要功能:

处理爆发技能和手动技能操作

管理操作队列

自动技能条件排序

📄 BattlePathFinding.lua
描述: 路径寻找系统
主要功能:

A*路径寻找算法实现

网格管理和障碍物处理

测试路径生成和显示

📄 BattleScene.lua
描述: 战斗场景管理器，核心的战斗逻辑协调器
主要功能:

初始化战斗场景和地图

管理所有战斗单位、子弹、炸弹

处理技能信息和触发条件

战斗胜负判断

范围检测和距离计算

核心函数: Init(), UpdateProcess(), IsBattleWin(), GetInRangeUnit()

📄 BattleService.lua
描述: 战斗网络服务模块
主要功能:

处理战斗准备和挑战请求

管理战斗记录

与服务器通信

📄 BattleSkillWait.lua & BattleSummonWait.lua & BattleTransform.lua
描述: 等待队列管理系统
主要功能:

管理技能、召唤、变形等待队列

处理等待逻辑和执行顺序

📄 BattleUIWindow.lua
描述: 主战斗UI界面，最复杂的UI控制模块
主要功能:

管理所有战斗UI元素

处理技能拖拽和释放

爆发技能选择和引导

Boss状态显示

自动战斗和速度控制

核心函数: OnDragStart(), PlayBurstSkillGuide(), UpdateBurstInfo()

📄 BattleUnit.lua
描述: 战斗单位基础模块
主要功能:

创建战斗单位对象

处理单位技能和状态变化

📄 BattleScriptList.lua
描述: 战斗脚本列表定义文件

系统架构特点
模块化设计: 每个文件负责特定的功能领域

事件驱动: 通过监听器和触发器实现模块间通信

状态管理: 明确的战斗状态转换

显示与逻辑分离: Action处理逻辑，Display处理显示

数据驱动: 通过常量文件配置战斗参数

核心数据流
输入 → BattleOperation → BattleAction → BattleScene

逻辑计算 → BattleDataCount → BattleBuffMgr

显示更新 → BattleActionDisplay → BattleUIWindow

结果处理 → BattleFinishWindow → BattleMgr

这个战斗系统展现了典型游戏战斗引擎的完整架构，适合用于卡牌、策略或RPG类型的游戏战斗。

