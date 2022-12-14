# money-parent
## 默认引入依赖
~~~xml
<!-- lombok -->
<dependency>
    <groupId>org.projectlombok</groupId>
    <artifactId>lombok</artifactId>
</dependency>
<!-- 工具集 -->
<dependency>
    <groupId>cn.hutool</groupId>
    <artifactId>hutool-all</artifactId>
</dependency>
~~~
## 版本声明
~~~xml
<properties>
    <java.version>1.8</java.version>
    <maven.compiler.source>1.8</maven.compiler.source>
    <maven.compiler.target>1.8</maven.compiler.target>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
    <project.reporting.outputEncoding>UTF-8</project.reporting.outputEncoding>

    <spring-boot.version>2.6.10</spring-boot.version>
    <spring-boot-admin.version>2.4.3</spring-boot-admin.version>
    <mybatis-plus.version>3.5.2</mybatis-plus.version>
    <mybatis-plus-generator.version>3.5.1</mybatis-plus-generator.version>
    <xxl-job.version>2.3.1</xxl-job.version>
    <qiniu.version>7.7.0</qiniu.version>
    <caffeine.version>2.9.2</caffeine.version>
    <jjwt.version>0.11.2</jjwt.version>
    <springdoc-openapi.version>1.5.11</springdoc-openapi.version>
    <hutool.version>5.8.4</hutool.version>
    <jackson.version>2.13.3</jackson.version>
    <log4j.version>2.18.0</log4j.version>
</properties>
~~~
## 使用
~~~xml
<parent>
    <groupId>com.money</groupId>
    <artifactId>money-parent</artifactId>
    <version>1.0.0</version>
    <relativePath/>
</parent>
~~~