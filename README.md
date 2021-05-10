# 傅凯琪-前端工程师

## 个人信息

- 傅凯琪/男/2019 届/本科/杭师大软件工程系
- Github： [https://github.com/dreamhuan](https://github.com/dreamhuan)
- 手机（微信）： 18268706984
- Email： fu_kaiqi@qq.com

---

## 专业技能

- 熟练掌握 HTML5，CSS3，JavaScript，Typescript
- 熟悉前端开发框架 React，以及周边生态 Redux、Next.js。对 Vue，Angular 有一定了解
- 熟悉前端工程化技术，对 Webpack、Gulp、Rollup 等有一定了解
- 熟悉组件开发，使用 lerna 管理团队组件库
- 熟练使用 Git
- 了解一点后端技术包括 Java，SpringMVC，Redis，MySQL，Node.js，Nest.js
- 了解 cli、Chrome 插件的开发，提高业务开发效率

---

## 工作经历

### 2019.5 至今 杭州涂鸦信息技术有限公司

我在 IoT 组，主要负责[涂鸦 IoT 平台](https://iot.tuya.com)的产品、采购、优惠券三块的内容。19 年划分详细业务线，我属于应用服务业务线，主要负责产品上层服务相关的内容，比如产品多语言、消息推送、产品 OEM 等。20 年转到生产采购线，主要负责生产资料相关业务开发。核心技术栈 Next.js、Typescript、react-redux、fetch。

> 项目

- IoT 工作台全站导航改版。
  - 项目描述：统一 IoT 全站的导航，修改 UI 和结构。
  - 项目职责：
    1. 作为项目的 owner， 调研各业务方使用导航组件的情况，根据新的需求和 UI 将配置进行统一和标准化。
    1. 暴露多个位置的 ReactNode 满足各方业务需求，方便后续扩展。
    1. 使用 IntersectionObserver api 处理目录“加载更多”逻辑。
    1. 使用 lerna 拆分组件管理依赖包。
    1. 组织团队 Code Review 保证代码质量。
    1. 产出详细对接文档协调多个业务方接入，并按依赖以及优先级制定整体发布和回滚策略。
- 产品多语言。
  - 项目描述：开发一个多语言管理平台支持配置 IoT 的产品在不同语种下 App 中的多语言显示。
  - 项目职责：
    1. 从 0 创建新的子项目，串联平台的各个系统。
    1. 前端处理数据映射，从对象解析到列表，应用函数式编程思维，简化了逻辑代码。
    1. 编写通用函数处理 Table 多级行合并逻辑
- 子项目迁移。
  - 项目描述：技术项目，从一个大的 JavaScript + React 主项目中迁移相关业务至 Typescript + Next.js 子项目。
  - 项目职责：
    1. 梳理组件逻辑，重构历史代码。
    1. 补充 Typescript 类型，完成 10+页面的迁移。
- 项目引用依赖分析。
  - 项目描述：技术项目，基于 Next.js 的入口 page 列表，分析整个项目的引用情况，并对特定 AST 结点做一些处理。
  - 项目职责：
    1. 通过引用分析获取到整个项目的引用图。
    1. 用 d3 使用力导向算法绘制引用图。
    1. 根据某个 page 建立引用树结构。
    1. 根据某个组件建立被引用树结构。
    1. 识别项目中的中文结点，并输出，方便后续修改多语言。

## 实习经历

### 2018.7-2019.1 杭州有赞科技有限公司

[有赞微商城后台](https://www.youzan.com/v4/dashboard) 使用 React 技术栈，用户端 h5 使用 Vue 技术栈，小程序是原生的没用任何框架。我主要做会员相关业务，包括 B 端会员模块和 C 端个人中心模块（个人中心包括 h5 页面和小程序）。有赞前端是包含展示层和 node 层，node 用的是基于 Koa 二次开发的[Astroboy](https://github.com/astroboy-lab/astroboy)框架。

> 项目

- PC 端标签管理。有个多级联动的表单，使用了配置型表单，即把公共部分（结构）独立出一个配置对象，可以传递给 jsx 中的函数渲染，部分不完全相同的结构则在配置中放一个 render 函数，根据参数返回不同 jsx。这样就把大的表单按结构分成一块块，也易于维护。
- h5 端个人中心页面。整个页面是多块内容，基于 PC 后台的配置（店铺装修）生成。所以要把每个可配置部分做成单独的组件，并提供给 PC 端使用，h5 端先注册完所有的组件，然后页面中根据后台传过来的组件顺序以及配置渲染对应的组件，主要使用了动态组件的写法，状态管理也整体使用了 Vuex。

---

## 开源项目

- [Cookie 同步插件](https://github.com/dreamhuan/cookie-sync)复制粘贴 Cookie 的 Chrome 插件
- [Next.js 项目依赖分析](https://github.com/dreamhuan/next-analysis)基于 AST 的 Next.js 项目依赖分析工具
- [弹幕射击小游戏](https://github.com/dreamhuan/stg-game)使用 HTML5 canvas 相关 api 开发的弹幕射击小游戏
