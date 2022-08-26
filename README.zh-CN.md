<p align="center">
    <img src="https://scx.cool/img/scx-parent-logo.svg" width="300px"  alt="scx-logo"/>
</p>
<p align="center">
    <a target="_blank" href="https://github.com/scx567888/scx-parent/actions/workflows/ci.yml">
        <img src="https://github.com/scx567888/scx-parent/actions/workflows/ci.yml/badge.svg" alt="CI"/>
    </a>
    <a target="_blank" href="https://search.maven.org/artifact/cool.scx/scx-parent">
        <img src="https://img.shields.io/maven-central/v/cool.scx/scx-parent?color=ff69b4" alt="maven-central"/>
    </a>
    <a target="_blank" href="https://github.com/scx567888/scx-parent">
        <img src="https://img.shields.io/github/languages/code-size/scx567888/scx-parent?color=orange" alt="code-size"/>
    </a>
    <a target="_blank" href="https://github.com/scx567888/scx-parent/issues">
        <img src="https://img.shields.io/github/issues/scx567888/scx-parent" alt="issues"/>
    </a>
    <a target="_blank" href="https://github.com/scx567888/scx-parent/blob/master/LICENSE">
        <img src="https://img.shields.io/github/license/scx567888/scx-parent" alt="license"/>
    </a>
</p>
<p align="center">
    <a target="_blank" href="https://github.com/eclipse-vertx/vert.x">
        <img src="https://img.shields.io/badge/Vert.x-f44336" alt="Vert.x"/>
    </a>
    <a target="_blank" href="https://github.com/FasterXML/jackson">
        <img src="https://img.shields.io/badge/Jackson-ff8000" alt="Jackson"/>
    </a>
    <a target="_blank" href="https://github.com/spring-projects/spring-framework">
        <img src="https://img.shields.io/badge/Spring Framework-d8b125" alt="Spring Framework"/>
    </a>
    <a target="_blank" href="https://github.com/brettwooldridge/HikariCP">
        <img src="https://img.shields.io/badge/HikariCP-98c510" alt="HikariCP"/>
    </a>
    <a target="_blank" href="https://github.com/apache/freemarker">
        <img src="https://img.shields.io/badge/FreeMarker-44be16" alt="FreeMarker"/>
    </a>
    <a target="_blank" href="https://github.com/bcgit/bc-java">
        <img src="https://img.shields.io/badge/Bouncy Castle-37b484" alt="Bouncy Castle"/>
    </a>
    <a target="_blank" href="https://github.com/jasypt/jasypt">
        <img src="https://img.shields.io/badge/Jasypt-29aaf5" alt="Jasypt"/>
    </a>
    <a target="_blank" href="https://github.com/coobird/thumbnailator">
        <img src="https://img.shields.io/badge/Thumbnailator-6269d3" alt="Thumbnailator"/>
    </a>
    <a target="_blank" href="https://github.com/google/guava">
        <img src="https://img.shields.io/badge/Guava-9c27b0" alt="Guava"/>
    </a>
    <br/>
    <a target="_blank" href="https://github.com/netty/netty">
        <img src="https://img.shields.io/badge/Netty-f44336" alt="Netty"/>
    </a>
    <a target="_blank" href="https://github.com/zxing/zxing">
        <img src="https://img.shields.io/badge/ZXing-ff8000" alt="ZXing"/>
    </a>
    <a target="_blank" href="https://github.com/apache/poi">
        <img src="https://img.shields.io/badge/Apache POI-d8b125" alt="Apache POI"/>
    </a>
    <a target="_blank" href="https://github.com/mysql/mysql-connector-j">
        <img src="https://img.shields.io/badge/MySQL Connector/J-98c510" alt="MySQL Connector/J"/>
    </a>
    <a target="_blank" href="https://github.com/java-native-access/jna">
        <img src="https://img.shields.io/badge/JNA-44be16" alt="Java Native Access (JNA)"/>
    </a>
    <a target="_blank" href="https://github.com/qos-ch/slf4j">
        <img src="https://img.shields.io/badge/SLF4J-37b484" alt="SLF4J"/>
    </a>
    <a target="_blank" href="https://github.com/apache/logging-log4j2">
        <img src="https://img.shields.io/badge/Apache Log4j 2-29aaf5" alt="Apache Log4j 2"/>
    </a> 
    <a target="_blank" href="https://github.com/cbeust/testng">
        <img src="https://img.shields.io/badge/TestNG-9c27b0" alt="TestNG"/>
    </a>
</p>

简体中文 | [English](./README.md)

> SCX 项目的基础父 pom

## Maven

``` xml
<parent>
    <groupId>cool.scx</groupId>
    <artifactId>scx-parent</artifactId>
    <version>{version}</version>
</parent>
```

## 快速开始

#### 1. 复制 [script.ps1](./script.ps1) 到您的项目根目录 。

```
your-project
    ├── src
    ├── pom.xml
    └── script.ps1
```

#### 2. 编辑您的 pom.xml 中的 properties 。

```xml
<properties>
    <scx.mainClass>{your.main.class}</scx.mainClass>
</properties>
```

#### 3. 使用 PowerShell 运行 [script.ps1](./script.ps1) 。

```
1. 运行项目
2. 构建项目 (不包括依赖项)
3. 构建项目 (包括依赖项)
4. 仅复制依赖项
0. 退出
```

有关更多信息，请参阅 [文档](https://scx.cool/docs/scx/index.html)

## Stats

![Alt](https://repobeats.axiom.co/api/embed/597e26caedc0b7bd9b5b4293298c75ef4f9d21e7.svg "Repobeats analytics image")