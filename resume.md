# 简历

## 个人信息

姓名: 张良

性别： 男

年龄： 27（1990/08）

籍贯： 河南信阳

婚姻： 已婚

电话： (+86) 180 0126 3960

学历： 本科（河南大学/计算机科学技术）

邮箱： rdshoep@gmail.com; rdshoep@126.com;

Github: [https://github.com/rdshoep](https://github.com/rdshoep)

Npm: [https://www.npmjs.com/~rdshoep](https://www.npmjs.com/~rdshoep)

Blog: [https://blog.rdshoep.com](https://blog.rdshoep.com)

工作年限： 6年三月（前端2-3年）

现居城市： 北京

## 技能清单

### 前端

掌握原生 Javascript，熟悉 ES6

能够编写语义化的 HTML，模块化的 CSS

熟练使用 React、jQuery

熟悉 PostCSS(Autoprefixer)、Sass、Less 等CSS预处理和模块化工具

熟悉 Webpack、Gulp、Babel 等Javascript模块化打包工具

能运用模块化、面向对象的方式编程

### Nodejs

掌握Koa后端开发

使用Redis、Mysql作为session 缓存和数据缓存

使用forever进行线上部署运行

## 项目经验

### 咪听问卷

2017/08 -- 2017/10

系统完全由本人使用Javascript快速实现，针对中南海香烟调研而扩展出来的复杂通用版本。

支持题型： 单行问题、多行文本、单选、多选（其他、互斥选项）、下拉选择、文件上传、评分、验证码等；规则：多问题内容联合影响、表达式的条件判断（支持多题）、选项互斥／同步等

借鉴koa-compose的实现了参加问卷的校验中间件;
设计了可扩展的答题触发器出发一系列的自定义事件;
使用redux-persist 支持未完成答题的数据缓存;
并支持问卷功能的外部支持和自适用，已实现针对问卷的

相关技术栈：Koa@2、Sequence@3、React@15、Antd、Webpack、Babel

### [咪听活动移动端](http://m.miting.net.cn)

2016/08 -- 2017-07

系统使用前后分离的模式开发，使用Koa@1作为中间件负责前端页面的渲染。
前端使用三层模版支持（编译层Nunjucks、服务端渲染和前端渲染artTemplate），Webpack、babel、Gulp、Sass

后期引入Reactjs，替代发活动、活动管理等复杂应用界面，相关页面支持服务器渲染和资源按需加载。

基于本项目拓展出的新模块：

1. [koa-api-client](https://node-wechat.github.io/koa-api-client/)（支持koa1.x、koa2.x中和后端的数据交互、支持Mock、Middlewares、Converter、Logs）
1. voepn（支持多公众账号的共同管理、中间层代理访问支持、微信js的动态引入）
1. koa-oauth-wechat（简单的微信oauth中间件，支持联合vopen的代理访问模式）
1. 针对alioss的扩展支持([alioss-upload](https://rdshoep.github.io/alioss-upload/)、adavanceOssStsServer、[ghost-storage-alioss](https://rdshoep.github.io/ghost-storage-alioss/))

### [郁金香运动Android版本](http://http://sj.qq.com/myapp/detail.htm?apkName=com.tulipsport.run)

2014/08 -- 2016/07

本项目Android版本由我主导开发，负责结构设定、基础控件的封装和大部分界面的实现。
早期使用RoboGuice、GreenDao、AsyncTask、EventBus、HttpClient/Volley，
后期升级为Dagger2、RxJava、Retrofit、OkHttp。

项目中我解决了：运动软件真实使用情况下的软件保活问题、在记录数据时的运动数据中断恢复、Android GPS点的动态取舍、支持Android Wear、并对早期的MPAndroidChart进行代码层修改，支持x轴为数据格式情况下的数据展示等等

### 其他个人项目

1. [nconf-pro](https://rdshoep.github.io/nconf-pro/)
    增强版nconf，自动根据文件名后缀识别对应的加载器；使用json5替换掉默认的json解析器，以至于支持带注释的json配置文件

1. [LoadMoreRecyclerView](https://github.com/rdshoep/LoadMoreRecyclerView)
    Android版本的加载更多的RecyclerView的实现
1. [CropImage](https://github.com/rdshoep/cropimage)
    封装Android版本针对取图片的支持，版本升级导致的不同版本需要使用不同的Api
1. [Social](https://github.com/rdshoep/social)
    简化第三方社会化登陆/分享模块的使用，简化开发者的对各个版本API的学习使用，支持qq、微信、weibo
1. [RulerView](https://github.com/rdshoep/AndroidExpandTools/tree/master/rulerview)
    支持自定义的Android刻度尺控件，郁金香中进行了高级扩展，两级联动截取活动线路

## 工作经历

### 北京捷派科技有限公司（2016/08--至今）

负责公司的前端架构设计、和后端的数据通讯支持等。搭建了内部的私有npm仓库，并生产相关的内部库。
先后产出了产品咪听活动、咪听互助会（停止运营）、咪听众筹（停止运营）、咪听问卷等系统。

### 北京拉邦软件有限公司（2011/07--2016/07）

毕业后的第一份正式工作，伴随着公司一起成长。经历了很多，也学到了很多。

#### 2011/07 -- 2013/08

开始进入项目，进行Polycom视频会议系统开发，到后来成为主要的开发人员，负责重构了视频管理界面、和优化了Agent的通讯机制。

#### 2013/09 -- 2014/05

后来负责在引入相关GIS平台的基础上主导开发了国家海洋局基于GIS平台的海洋数据检测系统、使用Oracle物化视图提前对数据进行预处理分类提升数据的效率。

#### 2014/08 -- 2016/06

后来公司开始做自己的产品“郁金香运动”，我负责Android端，边学习边进行开发。在两个月内出了第一版本，支持运动数据记录、提交和展示。后期在解决国产环境中Android后台保活问题、中断恢复、Android Wear的支持等问题。