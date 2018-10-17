#本脚手架是通过网络进行修改，特别鸣谢该文章的作者
[小白配置教程](https://blog.csdn.net/khxu666/article/details/79851070#commentBox)

## 本项目的MySQL为8.0版本，所以需要使用对应新的drive。主干master为ssm+jsp。

``` java
    <dependency>
      <groupId>mysql</groupId>
      <artifactId>mysql-connector-java</artifactId>
      <version>8.0.11</version>
    </dependency>
```

``` xml
    jdbc.driver=com.mysql.cj.jdbc.Driver
    jdbc.url=jdbc:mysql://localhost:3306/Test?characterEncoding=utf8&useSSL=false&serverTimezone=UTC&rewriteBatchedStatements=true
```
## 分支freeMaker为ssm+freeMaker脚手架，更改了spring的版本，为了匹配相应的freeMaker。
``` xml
    <spring.version>4.3.6.RELEASE</spring.version>
    <dependency>
      <groupId>org.freemarker</groupId>
      <artifactId>freemarker</artifactId>
      <version>2.3.23</version>
    </dependency>
```