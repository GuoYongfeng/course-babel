# babel

## 仓库的使用方式

```
$ npm install
```

babel命令
```
$ npm run build
```

babel和gulp结合

```
$ npm run dev
```

## babel相关

babel -> 分拆

单独维护


```
npm instlal babel --save-dev
```

babel

- babel-core
- babel-cli
- babel-preset-x
- babel-plugin-x
- babel-polyfill
- .......

## babel-cli

- babel
- babel-node

## presets

一系列的plugin插件组合 完成es2015

## plugin

每一个插件只做一件事情

```
babel-plugin-transform-runtime
```

## babel-core

API -> code

## babel-loader

依赖关系
babel-core 一起下载

## loose

- normal
- loose

## 模块化规范

```
define(['a'], function(){

})
```

```
define(function(require, module, exports){

})
```

```
var fs = require('fs')

module.exports = function(){

}
```

```
import React from 'react';

export default a;
```

## 兼容IE8

## API 浏览器运行

兼容

Array.from -> API

报错了
浏览器

polyfill

## babel-polyfill

```
require('babel-polyfill')
```

API

## 生态

- plugin 扩展插件
- gulp-babel
- webpack
- browserify
- mocha/karma

## gulp


- 代码解析
- 打包合并
- 压缩 混淆
- md5


上线
