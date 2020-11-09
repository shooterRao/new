# 个人信息

- 饶晋玮/男/1995
- 本科
- 工作年限：3 年
- github: [https://github.com/shooterRao](https://github.com/shooterRao)
- 技术博客：[https://shooterblog.site](https://shooterblog.site)
- 个人开发笔录: [https://shooterblog.site/Notebook](https://shooterblog.site/Notebook)
- 期望职位：web 前端工程师
- 期望城市：广州

# 联系方式

- Email：rjw0319@163.com

# 工作经历

## 上海数慧系统技术有限公司 (2018/03 - 2020/08)

> 担任 web 前端开发 & 技术经理

工作职责：

- 参与多个ToB系统的前端开发，承担项目前端负责人的角色
- 负责前端基础设施的建设，包括基础框架、脚手架、组件库等
- 负责制定和统一前端项目的编码规范、开发流程，提高开发效率
- 负责前端前沿技术的研究和落地，并在内部进行推广和培训
- 担任导师，带领组内新人了解业务和前端前沿技术的探索，并在内部进行了多次技术分享

### 阳江国土基础信息平台

担任角色：前端开发 & 技术经理

技术栈：vue、vue-router、vuex、iview、single-spa、systemjs、typeScript、rollup、docker

工作描述：

- 负责项目技术路线的统筹，协助项目经理与客户进行需求研讨
- 负责开发工作量的评估，开发资源的调配以及对开发进度的把握
- 负责在项目中推动公司产品中前端新技术的落地，如微前端架构
- 解决实施微前端过程中的各种问题，如样式冲突、路由动态加载、权限控制
- 开发vue-eventbus插件，改善了系统中eventBus的使用方式，提高开发效率
- 解决大数据量目录树组件渲染卡顿的问题，自研树组件替代iview的tree组件
- 使用docker部署，提供前端自动化打包部署脚本，提高项目部署效率

### 国土空间规划一张图实施监督信息系统(大型项目产品，代码量超10w行)

担任角色：前端开发 & 子系统负责人

技术栈：vue、vue-router、vuex、iview、scss、single-spa、systemjs、typeScript、rollup、arcgis js api4.8、jest、docker

工作描述：

- 负责主体系统的前端框架搭建、底层核心模块(http请求、权限控制)的开发
- 负责制定目录分层结构、代码整体规范以及 gitlab 开发流
- 负责微前端的研究和改造，主导了该系统微前端方案的落地
- 解决了系统首屏渲染慢的问题，从 8s 降至 2s 左右
- 开发svg-loader的vuecli插件，快速接入各个子系统，使用svg图标代替传统iconfont图标
- 根据各子系统的需要，封装了许多通用的轮子，如动画库、轮询类、缓存请求结果工具
- 统一 api + mock 请求规范，解决 api 地址散落到各个页面模块导致难以集中管理的问题
- 引入 jest 进行单元测试，并负责编写核心工具模块的单元测试
- 利用 gitlab-webhooks + jenkins + docker 工具实现前端自动化打包部署

### 浙江省生态修复监管系统

担任角色：前端开发 & 子模块负责人

技术栈：vue、vue-router、vuex、iview、scss、g6

工作描述：

- 负责整体框架方面的搭建，layout层抽离，路由表按子系统模块划分
- 全局组件的开发以及统一管理，并提供组件demo页面和代码示例，方便快速接入
- 实现通过`this.$xxx()`命令方式调用vue组件，避免编写太多模板以及定义过多options
- 根据业务需要，修改iview-tree组件源码支持与tab窗口进行联动，并优化节点过多产生的性能问题
- 根据Flowable-BPMN返回的流程图数据，使用vue+g6实现流程图的渲染
- 修改润乾报表源码，解决单元格检验异常问题，以及实现了单元格tooltip提示
- 负责与后端对接，实现大文件的切片上传以及断点续传

## 广州鸿正软件技术有限公司 （2017 年 4 月 ~ 2018 年 1 月）

> 担任前端和移动开发

工作职责：

- 负责pc端、移动端页面模块的开发
- 负责用react-native进行多个智能管理信息系统的app开发

### 校园管理信息系统移动 app

担任角色：前端兼安卓开发

技术栈：react-native、react-navigation、mobx

工作描述：

  - 独立负责用`react-navigation`**重构**该项目。由于之前用`react-native`提供的导航器`navigatior`，在安卓端性能表现非常不好（IOS 正常），部分页面跳转需要等待**3 秒**以上（在旧机型上甚至需要**5 秒**），经过优化也需要**2 秒**左右。所以决定用官方最新推荐的页面导航器`react-navigation`进行**重写底层页面跳转**代码。重写完成后，在安卓端跳转页面缩短不到**1 秒**
  - 参与了履职审核，待办提醒，在线选课，在线学习等功能的开发
  - 负责把不同项目中相同的功能模块分离出来，进行组件式开发，编写**可复用，跨平台**的 react-native 业务功能组件，这样不仅**加快了开发效率**，更便于维护
  - 使用`mobx`实现跨组件状态管理
  - 使用`es6、es7`重写之前用`es5`写的代码，保持代码风格的一致性，便于维护
  - 负责安卓端的签名、打包 apk、上架，以及热更新

# 开源项目和作品

## 开源项目

- [create-simple-wheels](https://github.com/shooterRao/create-simple-wheels)：用typeScript来造轮子
- [vue-plugin-event-bus](https://github.com/shooterRao/vue-plugin-event-bus)：vue eventBus 管理插件，快捷使用eventBus，自动解绑事件
- [vue-cli-plugin-svg-sprite-loader](https://github.com/shooterRao/vue-cli-plugin-svg-sprite-loader)：vue svg-sprite-loader 插件，快速使用svg图标
- [arcgis-webpack-demo](https://github.com/shooterRao/arcgis-webpack-demo)：arcgis 融合 webpack 实现前端工程化示例
- [react-native-fruitStore](https://github.com/shooterRao/react-native-fruitStore)：一个迷你商城 app，技术栈为 react-native + mobx + react-navigation

## 技术文章

- [解读vue数据响应式实现原理](https://shooterblog.site/blogs/%E8%A7%A3%E8%AF%BBvue%E6%95%B0%E6%8D%AE%E5%93%8D%E5%BA%94%E5%BC%8F%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86.html#%E5%89%8D%E8%A8%80)
- [用node+vuepress+docker打造团队文档知识库](https://shooterblog.site/blogs/%E7%94%A8node+vuepress+docker%E6%89%93%E9%80%A0%E5%9B%A2%E9%98%9F%E6%96%87%E6%A1%A3%E7%9F%A5%E8%AF%86%E5%BA%93.html#%E5%89%8D%E8%A8%80)
- [企业级前端脚手架开发总结](https://shooterblog.site/blogs/%E4%BC%81%E4%B8%9A%E7%BA%A7%E5%89%8D%E7%AB%AF%E8%84%9A%E6%89%8B%E6%9E%B6%E5%BC%80%E5%8F%91%E6%80%BB%E7%BB%93.html#%E4%B8%BA%E4%BB%80%E4%B9%88%E6%88%91%E4%BB%AC%E9%9C%80%E8%A6%81%E5%89%8D%E7%AB%AF%E8%84%9A%E6%89%8B%E6%9E%B6)
- [记一次系统前端底层升级总结](https://shooterblog.site/blogs/%E8%AE%B0%E4%B8%80%E6%AC%A1%E7%B3%BB%E7%BB%9F%E5%89%8D%E7%AB%AF%E5%BA%95%E5%B1%82%E5%8D%87%E7%BA%A7%E6%80%BB%E7%BB%93.html#%E5%89%8D%E8%A8%80)
- [vue实践小结(长期更新)](https://shooterblog.site/blogs/vue%E5%AE%9E%E8%B7%B5%E5%B0%8F%E7%BB%93(%E9%95%BF%E6%9C%9F%E6%9B%B4%E6%96%B0).html#%E5%89%8D%E8%A8%80)
- [vuecli2引入arcgis-js-api方案总结](https://shooterblog.site/blogs/vuecli2%E5%BC%95%E5%85%A5arcgis-js-api%E6%96%B9%E6%A1%88%E6%80%BB%E7%BB%93.html#%E5%89%8D%E8%A8%80)
- ...

# 我的优势

- 有多个ToB系统的项目经验，也有移动端开发的经验，擅长vue方面的开发
- 热衷于前端开发，对新技术抱有浓厚的兴趣，时刻关注前端新动向，有自己的开源项目
- 会自我驱动预研新技术，并在实际项目中尝试落地，然后在公司进行内部推广
- 喜欢逛 github 和各种技术社区，对 github 上热门项目会有预研，近期在研究学习vue3
- 会科学上网，能阅读英文文档、技术博客，善于通过阅读文档、使用 Google 和 StackOverflow 解决问题
- 在学习的过程中，喜欢积累和总结，有写博客和记录笔记的习惯，注重分享和输出
- 在工作期间，进行过多次技术分享，如`arcgis+前端工程化`、`vue响应式原理及源码解读`、`国土空间规划一张图实施监督信息系统源码解析与实战心得`、`如何开发企业级前端脚手架`
- 喜欢各项球类运动，擅长 🏀🏓🏸

# 技能清单

- web开发：html/css/javaScript/typeScript/es6+/vue/react
- 移动开发：react-native/微信小程序
- 服务端开发：node.js/graphQl
- 构建工具：webpack/rollup/gulp
- 测试框架：jest/mocha/chai
- 版本管理：git
- 自动化部署工具：jenkins/docker
- 其它：mac、shell、cet4

# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
