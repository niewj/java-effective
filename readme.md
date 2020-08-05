**为了看起来没有那么多repositories, 使用了maven父子模块把几个modules集合到一块**
#### _java-miscellaneous_
**submodules:**
- concurrent
```并发练习代码```
- javagui
```java 图形界面```
- tutos
```教程随练代码```
- zoo-spring-mybatis-web (webapp-spring-mybatis)
```一个webapp模板，里面集中一些web工具或者代码段。```
- *spring-rabbitmq
```spring集成rabbitmq配置```
- *springmvc-mybatis-demo
```Java 语言 代码 留存```
- *springboot-demo1
```springboot-demo1```
- *spring-mvc-rest-exhandler
```spring-mvc-rest-exhandler```
- *kafka-lessons
```kafka-lessons```


```
<modules>
    <module>concurrent</module>
    <module>tutos</module>
    <module>java-gui</module>
    <module>zoo-spring-mybatis-web</module>
    <module>zoo-kafka-lessons</module>
    <module>zoo-springboot-demo1</module>
</modules>
```