# vue-cli
使用vue-cli + webpack实现前后分离
# 安装脚手架搭建
1.npm install vue-cli  初始化vue-cli<br/>
2.vue init webpack my-project  使用webpack模版新建一个项目 my-project<br/>
3.cd my-project 安装依赖并运行<br/>
  npm install<br/>
  npm run dev<br/>

# 配置文件
-src/-------------- 项目源代码 </br>
  APP.vue | main.js ---------- 入口文件</br>
  asset/ --------- 存放图片、字体、pdf等的文件夹</br>
  components/ ---------------- 组件目录</br>
  router/  ----------------- 路由目录</br>

-.babelrc ------------------ babel 配置文件</br>   
-index.html ---------------- HTML 模版</br>
-package.json -------------- npm 配置文件</br>
-README.md ----------------- 项目帮助文档</br>
-webpack.config.js --------- webpack 配置文件