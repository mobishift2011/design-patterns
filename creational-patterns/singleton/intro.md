```单例```是一种创建型设计模式，让你能够保证一个类只有一个实例，并提供一个访问该实例的全局节点。

单例拥有与全局变量相同的优缺点。尽管它们非常有用，但却会破坏代码的模块化特性。

在某些其他上下文中，你不能使用依赖于单例的类。你也将必须使用单例类。绝大多数情况下，该限制会在创建单元测试时出现。