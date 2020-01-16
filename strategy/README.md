---
layout: pattern
title: Strategy
folder: strategy
permalink: /patterns/strategy/
categories: Behavioral
tags:
 - Gang of Four
---
#Strategy Pattern 策略设计模式
## Also known as
Policy 政策

## Intent
Define a family of algorithms, encapsulate each one, and make them
interchangeable. Strategy lets the algorithm vary independently from clients
that use it.

定义一个家族或者算法，将每一个封装进去，并且使它们可以交换。策略让算法根据委托方的不同发生变化并且使用它。

![alt text](./etc/strategy_1.png "Strategy")

## Applicability
Use the Strategy pattern when
使用策略设计模式的情况：
* many related classes differ only in their behavior. Strategies provide a way to configure a class either one of
 many behaviors(许多相关的类只在它们的行为上有所不同。策略提供了一种配置类的方法，可以是许多行为之一)
* you need different variants of an algorithm. for example, you might define algorithms reflecting different space
 time trade-offs. Strategies can be used when these variants are implemented as a class hierarchy of algorithms
(你需要一种算法的不同实现。例如：)
* an algorithm uses data that clients shouldn't know about. Use the Strategy pattern to avoid exposing complex, algorithm-specific data structures
* a class defines many behaviors, and these appear as multiple conditional statements in its operations. Instead of many conditionals, move related conditional branches into their own Strategy class

## Tutorial 
* [Strategy Pattern Tutorial](https://www.journaldev.com/1754/strategy-design-pattern-in-java-example-tutorial)

## Credits

* [Design Patterns: Elements of Reusable Object-Oriented Software](http://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612)
* [Functional Programming in Java: Harnessing the Power of Java 8 Lambda Expressions](http://www.amazon.com/Functional-Programming-Java-Harnessing-Expressions/dp/1937785467/ref=sr_1_1)
