#	策略模式：
动作冒险游戏，游戏中有一系列角色(Character)，包括国王(King)、皇后(Queen)、骑士(Knight)、妖怪(Troll),这些角色可以在游戏中每一次使用一个武器(Weapon)来攻击对方，并且可以在运行时切换武器，为了增加游戏的乐趣，可以有的武器包括：匕首、宝剑、斧头、弓箭等等，可能以后又更时髦的武器出现。


## 1、策略模式适用的场景是什么？
•	许多相关类仅仅是行为不同。

•	需要使用一个算法的不同实现。

•	算法使用了客户不应该知道的数据。策略模式可以避免暴露复杂的、与算法相关的数据结构。

•	一个类定义了很多行为，而且这些行为在这个类里的操作以多个条件语句的形式出现。策略模式将相关的条件分支移入它们各自的 Strategy 类中以代替这些条件语句。

## 2、评估其设计效果
   策略模式提供了可以替换继承关系的办法。
   继承可以处理多种算法或行为。
   如果不是用策略模式，那么使用算法或行为的环境类就可能会有一些子类，每一个子类提供一个不同的算法或行为。
   但是，这样一来算法或行为的使用者就和算法或行为本身混在一起。
   决定使用哪一种算法或采取哪一种行为的逻辑就和算法或行为的逻辑混合在一起，从而不可能再独立演化。
   继承使得动态改变算法或行为变得不可能。
   
   


