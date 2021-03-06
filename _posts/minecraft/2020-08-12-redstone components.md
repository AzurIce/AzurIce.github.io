---
layout: post
title: 红石元器件
date: 2020-08-12
tags: Minecraft Redstone
---
# 红石元器件

## 漏斗

激活方式：

- 一个毗邻的开启的**[电源](https://minecraft-zh.gamepedia.com/红石元件#.E7.94.B5.E6.BA.90.E5.85.83.E4.BB.B6)**（例外：红石火把不会激活它附着的漏斗，侦测器只激活它指向的漏斗）。
- 一个毗邻的**充能方块**。
- 一个指向漏斗且输出信号的**[红石比较器](https://minecraft-zh.gamepedia.com/红石比较器)**或**[红石中继器](https://minecraft-zh.gamepedia.com/红石中继器)**。
- 邻近的指向漏斗（包括在漏斗上面的）的激活的**[红石粉](https://minecraft-zh.gamepedia.com/漏斗#.E7.BA.A2.E7.9F.B3.E7.B2.89)**。



未激活的漏斗可做下面的三件事：

- **输出**自己的物品栏里的一个物品到朝向的容器。

- **吸取**上方容器内的一个物品到自己的物品栏。

- **捕捉**上方的[物品实体](https://minecraft-zh.gamepedia.com/物品（实体）)（在世界中的掉落物）到自己的物品栏。

    > 漏斗只会捕捉凹槽内以及上方1×1×1的位置内的物品实体。即使物品只有一部分在可捕捉位置（例如，在[灵魂沙](https://minecraft-zh.gamepedia.com/灵魂沙)上）



同一游戏刻中，漏斗会尝试进行所有操作。但是漏斗先进行输出然后才进行吸取，如果上方没有容器，最后还会进行捕捉物品实体。漏斗的这三个操作只要有一个成功，漏斗就会有“冷却时间”：在漏斗再次运作之前会等待4红石刻（8游戏刻或无卡顿的0.4秒）。额外的，另一个漏斗或投掷器将物品输入此漏斗时，此漏斗也会有8游戏刻的冷却时间。

在[Java版](https://minecraft-zh.gamepedia.com/Java版)中，由于多种原因，一个漏斗或发射器向空漏斗传输一个物品，空漏斗接收到这一个物品后的冷却时间为7游戏刻。由于漏斗与漏斗之间会有更新顺序的差异，有更复杂的机制影响物品传输的延迟。