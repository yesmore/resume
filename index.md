### 熙的简历<img width='130' style='float:right;' src='https://cdn.jsdelivr.net/gh/yesmore/img/img/avatar.png'>

- 性别：男                                          年龄：21
- 电话：+86 13689662535              邮箱：3224266014@qq.com
- 求职岗位：**前端开发工程师**           在线简历：https://yesmore.cc/resume/
- 个人博客：https://yesmore.cc     Github：https://github.com/yesmore

### 教育背景

<div style='border-bottom: 1px dashed #666666'></div>

- 成都信息工程大学 · 通信工程 · 本科       2019.9 ~ 至今

### 专业技能

<div style='border-bottom: 1px dashed #666666'></div>

##### 基本技能

- **H5**技术：掌握 **DivCSS** 布局、资源预加载、CSS 动画，原生 JavaScript；
- **移动端**技术：掌握浏览器兼容性处理，**px**、**em**、**rem** 使用场景，掌握预处理器 **Less**、**Sass**，以及通过**媒体查询**、**Flex**编写自适应网站；
- **Vue.js**框架技术：掌握前端渐进式框架 **Vue.js** 全家桶，如 Vuex、Vue-router、Pinia、Nuxtjs(SSR)，以及 VuePress 搭建静态站点；
- **小程序**技术：掌握原生微信小程序、uni-app 开发；
- **前后端分离**技术：掌握 **Axios**、socket.io(websocket) 前后端数据交互技术，有使用 **Nodejs** 开发网站后台经验，如流行的 Express、NestJS、Eggjs 后端框架，结合数据库(MongoDB、MySQL) 开发后端 Api 实现与前端联调；
- **工程化与前端模块化**技术：**Webpack**，Vite，CommonJS/CMD/AMD/ES6，原生 JS 模块化，Vue 组件化；掌握代码托管工具 **Git** 管理项目，掌握包管理器 **npm**、**yarn** 使用，用 Nodejs 开发[脚手架](https://github.com/der-cli/der-cli)工具实现 Git Flow 流程，具备发布 npm 包经验；
- 其他方面，具备 **Element UI**、Vuetify、Vant、AntD 等流行 Ui 库的开发经验，有模仿 ElementPlus 实现自己的 [Vue3 组件库](https://yesmore.cc/Different-UI/) 开发经验；喜欢逛 Github，并使用 hexo 搭建了一个自己的[博客](https://yesmore.cc/)；尝试过 Serverless 技术如 Vercel 开发后台应用；有 Electron 开发桌面端应用经验。

##### 其他技能

- 通过英语六级：能流畅阅读英文文档
- 志愿精神：两年社区志愿者经验

### 个人项目

<div style='border-bottom: 1px dashed #666666'></div>

##### 一、[iTalk 社交聊天 App](https://github.com/yesmore/italk-uniapp)<span style='float:right'>2021/05~2021/06</span>

- **项目概述**：个人开发的**实时聊天 WebApp**；
- **技术栈**：**uni-app**、**Express**、**Socket.IO**、**MongoDB**
- **完成模块**：客户端界面编写；用户登录模块（JWT）、聊天模块（Socket.io）、添加好友模块、搜索用户模块；设计数据库用户模型，好友消息模型等，编写 Api 并制作文档；
- **项目难点**：**首页排序算法**，采用 **Socket.IO** + **冒泡排序** 实现类似 QQ 首页最新消息实时刷新并排序功能；**搜索框防抖**：为了节约服务器性能，防止页面卡顿，使用防抖限制请求频率；
- **项目成果**：在 [Github](https://github.com/yesmore/italk-uniapp) 开源并获得 <img src="https://img.shields.io/github/stars/yesmore/italk-uniapp.svg?logo=github" alt="star"/>；[线上项目](http://italk.aoau.top/) 已注册用户超**200**人。(用户名: hr，密码: 123456)

##### 二、[Der-Cli 脚手架工具](https://der-cli.vercel.app/) <span style='float:right'>2022/02~2022/03</span>

- **项目概述**：一个客户端脚手架工具，解决从项目**初始化**到**发布远程平台**的闭环流程需求。
- **技术栈**：采用原生 **Nodejs** 编写、**Lerna** 工程管理工具开发的单仓库多包项目。
- **完成模块**：**① 命令注册模块**(通过多进程结合 Commander 开源库实现)；**② 初始化项目模块**(自动更新、拉取项目模板，生成本地缓存，通过 Package 开源库实现)；**③GitFlow 模块**(自动初始化本地/远程仓库、自动提交、拉取、合并冲突、生成分支、发布 Tag，通过 SimpleGit 开源库实现)；**④ 后台模块**（存储项目模板信息，通过 Eggjs 实现）；
- **项目难点**：项目整体架构实现；Git Flow 流程架构设计。
- **项目成果**：[Github](https://github.com/der-cli/der-cli) 开源并获得 <img src="https://img.shields.io/github/stars/der-cli/der-cli.svg?logo=github" alt="star"/> ;发布在 [npm](https://www.npmjs.com/package/@der-cli/core) 上，下载量: <img src="https://img.shields.io/npm/dt/@der-cli/core?logo=npm">；[在线预览](https://der-cli.vercel.app/).

