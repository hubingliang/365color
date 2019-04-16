# 365color

[![npm](https://img.shields.io/npm/v/365color.svg)](https://github.com/hubingliang/365color)

> 一个根据日本 365 天诞生色为 idea 的颜色 api

## 起步

安装 365color

```
npm i 365color
```

在你的项目中引入 365color

```js
import { getColor } from '365color'
getColor() // 你可以直接调用 返回当天的颜色值
getColor('01-24') // 同时也支持: MM-DD/new Date(xxx)
```

## 源网站

![](https://i.loli.net/2019/04/16/5cb5b168cbb29.png)

[誕生色 一覧](http://www.daikanyamaflora.jp/birthcolor.shtml)
