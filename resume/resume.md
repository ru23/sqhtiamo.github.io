# [张宇航的个人简历](https://github.com/sqhtiamo/sqhtiamo.github.io/blob/master/resume.md)

## 联系方式

- 手机：15121036028
- Email：[sqhtiamo@163.com](sqhtiamo@163.com)

## 个人信息

 - 张宇航/男/1989
 - 本科/上海交通大学－电子与计算机工程/2008-2012
 - 硕士研究生/上海交通大学－无线网络与通信/2012-2015
 - 工作年限：2.5年
 - Github：[https://github.com/sqhtiamo](https://github.com/sqhtiamo)

---

## 工作经历

### 上海方付通商务服务有限公司(2016年6月~至今) － 高级前端开发工程师

#### BOSS项目
该项目为直采商城的运营人员提供后台商品、运营活动等配置功能，包括秒杀、预售、商品SKU、订单系统、抽奖系统等。

个人主要负责整个项目前端基础框架构建(自己研发了一套融入了自己组件化、配置化思想的后台快速开发框架 - [bigMom](https://github.com/sqhtiamo/bigMom))、规范制定、业务开发等。

#### 微信商城项目
该项目为公司直采商城的C侧部分，是一套面向微信用户的垂直电商网站，如：在微信中打开：https://mp.52shangchao.com/xinghua/m/boutique/home/index。

个人主要基于既有框架，负责相关业务的开发，包括订单系统、VIP用户系统、抽奖系统等。主要应用的技术是backbone和团队自研的MLBF框架，用node作为接入层作前后端分离，因此前端需要接手部分中台开发，如nginx接入、灰度用户筛选、微信权限认证等部分。


#### 组内人才培养计划与团队管理
主要负责前端团队下一个5人小组的团队管理工作。具体负责一下工作：

- [制定boss侧交互、视觉、前端组件规范](https://github.com/sqhtiamo/boss-doc)
- 制定组内code review规范和相关checklist
- 搭建组内文档平台
- 推进团队前端工程化进程以及工具集的推广
- 制定组内人才培养计划

### 腾讯科技有限公司－SNG企业平台部(2014年7月~2016年6月) － 前端开发工程师

#### 平台运营中心BOSS项目（2014.7-2015.5）
该项目主要负责经销商账户体系管理和企业产品的售卖。包含以下平台:

- [STORE在线直销平台](http://store.b.qq.com)：基于框架机(通过node服务进行的前后端分离方案)和LBF.js(组内自研基于组件化前端框架)进行开发。
- BOSS售中平台：基于EXTJS的SPA，内部运营系统。
- [企点官网平台](http://qidian.qq.com)：和外包团队制定合作规范、合作开发的静态官网平台。
- [BQQ官网平台](http://b.qq.com)：基于staticServer(Node的静态化工具)开发的官网平台。
- EPD数据展示平台：后端YII框架、前端用highcharts做数据展示,由于项目特殊前后端开发均有前端一人完成

由于项目较为成熟、负责，用到的技术大多为组内积累，个人负责日常迭代开发、 运维(线上服务器的配置、前端部署、织云安装包等工具的制作)、组件的扩展开发。

#### QQ公众号项目（2015.6-2015.10）
该项目为2015年即通综合部的重点项目，于2015.5-2015.9在深圳进行封闭式开发。

个人主要负责：

- [商家portal](https://mp.qq.com)(用户使用的公众号运营平台)的注册、认证、安全模块。
- 平台portal(后台腾讯运营人员的审核平台)主要基于框架机+LBF的模式开发

个人的贡献：

- 提出并实施前端监控方案(JS 报错、cgi 打点监控、页面渲染速度监控)
- 平台portal页面基于grunt的脚手架工具(旨于后端人员可以对前端进行页面开发)
- 引进LESS(EST.less)，页面模板组件化，JS基类封装等方案，使后端人员可以通过配置化的方式开发前端

#### 企点精准营销项目（2015.10-2016.6）
包含精准营销平台、代运营平台和企点营销平台。

- 其中代运营平台运用了前后端公用模板的分离方案(mustache)+ReactJS(ES6)进行组件式开发
- 精准营销平台与企点营销平台用框架机+LBF+MVC的开发模式进行开发

---

## 开源项目和作品

### 开源项目

 - [webpack-sftp-client](http://github.com/sqhtiamo/webpack-sftp-client)：通过sftp上传的webpack插件，以NPM包的形式进行发布，包括滴滴打车项目（DDFE）、方付通内部项目等其他公司均有使用，每周100＋下载量。([npm下载地址](https://www.npmjs.com/package/webpack-sftp-client))
 - [kaido](http://github.com/sqhtiamo/kaido)：供不会编码的人仅仅通过设置、拖拽等简单的页面功能生成H5动画页面。主要使用vue2.0(vuex + vue-router) + koa2.0 + mongoose等相关技术栈，进行全栈开发。
 - [bigMom](http://github.com/sqhtiamo/bigMom)：基于angular框架和extJS的配置化思想，自己研发了一套新的配置化、组件化、适用于快速开发后台管理系统的一套框架。主要使用angular(1.0) + webpack 等相关技术栈，进行组件化开发。
 - [jira-shell](https://github.com/sqhtiamo/sqhtiamo.github.io/tree/master/notes/jira-shell)：用nodejs写的，以便使用者在终端快速使用jira进行任务流操作。在保证项目质量的前提下，提高开发效率。

### 个人项目
 - [shangyang](https://github.com/lutaoact/shangyang)：一个基于微信公众号，以人传人的‘传销模式‘进行图片分享、用户报名参加的项目。主要是使用express+node-cavas，利用微信API进行后端开发。
 - [scott](https://coding.net/u/cagegong/p/scott/git/tree/master)：一个基于微信公众号的口语练习APP。主要调用微信sdk的录音接口和H5的音视频操作接口，使用react+redux+express+mongoose等进行开发。([http://learnwithwind.com/](http://learnwithwind.com/))
 - [phantom-demo](https://github.com/Strawhat-in-FE/phantom-demo)：用phantomJS抓取页面，监控页面的变化（比如：微信审批进度）并及时用邮件通知相关人员。

### 个人分享(公司级分享)

 - [FE 101 - 从web历史发展看前端框架](https://github.com/sqhtiamo/sqhtiamo.github.io/tree/master/notes/101)
 - [2016年velocity参会有感](https://github.com/sqhtiamo/sqhtiamo.github.io/blob/master/notes/velocity/velocity%20summary.pdf)
 - [商城BOSS侧前端框架技术分享](https://github.com/sqhtiamo/sqhtiamo.github.io/tree/master/notes/boss-xmall)
 - [Hybrid APP 本地缓存方案预研](https://github.com/sqhtiamo/sqhtiamo.github.io/blob/master/notes/hybrid-app-cache/hybrid%20app%20cache.pdf)

## 技能清单

- Web后端语言：PHP/Node
- Web后端框架：Yii/CI/Koa/Express
- 前端框架：Backbone/AngularJS(1.0&2.0)/VueJS/ReactJS(React Native)
- 前端工具：Grunt/Gulp/Webpack/Npm Scripts
- 版本管理、文档和自动化部署工具：Svn/Git
- 云和开放平台：七牛开放平台/微信应用开发

## 自我评价
个人喜欢探索，对于前端新技术保持着时刻关注，对于前端知识的广度知识吸收较快。但同时意识到对于前端深度上的不足，目前正在苦心研究w3c标准。除此对非前端专业学科也较为关注，如无线通信领域、智能家居领域、机器学习、视频直播等。
