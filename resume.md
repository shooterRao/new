# 个人信息

- 饶晋玮/男/1995
- 本科/华南理工大学广州学院
- 工作年限：2 年
- 技术博客：[http://shooterblog.site](http://shooterblog.site)
- github: [https://github.com/shooterRao](https://github.com/shooterRao)
- 个人开发笔录: [http://shooterblog.site/Notebook/](http://shooterblog.site/Notebook/)
- 期望职位：web 前端工程师
- 期望城市：广州

# 联系方式

- Email：rjw0319@163.com

# 工作经历

## 上海数慧系统技术有限公司 (201803 - 至今)

> 担任 web 前端开发

工作职责：

- 参与多个系统的前端开发，包括架构搭建、基础设施**组件库、cli**的建设
- 主导了公司内部地图组件库**vue + arcgis js api4.X**的开发，在很多新项目中都开始投入使用
- 为了统一开发规范和融入基础设施，**自主开发了项目基线脚手架**，给团队提供一套开箱即用的项目初始模板
- 负责在公司内部进行 vue 的推广、培训和转型，以及**arcgis+webpack+vue**技术研究和落地
- **担任导师**，带领组内实习新人了解业务和前端技术前沿探索，并在内部进行了多次技术分享

### 空间规划监测评估预警管理系统(大型项目，代码超10w行)

担任角色：前端开发(子系统负责人)

技术栈：vue、vue-router、vuex、iview、axios、sass、arcgis js api4.8、jest

工作描述：

- 负责该系统的**前端框架搭建、底层核心模块**的开发
- 负责制定**目录结构组织、代码规范以及 gitlab 开发流**
- **解决了首屏渲染慢的问题**，从 **8s** 降到 **2s** 左右
- 根据各子系统的需要，封装了许多通用的"轮子"，如 **迷你动画库**、**轮询工具类**、**storage工具函数**
- 把重复出现的业务组件抽象成**全局组件库**，**解决不同模块容易出现重复造轮子的问题**
- **二次封装 axios**，统一 api 请求规范，**解决 api 地址散落到各个页面模块导致难以集中管理的问题**
- 统一**封装数据转换接口函数**，实现 arcgis 和 echarts 之间的图表联动
- 用**sass @mixin**的方式进行公用样式的抽象，**解决各子系统样式不一致问题**
- 引入 jest 进行单元测试，编写**核心工具模块**的单元测试
- 利用 gitlab-webhooks + jenkins + docker 工具实现前端**自动化打包部署**

### 规划小智在线协同服务平台(互联网SaaS企业级产品)

担任角色：前端开发(主负责技术栈升级)

技术栈：vue、vue-router、vuex、elementUI、sass、echarts、mocha、chai

工作描述：

- 负责**vue技术栈取代旧版本dojo技术栈**的全面升级重构，基于vuecli3
- **用vue重写**基线版的项目管理、资料管理、任务管理等业务模块
- 根据业务需要，在**elementUI的基础上进行二次封装**成全局组件
- 使用**vuex统一维护跨页面组件状态**，并用modules形式进行store划分
- 利用**比对过滤路由表的方式**实现了不同租户渲染不同页面模块和加载相关组件
- 参与了**前端权限控制**的开发，主要用**路由拦截和vue指令控制显隐**方式进行实现

### 智慧规划驾驶舱大屏系统

担任角色：前端核心开发

技术栈：vue、arcgis js4.8、iview、less、echarts

工作描述：

- **底层基于本人预研的方案**[arcgis-webpack-demo](https://github.com/shooterRao/arcgis-webpack-demo)，[arcgis-webpack-vue](https://github.com/shooterRao/arcgis-webpack-vue)进行开发
- 负责首屏页面的开发、实现地图和echarts联动
- 负责实现用 vue 替代 dojo 框架进行页面快速开发
- 负责解决 arcgis 框架在使用 webpack 情况下产生的一系列问题
- 引入 eslint + prettier + precommit 进行代码规范和格式约束

## 广州鸿正软件技术有限公司 （2017 年 4 月 ~ 2018 年 1 月）

> 担任前端和移动开发

工作职责：

- 负责pc端、移动端页面模块的开发
- 负责用react-native进行多个智能管理信息系统的app开发

### 校园管理信息系统移动 app

担任角色：前端兼安卓开发

技术栈：

  - react-native
  - react-navigation
  - mobX

工作描述：

  - 独立负责用`react-navigation`**重构**该项目。由于之前用`react-native`提供的导航器`navigatior`，在安卓端性能表现非常不好（IOS 正常），部分页面跳转需要等待**3 秒**以上（在旧机型上甚至需要**5 秒**），经过优化也需要**2 秒**左右。所以决定用官方最新推荐的页面导航器`react-navigation`进行**重写底层页面跳转**代码。重写完成后，在安卓端跳转页面缩短不到**1 秒**
  - 参与了履职审核，待办提醒，在线选课，在线学习等功能的开发
  - 负责把不同项目中相同的功能模块分离出来，进行组件式开发，编写**可复用，跨平台**的 react-native 业务功能组件，这样不仅**加快了开发效率**，更便于维护
  - 使用mobX 实现跨组件状态管理
  - 使用`es6、es7`重写之前用`es5`写的代码，保持代码风格的一致性，便于维护
  - 负责安卓端的签名、打包 apk、上架，以及热更新

### 管理信息系统审核页面开发

担任角色：前端开发

技术栈：

  - vue
  - vue-router
  - vue-resource
  - webpack
  - es6/es7

工作描述：

- 负责页面组件的编写，如 tab 组件，拖拽组件等等
- 负责解决不同手机 webview 中出现兼容性问题，如 css3 不兼容、内置 api 不一致，部分手机不支持 es6 等等。使用**babel-polyfill**、**postCSS**解决问题
- 负责实现该页面在 webview 中与 app 进行数据交互，调用 app 提供的接口，例如**查看相册**，**录音**，**手写签名**等等

# 开源项目和作品

## 开源项目

- [react-native-fruitStore](https://github.com/shooterRao/react-native-fruitStore)：一个简而美的迷你商城 app，技术栈为 react-native + mobX + react-navigation，支持 android 和 ios 端。您可以通过这篇[技术博客](https://juejin.im/post/5a3f06cd6fb9a044fe4693bc)来了解一些细节 ---248⭐️
- [create-simple-wheels](https://github.com/shooterRao/create-simple-wheels)：用原生 js 来造轮子

## 技术文章

- [GraphQL + Apollo + Vue牛刀小试](http://shooterblog.site/2019/05/25/GraphQL%20+%20Apollo%20%E7%89%9B%E5%88%80%E5%B0%8F%E8%AF%95/)
- [记一次系统前端底层升级总结](http://shooterblog.site/2018/11/11/%E8%AE%B0%E4%B8%80%E6%AC%A1%E7%B3%BB%E7%BB%9F%E5%89%8D%E7%AB%AF%E5%BA%95%E5%B1%82%E5%8D%87%E7%BA%A7%E6%80%BB%E7%BB%93/)
- [Vue 实践小结(长期更新)](http://shooterblog.site/2018/11/04/Vue%E5%AE%9E%E8%B7%B5%E5%B0%8F%E7%BB%93(%E9%95%BF%E6%9C%9F%E6%9B%B4%E6%96%B0)/)
- [Vuecli2引入Arcgis-js-api方案总结(非esri-loader方向)](http://shooterblog.site/2018/09/23/Vuecli2%E5%BC%95%E5%85%A5arcgis-js-api%E6%96%B9%E6%A1%88%E6%80%BB%E7%BB%93(%E9%9D%9Eesri-loader%E6%96%B9%E6%A1%88)/)
- [如何用 Koa2 返回文本和图片流以及解决乱码事件](http://shooterblog.site/2018/04/15/%E5%A6%82%E4%BD%95%E7%94%A8Koa2%E8%BF%94%E5%9B%9E%E6%96%87%E6%9C%AC%E5%92%8C%E5%9B%BE%E7%89%87%E6%B5%81%E4%BB%A5%E5%8F%8A%E8%A7%A3%E5%86%B3%E4%B9%B1%E7%A0%81%E4%BA%8B%E4%BB%B6/)
- [用 React-Native+Mobx 做一个迷你水果商城 APP](http://shooterblog.site/2017/12/27/用React-Native+Mobx做一个迷你水果商城APP/)
- ...

# 我的优势

- 热衷于前端开发，对新技术抱有浓厚的兴趣，时刻关注前端新动向
- 喜欢逛 github 和各种技术社区，对 github 上热门项目会有预研，近期在**研究typescript、graphQl**
- 会科学上网，能阅读英文文档、和技术博客，善于通过阅读文档、使用 Google 和 StackOverflow 解决问题
- 在学习的过程中，喜欢积累和总结，有写博客和记录笔记的习惯，注重分享和输出
- 在工作期间，进行过多次技术分享，如`arcgis+前端工程化`、`前端知识图谱概览及gitlab协作开发和代码走查方案`、`国土空间规划评估预警系统源码解析与实战心得`
- 喜欢各项球类运动，擅长 🏀🏓🏸

# 技能清单

- web开发：html/css/javaScript/typeScript/es6+/vue/react
- 移动开发：react-native/weex/小程序
- 服务端开发：node.js/koa/express/graphQl/mongoDB
- 构建工具：webpack/rollup/gulp
- 测试框架：jest/mocha/chai
- 版本管理：gitlab/svn
- 自动化部署工具：jenkins/docker
- 其它：mac、shell、cet4

# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
