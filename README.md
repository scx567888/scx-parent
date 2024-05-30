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

English | [简体中文](./README.zh-CN.md)

> Base parent pom for SCX project

## Maven

``` xml
<parent>
    <groupId>cool.scx</groupId>
    <artifactId>scx-parent</artifactId>
    <version>{version}</version>
    <relativePath/>
</parent>
```

## Quick start

#### 1. Copy [script.ps1](./script.ps1) to your project root .

```
your-project
    ├── src
    ├── pom.xml
    └── script.ps1
```

#### 2. Edit properties in your pom.xml .

```xml
<properties>
    <scx.mainClass>{your.main.class}</scx.mainClass>
</properties>
```

#### 3. Run [script.ps1](./script.ps1) with PowerShell .

```
1. Run project
2. Build project (excluding dependencies)
3. Build project (including dependencies)
4. Copy dependencies only
0. Exit
```

For more information, see [docs](https://scx.cool/docs/scx/index.html)

## Stats

![Alt](https://repobeats.axiom.co/api/embed/a5c465a2af6f38e88ba2481efd555dc1500460cd.svg "Repobeats analytics image")
