# vue-book

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).



## 安装less
npm install less less-loader --save-dev


## 通过相同的路径/book 
- 请求的方式不同实现获取不同的资源
- GET获取  url路径传递数据
- PUT修改  url+reqbody
- POST增加 reqbody
- DELETE删除 url