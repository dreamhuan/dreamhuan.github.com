# 傅凯琪-前端工程师

## 联系方式

- 手机 / 微信：18268706984
- Email：fu_kaiqi@qq.com

---

## 个人信息

- 傅凯琪/男/1996
- 本科/杭师大软件工程系
- Github：[https://github.com/dreamhuan](https://github.com/dreamhuan)

---

## 工作经历

### 2019.5 至今 杭州涂鸦信息技术有限公司

我在 iot 组，主要负责[涂鸦 IoT 平台](https://iot.tuya.com)的产品、采购、优惠券三块的内容。19 年划分详细业务线，我属于应用服务业务线，主要负责产品上层服务相关的内容，比如产品多语言、消息推送、产品 OEM 等。20 年转到生产采购线，主要负责生产资料相关业务开发。核心技术栈 Next.js、Typescript、react-redux、fetch。

> 项目

- 导航改版。作为项目的 owner， 调研各业务方使用导航组件的情况，根据新的需求和 UI 将配置进行统一和标准化，暴露多个位置的 ReactNode 方便后续扩展。组织团队 Code Review 保证代码质量。产出详细对接文档协调多个业务方接入，并按依赖以及优先级制定整体发布和回滚策略。并持续跟进后续使用情况，以及一些细节难题的处理。

- 产品多语言。从 0 创建新的子项目，串联平台的各个系统，对整个前端系统架构有了更清晰的认知。需求本身数据层有历史包袱，需要前端做一层数据处理，从对象解析到列表，应用函数式编程思维，大大简化了逻辑代码。

- 子项目迁移。技术项目，从一个大的 js+react 主项目中迁移相关业务至 ts+next 子项目。梳理组件逻辑，重构历史代码，尽量补充 ts 类型，完成 10+页面的迁移。全过程用户无感知，未出现线上故障。

## 实习经历

### 2018.7-2019.1 杭州有赞科技有限公司

[有赞微商城后台](https://www.youzan.com/v4/dashboard) 使用 React 技术栈，用户端 h5 使用 Vue 技术栈，小程序是原生的没用任何框架。我主要做会员相关业务，包括 B 端会员模块和 C 端个人中心模块（个人中心包括 h5 页面和小程序）。有赞前端是包含展示层和 node 层，node 用的是基于 Koa 二次开发的[Astroboy](https://github.com/astroboy-lab/astroboy)框架。

> 项目

- PC 端标签管理。有个多级联动的表单，使用了配置型表单，即把公共部分（结构）独立出一个配置对象，可以传递给 jsx 中的函数渲染，部分不完全相同的结构则在配置中放一个 render 函数，根据参数返回不同 jsx。这样就把大的表单按结构分成一块块，也易于维护。

- h5 端个人中心页面。整个页面是多块内容，基于 PC 后台的配置（店铺装修）生成。所以要把每个可配置部分做成单独的组件，并提供给 PC 端使用，h5 端先注册完所有的组件，然后页面中根据后台传过来的组件顺序以及配置渲染对应的组件，主要使用了动态组件的写法，状态管理也整体使用了 Vuex。

### 2016.9-2018.6 杭州烁梦科技有限公司（校企合作实验室）

校内实验室，核心开发项目[拇指课堂](http://www.thumbclass.com/website/index.html)

> 项目

拇指课堂使用 AngularJS 和 Ionic 框架的混合式 app 开发，用于课堂管理，为增强课堂互动性而存在。我参与过答题模块和通知模块的开发。其中印象比较深刻的是答题模块中，题目从题库选择并打乱顺序。有个随机性强并且高效的 Fisher-Yates 算法。后面在 2018 年带领团队基于 Angular4 / Ionic3 进行前端升级（重构），框架升级后，大大增强了前端代码的可维护性。

---

## 技能清单

- 语言：Typescript/Java
- 前端框架：React/Vue/Next.js
- 后端框架：NestJS/SpringMVC
- 前端工程化：Webpack/Gulp
- 数据库：MySQL
- 版本管理工具：Git
- 其他：i18n/SSR/组件库/cli/浏览器插件

---

## 开源项目

- [Cookie 同步插件](https://github.com/dreamhuan/cookie-sync)复制粘贴 Cookie 的 Chrome 插件
- [弹幕射击小游戏](https://github.com/dreamhuan/stg-game)使用 HTML5 canvas 相关 api 开发的弹幕射击小游戏
- [MobileMassages](https://github.com/dreamhuan/MobileMassages)大二短学期完成的基于 mean.js 框架的网页（假期又基于 Angular4 进行前端重构）
- [webcli](https://github.com/dreamhuan/webcli)一个基于 gulp 和 webpack 工具的前端开发流打包的 npm cli 工具
