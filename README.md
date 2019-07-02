Vue移动端商城项目
项目概述：项目采用了vuex、Vue-router、Vue-resource以及ES6语法，采用组件化思想搭建整个项目，从而使部分组件可以重复利用 。主要功能有：主页列表，商品列表，新闻列表，图文列表，评论列表，购物车等；

项目细节：
1. 页面布局，首页轮播图，图文资讯里的滑动标签、评论模块等主要是由MUI，Mint-UI，Bootstrap，vue-lazyload以及部分HTML/CSS 实现的；
2. 采用Vue-router搭建项目路由；Vuex管理组件状态，来实现修改购物车数据；利用Vue-resource/GET通过API接口请求JSON数据并渲染，用POST存入新添加评论。
3. 利用Vue.js 中的双向绑定，父子组件相互传值，来实现数据的传递与渲染
4. 利用webpack打包。
# Test

图片示例：
![image](https://github.com/qianggezhenshuai666/vue-Shangcheng/blob/master/images/IMG01.JPG)

![image](https://github.com/qianggezhenshuai666/vue-Shangcheng/blob/master/images/IMG02.JPG)
