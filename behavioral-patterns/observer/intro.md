```观察者```是一种行为设计模式，允许一个对象将其状态的改变通知其他对象

##概念示例

在电商网站中，商品时不时地会出现缺货情况。可能会有客户对于缺货的特定商品表现出兴趣。这一问题有三种解决方案：

1. 客户以一定的频率查看商品的可用性。
2. 电商网站向客户发送有库存的所有新商品。
3. 客户只订阅其感兴趣的特定商品，商品可用时便会收到通知。同时，多名客户也可订阅同一款产品。

选项 3 是最具可行性的，这其实就是观察者模式的思想。观察者模式的主要组成部分有：

- 会在有任何事发生时发布事件的主体。
- 订阅了主体事件并会在事件发生时收到通知的观察者。