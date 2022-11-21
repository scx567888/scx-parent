<p align="center">
    <img src="https://scx.cool/logos/scx-parent-logo.svg" width="300px"  alt="scx-logo"/>
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

English | [简体中文](./README.zh-CN.md)

> Base parent pom for SCX project

## Maven

``` xml
<parent>
    <groupId>cool.scx</groupId>
    <artifactId>scx-parent</artifactId>
    <version>{version}</version>
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

![Alt](https://repobeats.axiom.co/api/embed/597e26caedc0b7bd9b5b4293298c75ef4f9d21e7.svg "Repobeats analytics image")