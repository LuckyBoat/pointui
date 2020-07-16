# 一个基于Vue的UI框架库

[![Build Status](https://travis-ci.org/mxylovezh/pointui.svg?branch=master)](https://travis-ci.org/mxylovezh/pointui)

## 作者: 舟

## 效果链接

[基于Vue的UI库](https://luckyboat.github.io/pointui/)

## 介绍
基于 Vue 做的 UI 框架
## 开始使用

## 安装

1. 添加 Css 样式

请在使用之前开启 border-box
在安装app.js设置样式
```css
*{ padding: 0; margin: 0; box-sizing: border-box; }
```
需要设置默认颜色和变量

2. 安装 pointui
 
```shell script
npm install --save pointui
```

3. 引入方法
```javascript
import {Button,ButtonGroup,Icon} from 'pointui'
import 'point/dist/index.css'

export default {
  name: 'app',
  components: {
    'g-button': Button,
    'g-icon': Icon 
  }
}
```



