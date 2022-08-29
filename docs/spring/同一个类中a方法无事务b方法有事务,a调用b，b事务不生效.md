### 原因

spring事务是通过代理实现的，使用this方法时候使用的并不是代理对象，所以事务不生效。

### 解决方法

获取代理对象，调用代理对象的方法。

```java
//使用AopContext.currentProxy()获取当前类的代理对象 强转即可
XxxService proxy =(XxxService) AopContext.currentProxy();
//使用代理对像调用方法即可
proxy.xxx();
```



