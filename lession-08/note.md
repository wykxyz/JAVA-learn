## java learn note 08

* 01  MetaClass 描述类的类 ； 虚拟机第一次加载一个类的时候，生成一个MetaClass 的实例 ； 不能手动实例化（new）， 由虚拟机创建
* 02  java反射机制是在运行状态中，对于任意一个类，都能够知道这个类的所有属性和方法；对于任意一个对象，都能调用它的任意一个方法和属性；这种动态获取信息以及动态调用对象的方法和功能成为java语言的反射机制
> 反射机制可以突破访问权限限制（可修改私有变量） 

* 03  获得对应类型或者实例的Class实例
```java
String s1 = null;
System.out.println(s1.getClass() == String.class);
```
> 同一个类只有一个class实例， 用==判断为真

* 04  针对抽象编程，可以提高灵活性，可移植性，便于以后替换某些组件
* 05  socket编程的话， 推荐去慕课网，看Java socket应用，多线程也有哦

## say

* 01  有必要花些时间来搞清楚一些程序的结构，试着用图去记一下比较好
* 02  先理清思路，再写代码； 多修改，求质量