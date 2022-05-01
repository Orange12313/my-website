---
title: java基础
sidebar_position: 1
---

## Java基础

一个 Java 程序可以认为是一系列对象的集合，而这些对象通过调用**彼此的方法**来协同工作。下面简要介绍下类、对象、方法和实例变量的概念。

- 对象
  > 对象是类的一个实例，有状态和行为。例如，一条狗是一个对象，它的状态有：颜色、名字、品种；行为有：摇尾巴、叫、吃等。



1. 对象

1. 类


```java
public class HelloWorld {
    /* 第一个Java程序
     * 它将输出字符串 Hello World
     */
    public static void main(String[] args) {
        System.out.println("Hello World"); // 输出 Hello World
    }
}
```

![img](https://www.runoob.com/wp-content/uploads/2013/12/662E827A-FA32-4464-B0BD-40087F429E98.jpg)

[点我查看GIthub实例](https://www.runoob.com/java/java-basic-syntax.html)

```bash
git clone http://github
```

`private` 关键字

:::tip
Java 5.0引入了枚举，枚举限制变量只能是预先设定好的值。使用枚举可以减少代码中的 bug。

> 例如，我们为果汁店设计一个程序，它将限制果汁为小杯、中杯、大杯。这就意味着它不允许顾客点除了这三种尺寸外的果汁。
:::

:::info
某某某某已经不再支持
:::

:::warning
某某某某已经不能这么用
:::