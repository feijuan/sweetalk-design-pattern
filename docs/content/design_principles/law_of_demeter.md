# 迪米特原则（最少知识原则）

## 1 概念

&emsp;&emsp;如果两个类不必彼此互相通信，那么这两个类就不应当发生直接的相互作用；如果其中一个类需要调用另一个类的某一个方法，可以通过第三者转发这个调用。

## 2 知识点

**前提**：在类的结构设计上，每一个类都应当尽量降低成员的访问权限
> 一个类包装好自己的`private`状态，不需要让别的类知道的字段或行为就不要公开

**根本思想**：迪米特原则强调类之间的松耦合
- 类之间的耦合越弱，越有利于复用；
- 一个处于弱耦合的类被修改，不会对有关系的类造成波及
