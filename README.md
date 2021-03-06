# [vue-ts-bus](https://github.com/zjhcn/vue-ts-bus)
[![](https://img.shields.io/badge/Powered%20by-jslib%20base-brightgreen.svg)](https://github.com/yanhaijing/jslib-base)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/zjhcn/vue-ts-bus/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/zjhcn/vue-ts-bus.svg?branch=master)](https://travis-ci.org/zjhcn/vue-ts-bus)
[![Coveralls](https://img.shields.io/coveralls/zjhcn/vue-ts-bus.svg)](https://coveralls.io/github/zjhcn/vue-ts-bus)
[![npm](https://img.shields.io/badge/npm-1.0.4-orange.svg)](https://www.npmjs.com/package/vue-ts-bus)
[![NPM downloads](http://img.shields.io/npm/dm/vue-ts-bus.svg?style=flat-square)](http://www.npmtrends.com/vue-ts-bus)
[![Percentage of issues still open](http://isitmaintained.com/badge/open/zjhcn/vue-ts-bus.svg)](http://isitmaintained.com/project/zjhcn/vue-ts-bus "Percentage of issues still open")


## :bookmark_tabs: 文档
[API文档](./doc/api.md)

## :star: 特性

- 支持ES6+或TypeScript编写源码，编译生成生产代码
- 多环境支持（支持浏览器原生，支持AMD，CMD，支持Webpack，Rollup，fis等，支持Node）
- 集成[jsmini](https://github.com/jsmini)

## :pill: 兼容性
单元测试保证支持如下环境：

| IE   | CH   | FF   | SF   | OP   | IOS  | Android   | Node  |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ----- |
| 9+   | 29+ | 55+  | 9+   | 50+  | 9+   | 4+   | 4+ |

**注意：编译代码依赖ES5环境**

## :open_file_folder: 目录介绍

```
.
├── demo 使用demo
├── dist 编译产出代码
├── doc 项目文档
├── src 源代码目录
├── test 单元测试
├── CHANGELOG.md 变更日志
└── TODO.md 计划功能
```

## :rocket: 使用者指南

通过npm下载安装代码

```bash
$ npm install --save vue-ts-bus
```

如果你是node环境

```js
var base = require('vue-ts-bus');
```

如果你是webpack等环境

```js
import base from 'vue-ts-bus';
```

如果你是requirejs环境

```js
requirejs(['node_modules/vue-ts-bus/dist/index.aio.js'], function (base) {
    // xxx
})
```

如果你是浏览器环境

```html
<script src="node_modules/vue-ts-bus/dist/index.aio.js"></script>
```

## :kissing_heart: 贡献者指南
首次运行需要先安装依赖

```bash
$ npm install
```

一键打包生成生产代码

```bash
$ npm run build
```

运行单元测试:

```bash
$ npm test
```

> 注意：浏览器环境需要手动测试，位于`test/browser`

修改 package.json 中的版本号，修改 README.md 中的版本号，修改 CHANGELOG.md，然后发布新版

```bash
$ npm run release
```

将新版本发布到npm

```bash
$ npm publish
```

## 贡献者列表

[contributors](https://github.com/zjhcn/vue-ts-bus/graphs/contributors)

## :gear: 更新日志
[CHANGELOG.md](./CHANGELOG.md)

## :airplane: 计划列表
[TODO.md](./TODO.md)