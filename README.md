# reset-css
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/BoizZ/reset-css/master/LICENSE)

统一浏览器的样式特性。针对PC端、移动端及移动客户端分离代码，更加轻量，减少冗(I)余(E)。基于`SASS`，支持快速拓展，个性化样式。

## 文件目录

``` bash
.
├── demo # 示例
├── dist # 1.2.2 版本
├── public # 2.0.0 版本
│   ├── main # 通用重置样式表：包含IE、MacOS Safari 及 手机重置样式表 的所有特性
│   ├── mobile # 手机重置样式表： 使用无衬线字体、去除IOS默认表单样式、去除a及表单点击时的蓝边及灰色背景
│   └── native # 原生应用重置样式表： 禁止长按链接与图片弹出菜单、禁止选中文字，及 手机重置样式表 的所有特性
├── sass # 2.0.0 的 sass 目录
├── .gitignore
├── gruntfile.js
├── package.json
└── README.md
```
