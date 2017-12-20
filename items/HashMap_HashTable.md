
#### 2.HashMap、Hashtable的区别？
[参考博客](http://blog.csdn.net/java2000_net/article/details/2512510)


|         |    |    |         |    |    |         |          |
| --------   | -----  | ----  | -----  | ----  | ----- | ----  | -----  |
| HashMap     | 线程不安全 |   效率高一点     | 允许有null的键和值0 |   方法不是Synchronize的要提供外同步     | 有containsvalue和containsKey方法|   HashMap是java1.2引入的，Map interface 的一个实现     | HashMap是Hashtable的轻量级实现|
| HashTable        |   线程安全   |   效率稍低   | 不允许有null的键和值 |   方法是是Synchronize的     | 有contains方法|   Hashtable 继承于Dictionary 类    | Hashtable 比HashMap 要旧 |
