﻿# money-parent
## 依赖
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
    <spring-boot.version>2.7.12</spring-boot.version>
    <mysql.version>8.0.33</mysql.version>
    <mybatis-plus.version>3.5.3.2</mybatis-plus.version>
    <mybatis-plus-generator.version>3.5.3.2</mybatis-plus-generator.version>
    <xxl-job.version>2.3.1</xxl-job.version>
    <qiniu.version>7.13.1</qiniu.version>
    <caffeine.version>3.1.6</caffeine.version>
    <jjwt.version>0.11.5</jjwt.version>
    <spring-boot-admin.version>2.4.3</spring-boot-admin.version>
    <springdoc-openapi.version>1.7.0</springdoc-openapi.version>
    <hutool.version>5.8.20</hutool.version>
    <jackson.version>2.13.5</jackson.version>
    <fastjson.version>2.0.32</fastjson.version>
    <log4j.version>2.20.0</log4j.version>
</properties>
~~~
## 使用
pom.xml
~~~xml
<parent>
    <groupId>com.money</groupId>
    <artifactId>money-parent</artifactId>
    <version>{latest-version}</version>
    <relativePath/>
</parent>

<repositories>
    <repository>
        <id>github</id>
        <url>https://maven.pkg.github.com/ycf1998/money-parent</url>
    </repository>
</repositories>
~~~
settings.xml
~~~xml
<servers>
    <server>
        <id>github</id>
        <username>ycf1998</username>
        <password>TOKEN</password>
    </server>
</servers>
~~~
