# 笔记

## 脚手架的目录结构
vue_test
├─ public
│  ├─ favicon.ico   页签图标
│  └─ index.html    主页面
├─ src
│  ├─ App.vue   汇总所有文件
│  ├─ assets    存放静态资源
│  │  └─ logo.png
│  ├─ components    存放组件
│  │  └─ HelloWorld.vue
│  └─ main.js   入口文件
├─ .gitignore git   版本管制忽略的配置
├─ babel.config.js  babel的配置文件
├─ jsconfig.json    
├─ package-lock.json    包版本控制文件
├─ README.md            应用描述文件
├─ package.json         应用包配置文件
└─ vue.config.js        

## 关于不同版本的vue
- vue.js与vue.runtime.xxx.js的区别：
        (1).vue.js是完整版的vue,包含核心功能和模板解析器
        (2).vue.runtime.xxx.js是运行时版本的vue，只包含了核心功能：没有解析器
- 因为vue.runtime.xxx.js是没有模板解析器，所以不能使用template配置项，需要使用
    redner函数接收到createElement函数去指定具体内容。

## vue.config.js配置文件
    使用vue inspect >out.js 可以查看到vue脚手架的默认配置
    使用vue.config.js可以对脚手架进行个性化定制
    