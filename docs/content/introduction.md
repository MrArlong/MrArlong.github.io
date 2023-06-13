# 前言

1994 年，埃里希·伽玛、 约翰·弗利赛德斯、 拉尔夫·约翰逊和理查德· 赫尔姆四位作者出版了《设计模式：可复用面向对象软件的基础》一书，正式将设计模式的概念引入到软件开发领域。该书提供了 23 个模式来解决面向对象程序设计中的常见问题，这本书后来被称为「四人组的书」，即我们熟知的「GoF 的书」或「GoF」。

## 简介

设计模式是软件开发过程中一些常见问题的「典型」解决方案。我们可以将其理解为软件开发的「套路」。

关于设计模式，我们首先应该有以下几点认知：

- 它不同于算法，并不能告诉我们面对某个问题时应该怎么一步步操作，它是更加抽象的蓝图——我们可以看到模式和设计，但并不关心具体实现。
- 无论是一个小小的模块还是一整套软件系统，都可以应用设计模式，且实际中往往是多个模式同时使用。当然，可能部分模式只使用了其中一部分。
- 不同的模式适用于不同的功能和设计，相反，同样的功能和设计在不同阶段或背景下也可能需要不同的模式。模式没有好坏，只有适不适合。

我们为什么需要设计模式，主要有以下几个原因：

- 设计模式是经过多年实践验证有效的解决思路，无论是新开发软件还是进行重构，它都可以让系统更加稳固、代码更加清晰。
- 设计模式是一种可用于工程师之间沟通的「高效语言」，当我们在讨论和分析问题时，简单几个字就可以让彼此明白心意。

## 概览

本书包括常见的 23 个设计模式，一般又被分为三种类型：

- 创建型模式（5 个）：与对象的创建有关。
    - 工厂方法模式
    - 抽象工厂模式
    - 单例模式
    - 建造者模式
    - 原型模式
- 结构型模式（7 个）：与对象的组装有关。
    - 适配器模式
    - 装饰模式
    - 外观模式
    - 桥接模式
    - 代理模式
    - 组合模式
    - 享元模式
- 行为模式（11 个）：与对象之间的沟通协调有关。
    - 观察者模式
    - 命令模式
    - 状态模式
    - 职责链模式
    - 模板方法模式
    - 策略模式
    - 解释器模式
    - 中介者模式
    - 访问者模式
    - 备忘录模式
    - 迭代器模式

另外，面向对象设计的基本原则包括：

- 针对接口编程，而不是针对实现编程。
- 优先使用对象组合，而不是类继承。
- 封装变化，将不变的与变化的内容分开。

我们将会从每个设计原则和设计模式中感受到上述基本原则。

## 理念

本项目特点如下：

- 详细分析每个模式的动机、特点和使用场景。
- 以案例为主，关注代码设计的变化。
- 常见语言（C++、Java、Python ）实现。

本项目适用人群：

- 想让自己代码变得更好。
- 写代码逐渐感受到瓶颈。

的之前不懂或没听过设计模式的软件工程师。