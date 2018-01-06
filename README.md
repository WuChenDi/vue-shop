# 基于Vue2.0 + vue-router + webpack + ES6/7 + nodejs + express 实现web端购物商城网站

[vuejs](https://vuejs.org/)初学（WuChenDi）


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
通过npm安装本地服务第三方依赖模块(需要已安装[Node.js](https://nodejs.org/))
#### 注意：由于涉及大量的 ES6/7 等新属性，node 需要 6.0 以上版本 
```
cd vue-shop

npm install 或 cnpm install(个人比较喜欢使用后者，下载依赖模块速度较快)

npm run dev

```

## 项目效果图
<img src="https://github.com/WuChenDi/vue-shop/blob/master/screenshots/index.png" width="1182" height="892"/>
<img src="https://github.com/WuChenDi/vue-shop/blob/master/screenshots/login.png" width="1182" height="892"/>
<img src="https://github.com/WuChenDi/vue-shop/blob/master/screenshots/about.png" width="1182" height="892"/>
<img src="https://github.com/WuChenDi/vue-shop/blob/master/screenshots/analysis.png" width="1182" height="892"/>
<img src="https://github.com/WuChenDi/vue-shop/blob/master/screenshots/bankChooser.png" width="1182" height="892"/>
<img src="https://github.com/WuChenDi/vue-shop/blob/master/screenshots/checkOrder.png" width="1182" height="892"/>
<img src="https://github.com/WuChenDi/vue-shop/blob/master/screenshots/orderList.png" width="1182" height="892"/>


