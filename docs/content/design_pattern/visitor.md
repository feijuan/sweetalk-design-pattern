# 访问者模式

## 1 概念

访问者模式：表示一个作用于某对象结构中的各元素操作。可以再不改变元素的类的前提下定义于这些元素的新操作。

## 2 知识点

目的：把处理从数据结构中分离出来。

访问者模式，把数据结构和作用于结构上的操作之间的耦合解脱开，使得操作集合可以相对自由地演化。

优点：增加新的操作很容易。访问者模式将有关的行为集中到一个访问者对象中。

缺点：增加新的数据结构变得困难。