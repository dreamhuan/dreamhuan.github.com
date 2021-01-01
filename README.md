# 傅凯琪-前端工程师

## 联系方式

- 手机 / 微信：18268706984
- Email：fu_kaiqi@qq.com

---

## 个人信息

- 傅凯琪/男/1996
- 本科/杭师大软件工程系
- 博客：[https://dreamhuan.github.io](https://dreamhuan.github.io)
- Github：[https://github.com/dreamhuan](https://github.com/dreamhuan)
- 期望城市：杭州

---

## 工作经历

### 2019.5-now 杭州涂鸦信息技术有限公司（实习了两月）

涂鸦是一家 AIoT 企业，帮助传统企业赋能物联网。[涂鸦官网](https://www.tuya.com),[涂鸦 IoT 平台](https://iot.tuya.com)
我在 iot 组（后更名为 iss，iot self service）刚进涂鸦那会儿 iot 组人比较少，我做的就比较广，主要负责产品、采购、优惠券三块的内容。19 年 Q3 划分详细业务线，我属于应用服务业务线，主要负责产品上层服务相关的内容，比如产品多语言、消息推送、OEM 等。

> 技术栈：

- React
- Next.js

## 实习经历

### 2018.7-2019.1 杭州有赞科技有限公司（大三-大四）

有赞是一家帮助商家开店的公司，为商家提供 h5 和小程序开店支持。[有赞官网](https://www.youzan.com),[微商城后台](https://www.youzan.com/v4/dashboard)

有赞商家 pc 后台使用 react 技术栈，用户端 h5 使用 vue 技术栈，小程序是原生的没用任何框架...我主要做会员相关业务，包括 B 端会员模块和 C 端个人中心模块。有赞前端是包含展示层和 node 层，node 用的是基于 Koa 二期开发的[Astroboy](https://github.com/astroboy-lab/astroboy)框架。在有赞实习的这半年是自我技术提升最快的半年，有赞的技术栈完美避开了我之前开发用的技术栈（我：Angular+Express，有赞：React/Vue+Koa）。因为之前没做过 react 和小程序相关的，实习过程中基本属于边学边做，对于自己技术和业务上的提高帮助非常大。

> 项目

- PC 端一个大的项目是标签管理，有个多级联动的表单，直接把 if 的逻辑和组件放一起写就会比较麻烦，代码也会很长。后面我用了配置型表单，即把公共部分（结构）独立出一个配置对象，可以传递给 jsx 中的函数渲染，部分不完全相同的结构则在配置中放一个 render 函数，根据参数返回不同 jsx。这样就把大的表单按结构分成一块块，也易于维护。

- h5 端就是个人中心页面，整个页面比较平淡，重点在于它的显示是基于 PC 后台的配置（店铺装修）。所以要把每个可配置部分做成单独的组件，并提供给 PC 端使用，h5 端先注册完所有的组件，然后页面中根据后台传过来的组件顺序以及配置渲染对应的组件，主要使用了动态组件的写法，感觉比较新奇。状态管理也整体使用了 Vuex。

> 技术栈：

- React
- Vue
- Astroboy（内部框架，基于 Koa）

### 2016.9-2018.6 杭州烁梦科技有限公司（大二-大三，校企合作实验室）

校内实验室，核心开发项目[拇指课堂](http://www.thumbclass.com/website/index.html)

拇指课堂使用 AngularJS 和 Ionic 框架的混合式 app 开发，用于课堂管理，为增强课堂互动性而存在。我参与过答题模块和通知模块的开发。其中印象比较深刻的是答题模块中，题目从题库选择并打乱顺序。有个随机性强并且高效的 Fisher-Yates 算法，感觉比较惊艳。后面在 2018 年带领团队基于 Angular4 / Ionic3 进行前端升级（重构），框架升级后，大大增强了前端代码的可维护性。AngularJS 已经不再更新，并且之前我们业务代码都写在一起比较混乱，更新到 Angular 后，因为整体的模块设计和 typescript 加成，所以整体代码结构和功能都比较清晰，ts 的类型检查也比较给力。

> 技术栈：

- AngularJS（1.x）
- Angular（2+，两个框架... 0.0）
- Ionic
- Express

---

## 技能清单

- 前端开发：HTML5/CSS3/JavaScript/TypeScript
- 前端框架：React/Vue/Angular/AngularJS/Ionic
- 后端框架：Express/Koa/SpringMVC
- 前端工具：Webpack/Gulp
- 数据库：MySQL/Oracle/MongoDB
- 版本管理工具：Git

---

## 开源项目

- [弹幕射击小游戏](https://github.com/dreamhuan/stg-game)使用 HTML5canvas 相关 api 开发的弹幕射击小游戏
- [MobileMassages](https://github.com/dreamhuan/MobileMassages)大二短学期完成的基于 mean.js 框架的网页（假期又基于 Angular4 进行前端重构）
- [webcli](https://github.com/dreamhuan/webcli)一个基于 gulp 和 webpack 工具的前端开发流打包的 npm cli 工具

---

## 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
