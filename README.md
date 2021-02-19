<h1 align="center">vueAdmin</h1>

## 简介

vueAdmin 是一个基于 vue 开发的后台管理系统的前端页面展示项目模板
是由 vue-cli4 和 elemnet-ui 搭建实现的。
项目采用弹性盒（flex）布局，简单适配移动端。

## 开发

```bash
# 进入项目目录 下载依赖 启动
cd vueAdmin

npm install/yarn

npm run/ yarn serve

# 映射切换
npm install --registry=https://registry.npm.taobao.org
# 如遇到node-sass的问题，可尝试
npm rebuild node-sass
```

## 打包发布

````bash
# 构建生产环境
npm run/yarn build


```javascript
// 建议首先查看路由文件(了解项目路由以及如何进行动态生成前端路由)
// 页面查看顺序(登录页（views/Login）-> 首页(views/Home/Dashboard))，其中views/Home为其他页面的公共引用部分
// 与后端交互接口（请查看service/index.ts，数据由mock.js产生；实际开发请查看util/request.ts）
// 后台系统包括了登录，异步生成路由，echarts数据可视化，table表增删改查等功能，希望该demo示例可以帮助到有需要的朋友快速上手
// 根据vue-cli示例，主页面index.vue中会采用vue2的写法，在子组件中则有较大的变化，请仔细查看区别
````
