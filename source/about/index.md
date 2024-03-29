---
title: about
layout: "about"
date: 2023-10-17 10:46:33
---

Email：zhangyijie356a@gmail.com

# 技能清单

* 熟练掌握 HTML5、CSS3以及常用的响应式布局、移动端布局方案，熟悉CSS预处理器
* 熟练掌握 JavaScript、TypeScript
* 熟练掌握 Vue2.x/3.x、VueRouter、Vuex 等Vue全家桶，了解 Vue 原理与技术栈
* 熟练掌握 ElementUI、VantUI 等业界UI框架以及周边生态应用
* 熟悉原生小程序开发、Taro.js开发，能独立完成小程序的项目框架搭建、开发、测试及部署
* 熟悉前端工程化，熟悉 Webpack、Vite、Gulp 等构建工具
* 熟悉 Node.js，了解常用的 Node 模块，有 Node 框架搭建经验，有后端开发经验
* 了解 MySQL 和 MongoDB 数据库管理和使用
* 英语-cet4/cet6

# 工作经历

## 某公司（ 2022年5月 ~ 2023年8月）

### 关系图模块重构
* 重构关系图组件，使用antv-g6对关系图数据进行可视化，替换项目中原先使用的ECharts，减少冗余代码，保持代码清晰
* 使用antv-g6自定义节点的API实现数据翻页，完善数据过多时的用户体验
* 使用简化diff算法，完成关系图树形数据更新，以保持原有节点位置的不变，减少不必要的节点操作以提升页面性能

### 流程管理模块开发
* 使用monorepo的方式完成项目的改造，将组件库与业务代码分离，保持项目整洁，提高开发效率
* 使用JSX的完全开发能力，完成流程图组件的开发，精细化控制每个类型节点的权限，提高了组件的适用范围
* 设计并开发Table-v2表格组件、Form-v2表单组件，采用JSON配置化设计，提高开发效率

## 某互联网公司（ 2021年5月 ~ 2022年4月）

### 相册小程序
* 使用Taro3+Vue3开发而来，满足跨端开发需求，简化开发流程，为用户提供了多端的使用体验
* 针对长列表导致手机运行缓慢的问题，使用虚拟列表优化列表性能，提高小程序的运行效率
* 利用Vue3的composition api实现状态管理，满足基本的响应式需求，提高了小程序的可维护性
* 通过cms管理小程序中用到的静态资源以及所需的配置项，提高产品的可配置性和可扩展性

### 类微博小程序

* 使用Python和OpenCV，完成图片拼接功能。使用定时任务触发拼图功能，减轻云服务器的压力，
* 使用原生小程序完成前端的开发工作，开发的页面具有高保真度和良好的用户体验
* 使用富文本编辑器实现基础的图文混合输入功能，提高了用户的输入体验
* 对于夜晚自动换肤的需求，使用css变量定义两套主题色，实现主题的切换，提高用户体验
* 利用微信小程序的消息订阅接口，实现预约并通知的功能，使用云函数定时调用网关查询是否有需要发送的消息，提高系统的实时性

## 某医疗软件公司 （ 2019年3月 ~ 2021年4月 ）

### 系统重构（管理系统）

* 实现权限管理和路由控制，根据不同的用户组展示不同的菜单。使用Vue Router的beforeRoute钩子函数进行重定向，以确保用户只能访问他们有权限访问的路由
* 利用Element提供的动态表单功能，将表单元素转化为JS数组，并动态加载数据请求接口和远程搜索功能，以减少代码冗余和提高维护性
* 将表格组件与RESTful请求接口封装，以减少重复代码和提高开发效率。同时，利用Webpack提供的动态导入功能，实现页面的批量动态加载，以减少代码量，提高开发体验