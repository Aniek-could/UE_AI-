# UE_AI-
# 我的ue学习内容记录

## 第 1 周：AI 基础闭环
学会 AIController、AIPerception、Blackboard，能实现“看到玩家后追踪”。

## 第 2 周：StateTree 或 Behavior Tree
实现巡逻、追击、攻击、丢失目标、搜索、返回巡逻。

## 第 3 周：导航与 EQS
加入 NavMesh 移动、掩体选择、低血量寻找治疗点。

## 第 4 周：网络与异常处理
AI 只在服务器决策；客户端表现同步；死亡、复活、目标丢失都要可恢复。

## 第 5～6 周：整合进 Online-game
完成三类 NPC：近战、远程、支援。加入一个 AI 调试面板和性能统计。

## 第 7～8 周：测试与演示
录像、README、架构图、状态转换图、性能数据，然后才开始大范围阅读开源项目。


# 官方学习地址
# 先按这些顺序阅读：

1. 虚幻引擎 AI 总览
2. Gameplay Framework
3. AI Perception 感知系统
4. Navigation 导航系统
5. StateTree
6. Behavior Tree
7. Environment Query System / EQS
8. 网络同步总览

# 你现有项目的学习地址
# 你的 Online-game 已经是 UE5.6，而且里面已经有一套 EPIC 示例 AI，非常适合作为第一份源码教材：
- [ShooterAIController.cpp](E:/Game(UE\)/Online-game/Source/Local_AdventureGame/Variant_Shooter/AI/ShooterAIController.cpp)
- [ShooterNPC.cpp](E:/Game(UE\)/Online-game/Source/Local_AdventureGame/Variant_Shooter/AI/ShooterNPC.cpp)
- [ShooterStateTreeUtility.cpp](E:/Game(UE\)/Online-game/Source/Local_AdventureGame/Variant_Shooter/AI/ShooterStateTreeUtility.cpp)
- [EnvQueryContext_Target.cpp](E:/Game(UE\)/Online-game/Source/Local_AdventureGame/Variant_Shooter/AI/EnvQueryContext_Target.cpp)
