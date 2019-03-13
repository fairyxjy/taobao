# mymall

实现用户登录、注册、添加购物车、购买结算、轮播图、分页、路由跳转等功能

1.vue-router可实现单页面应用，不刷新跳转,还可以实现页面间传参等其他功能;
2.利用vuex技术，保存用户是否处在登录状态;
3.将数据保存到localStorage,进而实现购物车功能（删除、添加、价格计算等）;
4.在全局引入axios跨域请求，在后端引入jsonp并配置;
5.用swiper滑动,切换页面;
6.使用vue-lazyload实现图像懒加载;
7.使用axios的http拦截器添加对响应状态码的判断，来决定是跳转到登录页面还是留在当前页面继续获取数据;
7.使用iscroll实现移动端滚动;
8.使用better-scroll实现上拉加载,下拉刷新;
9.使用rem实现解决移动端页面自适应问题

> test

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

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
