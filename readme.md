## 一:Vue.js简介
### 1.Vue.js是什么
    **Vue.js**也称为Vue,读音/vju:,类似view，错误读音v-u-e
    版本：v1.0,v2.0
    
  + 是一个构建用户界面的框架
  + 是一个轻量级MVVM(Model-View-ViewModel)框架
  + 数据驱动 + 组件化的前端开发（核心思想）
  + 通过简单的API实现响应式的数据绑定，和组合的视图组件
  + 容易上手，小巧
  
  参考:[官网](https://cn.vuejs.org/)

## 2.Vue和angular的区别
 ### 2.1 angular
    + 上手较难
    + 指令以ng-xxx开头
    + 所有属性和方法都存储在$scope中
    + 由google维护
 ### 2.2 vue
    + 简单、易学、更轻量
    + 指令以v-xxx开头
    + HTML代码+JSON数据，再创建一个vue实例
    + 由个人维护：**尤雨溪**，华人，目前就职于阿里巴巴
    
    共同点:都不兼容低版本
    对比:github上vue是angular的三倍
    
## 二:起步
### 1.下载核心库(使用npm)
    npm init --test
    npm install vue --save
    最新版本:v2.6.10(2019年10月26日)
    
    vue2.0和vue1.0相比，更大的变化就是引入Virtual DOM(虚拟DOM),页面的更新效率会更高，效率会跟快
### 2.Hello World
    js：
        new Vue({
            el:"itany" //指定关联的选择器
            data:{//存储数据
                msg:'Hello World',
                name:'tomm'
            }
        })
    html:
    <div id = "itany">
    
    </div>
