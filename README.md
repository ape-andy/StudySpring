#一、Spring Boot入门
##1、Spring Boot简介
简化spring应用开发的一个框架；
整个spring技术栈的一个大整合；
J2EE开发的一站式解决方案；
##2、微服务
2014，martin fowler
微服务：架构风格
一个应用应该是一个小型服务；可以通过HTTP方式进行互通；
每一个功能元素最终都是一个可独立替换和独立升级的软件单元
[详细参照微服务文档](https://martinfowler.com/articles/microservices.html#MicroservicesAndSoa)
##3、环境配置
http://www.gulixueyuan.com/ 谷粒学院

环境约束

–jdk1.8：Spring Boot 推荐jdk1.7及以上；java version "1.8.0_112"

–maven3.x：maven 3.3以上版本；Apache Maven 3.3.9

–IntelliJIDEA2017：IntelliJ IDEA 2017.2.2 x64、STS

–SpringBoot 1.5.9.RELEASE：1.5.9；

统一环境；
### 1、MAVEN设置；

给maven 的settings.xml配置文件的profiles标签添加

```xml
<profile>
  <id>jdk-1.8</id>
  <activation>
    <activeByDefault>true</activeByDefault>
    <jdk>1.8</jdk>
  </activation>
  <properties>
    <maven.compiler.source>1.8</maven.compiler.source>
    <maven.compiler.target>1.8</maven.compiler.target>
    <maven.compiler.compilerVersion>1.8</maven.compiler.compilerVersion>
  </properties>
</profile>
```

### 2、IDEA设置

整合maven进来；

![idea设置](images/搜狗截图20180129151045.png)



![images/](images/搜狗截图20180129151112.png)