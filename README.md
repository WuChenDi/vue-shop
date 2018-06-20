# 基于Vue2.0 + vue-router + webpack + ES6/7 + nodejs + express 实现web端购物商城网站


## 前端构架
***
- 页面结构(H5,CSS3,原生JS)
- 框架(基于Vue脚手架:vue-cli)进行搭建
- 数据请求处理框架(vue-resource或者Axios)
- Vue-Router进行路由处理
- 使用json-server模拟REST API(目前项目使用express)

## 目前项目已实现功能
***
1. 登录
2. 注册 (没有实现，点击按钮跳转回登录页面)
3. 首页数据的展示
4. 产品数据与最新消息的展示
5. 商品详情页
6. 购物车
7. 购物确认银行支付选择
8. 购买订单 (排序 ( 高->低 ) ) 

## 项目运行
***
通过npm安装本地服务第三方依赖模块(需要已安装[Node.js](https://nodejs.org/ "nodejs"))
#### 注意：由于涉及大量的 ES6/7 等新属性，node 需要 6.0 以上版本 
```
cd vue-shop

npm install 或 cnpm install(个人比较喜欢使用后者，下载依赖模块速度较快)

npm run dev

```

## 总结
- 了解vue - 数据渲染、前端模块化、路由
- 熟悉VueJs的接口功能 - 指令的用法、选项的用法
- 了解vue组件 - 组件的交互
- 了解vue工程化方案 - 单文件组件Webpack测试数据
- vue项目的搭建流程
- 使用Ajax请求后端数据
- 组件的设计与交互
- 路由和子路由(嵌套路由通信)

## 目录结构

```
.
├── build
├── config
├── screenshots
├── src
│   ├── assets
│   │   ├── banks
│   │   ├── images
│   │   └── slideShow
│   ├── components
│   │   ├── base
│   │   │   ├── chooser.vue
│   │   │   ├── counter.vue
│   │   │   ├── datepicker.vue
│   │   │   ├── dialog.vue
│   │   │   ├── multiplyChooser.vue
│   │   │   └── selection.vue
│   │   ├── bankChooser.vue
│   │   ├── checkOrder.vue
│   │   ├── HelloWorld.vue
│   │   ├── layout.vue
│   │   ├── logForm.vue
│   │   ├── regForm.vue
│   │   └── slideShow.vue
│   ├── pages
│   │   ├── detail
│   │   │   ├── analysis.vue
│   │   │   ├── count.vue
│   │   │   ├── forecast.vue
│   │   │   └── publish.vue
│   │   ├── detail.vue
│   │   ├── index.vue
│   │   └── orderList.vue
│   ├── App.vue
│   └── main.js
├── static
│   └── .gitkeep
├── .babelrc
├── .editorconfig
├── .gitgnore
├── .postcssrc.js
├── db.json
├── index.html
├── package.json
└── README.md
.
```

## 项目效果图
![](/screenshots/index.png)
![](/screenshots/login.png)
![](/screenshots/about.png)
![](/screenshots/analysis.png)
![](/bankChooser.png)
![](/checkOrder.png)
![](/orderList.png)
