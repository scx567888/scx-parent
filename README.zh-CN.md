<p align="center">
    <img src="https://scx.cool/logos/scx-parent-logo.svg" width="300px"  alt="scx-parent-logo"/>
</p>
<p align="center">
    <a target="_blank" href="https://github.com/scx567888/scx-parent/actions/workflows/ci.yml">
        <img src="https://github.com/scx567888/scx-parent/actions/workflows/ci.yml/badge.svg" alt="CI"/>
    </a>
    <a target="_blank" href="https://central.sonatype.com/artifact/cool.scx/scx-parent">
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

简体中文 | [English](./README.md)

> SCX 项目的基础父 pom

## Maven

``` xml
<parent>
    <groupId>cool.scx</groupId>
    <artifactId>scx-parent</artifactId>
    <version>{version}</version>
    <relativePath/>
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

![Alt](https://repobeats.axiom.co/api/embed/a5c465a2af6f38e88ba2481efd555dc1500460cd.svg "Repobeats analytics image")
