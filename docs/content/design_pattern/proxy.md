# 代理模式

## 1 概念

&emsp;&emsp;代理模式（Proxy Pattern）是指实现一个类代表另一个类的功能，为其他对象提供一种代理以控制对这个对象的访问。

## 2 知识点

### 2.1 适用场景

&emsp;&emsp;不方便直接访问对象时，为不宜直接访问的对象提供一个访问层。

### 2.2 使用步骤

1. 创建抽象类（Subject），定义原对象和代理对象的共用接口；
2. 创建原对象（Real Subject），定义需要代理的真正实体，继承于抽象类；
3. 创建代理（Proxy），保存一个引用使得代理可以访问实体，继承于抽象类，实现对实体的替代；

在客户端中使用时，直接实例化代理，并访问代理即可。