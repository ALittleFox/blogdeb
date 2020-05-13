---
title: "Neutrino安装"
date: 2020-05-13T14:09:08+08:00
draft: false
tags: ["neutrino中文","neutrino"]
---
### 安装Neutrino

#### 要求
安装 `Neutrino` 需要 `node.js 10+`，`yarn` 或者 `npm`。至少你应该安装 `Neutrino` 或者 `Neutrino` 中间件，比如 `@neutrinojs/react`。

#### 创建新工程
最快的方法是使用脚手架工具 `@neutrinojs/create-project`。 如果你不想使用命令行帮助程序，请按照以下步骤进行手动安装说明。

#### Yarn 安装
在你的项目目录下运行下面的命令。把下文中的 `MIDDLEWARE` 替换为你想要安装的中间件的名字

```bash
yarn add --dev neutrino MIDDLEWARE
```
例如，如果你想要使用 `Neutrino` 的 React 预设（中间件）来构建项目：

```bash
yarn add --dev neutrino @neutrinojs/react
```
#### npm 安装
在你的项目目录下运行下面的命令。把下文中的 `MIDDLEWARE` 替换为你想要安装的中间件的名字

```bash
npm install --save-dev neutrino MIDDLEWARE
```
例如，如果你想要使用 `Neutrino` 的 `React` 预设（中间件）来构建项目：

```bash
npm install --save-dev neutrino @neutrinojs/react
```

####  入门
请继续阅读文档以获取有关 `Neutrino` 使用和默认项目布局的说明
