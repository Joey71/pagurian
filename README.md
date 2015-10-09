# Pagurian
[ ![Build Status](https://img.shields.io/travis/joyent/node/v0.6.svg) ](http://www.pagurian.com)[ ![tag-1.3.0](https://img.shields.io/badge/tag-v1.3.0-orange.svg) ](https://github.com/hypers/pagurian/tree/v1.3.0)[ ![License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat) ](http://mit-license.org/)

一个管理系统的前端框架

## 开发及构建
用户可以在 Pagrian 的基础上进行二次开发

### 目录结构

```
Pagurian
├── [.] .build
├── dist/                   //发布目录
│   ├── lib/
│   ├── modules/
│   ├── plugins/
│   ├── resources/
│   └── templates/
├── docs/                   //开发文档
│   ├── api-datatable.md
│   └── api-*.md
├── [.] node_modules/           //Grunt依赖的NodeJs 模块
├── src/                    //开发目录
│   ├── lib/                //框架依赖的基础库
│   ├── modules/            //业务模块
│   ├── plugins/            //插件模块
│   ├── resources/          //css,images,fonts
│   └── templates/          //handlebars 模版文件
├── test/                   //测试
├── Gruntfile.js
├── package.json
└── pagurian.js
```

### 构建工具
Pagurian 使用 [Grunt](http://gruntjs.com/) 构建项目。

首先全局安装 Grunt

```
npm install -g grunt-cli
```

Clone 项目文件:

```
git clone https://github.com/hypers/pagurian.git
```

安装grunt插件:

```
cd pagurian
npm install
```

接下来，执行 `grunt`：

```
grunt
```

## 参考、使用的项目
- [Sea.js v2.2.1](https://github.com/seajs/seajs) ([MIT License](https://github.com/seajs/seajs/blob/master/LICENSE.md))[V]
- [FontAwesome v4.0.1](https://github.com/FortAwesome/Font-Awesome/) ([CC BY 3.0 License](http://creativecommons.org/licenses/by/3.0/))
- [Bootstrap v3.0.3](https://github.com/twbs/bootstrap) ([MIT License](https://github.com/twbs/bootstrap/blob/master/LICENSE))
- [bootstrap-datepicker.js v1.2](http://www.eyecon.ro/bootstrap-datepicker/) ([Apache License 2.0](http://www.eyecon.ro/bootstrap-datepicker/js/bootstrap-datepicker.js))
- [Datatabls v1.9.4](http://www.datatables.net/)([MIT License](http://www.datatables.net/license/mit))
- [Echarts v2.0](http://echarts.baidu.com/)([MIT License](https://github.com/ecomfe/echarts/blob/master/LICENSE.txt))
- [jQuery v1.9.1](http://jquery.com/)([MIT License](https://jquery.org/license/))
