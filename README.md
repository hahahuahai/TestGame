# TestGame(Unity5 + kbengine)

一款mmorpg的移动端网络游戏，采用大世界即时战斗方式。
这个游戏有两个职业，每个职业有三个技能。战士的血量和防御比较强，有近程打击和吸血的技能；法师血少攻击距离远，具有远程攻击和治疗的技能。
左下角是控制手柄，视角会随着人物方向变换，点击视角可以瞬间完成变换，右下角是技能按钮和切换对象按钮用来选择对象并攻击或援助。
点选怪物或者玩家左上角会出现血条和名字，表示已选中，此时点击技能可以对该目标释放，如果目标距离大于技能范围则会自动移动到技能范围内，点击左上角自己的血条可以取消对其他目标的选中，此时释放治疗技能可以治疗自己。

v1.0版，目前有物品系统，装备系统，战斗系统，聊天系统完成

使用kbengine-0.8.2版本，服务器脚本在：https://github.com/liuxq/MyGameServerAssets.git

![ui-demo](/demo1.png)
![ui-demo2](/demo2.png)
200人同屏，帧率14，下图是200人同屏的截图，机器配置：cpu：Intel(R) Xeon(R) CPU E5-2430 0 @ 2.20GHz 单核，内存：1G
![ui-demo2](/200.png)
