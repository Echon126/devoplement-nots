#### 一、mysql事务

##### 1.事务基础概念

事务是访问和更新数据库的程序执行单元，事务中可能包含一个或多个sql语句，这些语句要么都执行，要么都不执行，作为关系型数据库。



![](C:\Users\25144\Desktop\1174710-20190128200647649-2138221098.png)



##### 2.ACID特性

​	ACID是衡量事务的四个特性：

- 原子性（Atomicity，或称不可分割性）
- 一致性（Consistency）
- 隔离性（Isolation）
- 持久性（Durability）



##### 3.事务的隔离级别

SQL标准中定义了四种隔离级别，并规定了每种隔离界别下上述问题是否存在，一般来说，隔离级别越低，系统开销越低，可支持的并发越高，但是隔离性也越差。隔离级别与读问题的关系如下：

![](C:\Users\25144\Desktop\sgljb2.png)





https://www.cnblogs.com/kismetv/p/10331633.html (知识链接)



https://juejin.im/post/5e7ef0bae51d4546f16bb3fb











