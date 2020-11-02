## 前端面试题纲

常识:
规范: 文件命名、JS\CSS
字节数转换
进制

- H5

  > 1、html 语义化标签的理解、结构化的理解,能否写出简洁的 html 结构
  > 2、SEO 优化

        - spa \ ssr

  > 3、多语言 i18n
  > 4、doctype 文档类型(历史产物)
  > 5、块元素、行元素、行内元素 h5[结构性: section\article\nav\header\footer、级块:aside\figure\code\dialog、行内语义:meter\time\progress\video\audio、交互性:details\datagrid
  >
  > > menu\command]
  > > 6、h5 中新增的属性，如自定义属性 data、类名 className、svg\canvas 等；新增表单元素；拖拽 Drag
  > > 7、h5 中新增的 API、修改的 API、废弃的 API 稍作了解（离线存储、audio、video）
  > > 8、meta 标签
  > > 9、manifest 离线缓存机制

  - 离线浏览、访问速度快、稳定-本地
    > 10、新增:web storage 网页存储 [cookie\sessionStorage\localStroage\indexDB]
    > 11、navigator : service woker navigator.serviceWorker 用于多个浏览上下文关联
    > 12、async 加载方式
    > 13、input 和 textarea 的区别
    > 14、 web 标准理解
    > ------- 题 ------
    > 1、用一个 div 模拟 textarea 的实现
    > 2、移动设备忽略将页面中的数字识别为电话号码的方法

- CSS3
  1、CSS 选择器（三大特性）。
  2、BFC 机制\IFC\GFC\FFC
  3、盒模型。
  4、CSS 模块化开发（封装）；SCSS 和 LESS 的使用。
  5、屏幕适配以及页面自适应。 - 响应式布局
  6、CSS3 中新增的选择器。
  7、CSS3 中新增的属性，transform、trasition、animation 等。
  8、flex
  9、grid
  10、css 预处理、后处理
  11、display
  12、相邻的两个 inline-block 节点为什么会出现间隔，该如何解决
  13、meta viewport 移动端适配
  14、CSS 实现宽度自适应 100%，宽高 16:9 的比例的矩形
  15、rem 布局的优缺点
  16、transform 居中 原理
  17、Vertical-align 和 font-size
  18、Vertical-align 的对齐方式
  19、图片格式,区别
  20、position
  21、css 的继承父级
  22、规范
  ------ 题 -----
  1、居中垂直布局
  2、画三角形
  3、1 像素边框问题
  4、布局 - 两栏 - 三栏 [双飞翼、圣杯]
  5、滚动

- JS
  JS 基础:
  1、变量数据类型及检测：基本 + 引用。
  2、运算符：算术 + 条件 + 逻辑 + 位 + 短路、隐式转换等。
  3、条件、循环、异常处理 if、switch(){case xxx:}、try、catch、finally、throw。
  4、函数定义、调用方式（apply、call、直接调用）；传参：实参给形参赋值。
  5、字符串、数组、对象常用 API。
  6、正则表达式。
  7、变量提升
  8、值传递、引用传递
  9、数据类型判断
  10、事件模型
  11、数字静度
  12、错误类型
  13、事件传播机制
  14、事件委托、代理
  event.target
  15、拆箱 / 装箱

  如何让事件先冒泡后捕获
  如何使用事件，以及 IE 和标准 DOM 事件模型之间存在的差别。
  ------ 题 ------
  1、数据类型判断
  JS 高级
  1、作用域、作用域链、闭包。
  2、原型、原型链、继承。构造函数、实例 - 继承的几种方式 - 原型实现继承的缺点、怎么解决
  3、js 重载
  4、new
  3、arguments
  4、definePrototype \ new Object() \ {} 区别
  3、函数上下文、this 指向。
  4、js 的运行机制、事件队列和循环。
  6、数组方法: concat slice splice 使用方法和改变原数组、every some map forEach reduce filtter
  7、对象方法
  5、Ajax 原理、axios 库。
  6、同步、异步编程。
  7、jQuery 源码学习。
  8、内存泄漏
  9、图片懒加载、预加载
  10、垃圾回收
  11、函数式编程 - 函数柯里化 - 纯函数 高阶函数 柯里化函数
  12、为什么会有同源策略
  13、window 的 onload 事件和 domcontentloaded
  14、for...in 迭代和 for...of 有什么区别
  15、立即执行函数和使用场景
  16、设计模式(要求说出如何实现,应用,优缺点)/单例模式实现
  17、iframe 的缺点有哪些
  18、BOM 属性对象方法
  19、DOM - 、DOM 结构 —— 两个节点之间可能存在哪些关系以及如何在节点之间任意移动。 - 2、DOM 操作 ——如何添加、移除、移动、复制、创建和查找节点等。
  19、服务端渲染
  20、eventloop
  进程和线程
  任务队列
  21、模块加载
  22、文档碎片
  23、元编程
  24、错误类型
  25、模版引擎
  26、编译机制：VO/AO/GO
  27、底层运行机制
  28、单线程和同步异步编程
  29、隐式锁 obj.a / Object.defineProperty(obj,a,{})

          ----- 源码 -----
          1、bind\call\apply
          2、new
          3、拷贝
          4、Ajax的原生写法
          5、数组去重、合并
          6、手动实现parseInt
          ----- 题 -----
          1、实现页面加载进度条
          2、怎么判断两个对象是否相等
          3、数组去重
                  数组常用方法
                  查找数组重复项
                  扁平化数组
                  按数组中各项和特定值差值排序
          4、如何快速让字符串变成已千为精度的数字
          5、节流和防抖
          6、Bom中的location history截取字符串
          7、取出当前页面所有DOM
          8、常考正则题
          9、递归、尾递归

      ES6
          2、解构赋值
          3、声明类与继承：class、extend
          4、Promise的使用与实现
          5、generator（异步编程、yield、next()、await 、async）
               - async + await：异步编程的终极方案promise + generator的语法糖。
          6、箭头函数this指向问题、拓展运算符
          7、map和set有没有用过，如何实现一个数组去重，map数据结构有什么优点？
          8、ES6怎么编译成ES5,css-loader原理,过程
          9、ES6转成ES5的常见例子
          1、字符串、数组、对象扩展的api。
          2、变量扩展：let、const解构赋值，块级作用域。
          3、函数扩展：箭头函数默认参数、rest参数。
          4、展开运算符、模板字符串。
          5、set和map数据结构。
          6、迭代器和生成器函数next和yield的理解。
          7、proxy对象属性代理器：属性的读取（get）和设置（set）相关操作。
          8、promise对象、异步编程的解决方案。
          10、class语法、构造函数的语法糖。
          11、模块化编程export + import的导出和导入。
          12、使用es5实现es6的class
          13、Insterator迭代器和for of循环

          ------ 源码 ----
          1、 promise
          ----- 题-----
          1、flat

  DOM
  document object model 文档对象模型
  Document 根节点包含子节点：forms、embeds、anchors、images、links
  --- 题---
  1、获取当前页面上所有节点
  BOM
  browser object model 浏览器对象模型
  Window 对象包含属性：document、location、navigator、screen、history、frames
  1、 history API

- ES6+
  1、es6+ 增加特性
- TS

  1. 装饰器 2.比较优点

  - JS 引擎
    - JIT
    - 延迟编译
    - 实施重编译

- 浏览器
  1、浏览器的构成和运行机制。
  2、浏览器内核。
  3、浏览器交互：BOM 和 DOM 相关 webApi、监听事件。
  4、浏览器缓存机制。
  5、浏览器的渲染原理。
  6、浏览器的安全性：跨域和攻击。
  跨域：
  fiddler & charles 代理
  7、perfermance 监控
  1、输入 url 到展示页面过程发生了什么？ - ip 查询:本地 host \ DNS - 防火墙 - 数据链路 - 服务器:代理、负载均衡、集群 - CDN - 页面渲染: js html css 加载顺序
  2、重绘与回流
  重绘(repaint): 当元素样式的改变不影响布局时，浏览器将使用重绘对元素进行更新，此时由于只需要 UI 层面的重新像素绘制，因此 损耗较少
  回流(reflow): 当元素的尺寸、结构或触发某些属性时，浏览器会重新渲染页面，称为回流。此时，浏览器需要重新经过计算，计算后还需要重新页面布局，因此是较重的操作。会触发回流的操作:
  _ 页面初次渲染
  _ 浏览器窗口大小改变
  _ 元素尺寸、位置、内容发生改变
  _ 元素字体大小变化
  _ 添加或者删除可见的 dom 元素
  _ 激活 CSS 伪类（例如：:hover）
  _ 查询某些属性或调用某些方法
  _ clientWidth、clientHeight、clientTop、clientLeft
  _ offsetWidth、offsetHeight、offsetTop、offsetLeft
  _ scrollWidth、scrollHeight、scrollTop、scrollLeft
  _ getComputedStyle()
  _ getBoundingClientRect() \* scrollTo()
  回流必定触发重绘，重绘不一定触发回流。重绘的开销较小，回流的代价较高。
- 网络协议 / 服务端与网络
  1、HTTP 协议。 http/https/http2.0
  2、UDP \ TCP
  3、加密
  2、cookie、session、token。
  1、常见状态码 > 301 302 客户端
  2、缓存
  200 From cache 和 200 ok
  400,401,403 状态码分别代表什么
  浏览器缓存: [last-modify\]
  3、cookie, session, token
  4、前端持久化的方式、区别
  5、DNS 是怎么解析的
  6、cdn
  7、计算机网络的相关协议
  9、get post 区别
  10、ajax、 axios 库
  11、tcp 三次握手，四次挥手流程
  12、跨域
  13、前端安全 XSS、CSRF
  14、websocket
  15、Http 请求中的 keep-alive 有了解吗
  16、网络分层
  17、即时通信，除了 Ajax 和 websocket
  18、模块化，commonJS，es6，cmd，amd
- 移动端
  1、自适应
  2、pwa
  3、移动端手势
  4、rem flexible 的适配原理
  5、区别:webApp hybirdApp nativeApp
  6、phonegap
  7、工具: 同时多个测试页面
  8、视口
  9、1x 2x 3x 中页面相同, 字体 图片 容器都分别用什么单位
  10、滚动穿透
  11、viewport 和 dpi 适配
  12、Touch/Gesture 事件及封装处理
  13、DIALOG 模态框组件的封装
  14、视口区别: viewport
- 微信小程序
  微信小程序和 h5 差异，如果有开发 weex 的经验，可能会加上 weex
- 打包工具
  webpack
  1、打包原理
  2、打包插件
  3、webpack 热更新原理
  4、优化构建速度
  5、loader > css-loader > babel-loader
  包管理工具 npm 1. 读取顺序 2. 插件
  gulp 流清洗
  rullup
  snowpack
- 框架
  概念:MVC/MVVM 状态管理
  Vue
  1、vue 解决了什么问题
  2、MVVM 的理解
  3、如何实现一个自定义组件，不同组件之间如何通信的？
  4、nextTick
  5、生命周期
  6、虚拟 dom 的原理
  7、双向绑定的原理？数据劫持？
  9、Proxy 相比于 defineProperty 的优势
  10、watch computed 区别
  11、virtual dom 原理实现
  12、vue-router(hash， HTML5 新增的 pushState
  单页应用，如何实现其路由功能---路由原理
  vue-router 如何做用户登录权限等
  你在项目中怎么实现路由的嵌套
  13、vuex 的理解
  14、transtion
  15、mixins
  VUE 基础
  1、基本指令。
  2、实例的属性和方法。
  3、实例的生命周期。
  4、组件基础：创建、注册、添加属性方法、套用等。
  5、组件通信传值，父子、兄弟、跨级。
  6、插槽 slot 等。
  7、v-show、v-if
  VUE 高级
  1、vue-router：搭建 SPA
  ▪ 路由、组件的配置。
  ▪ 路由间的传值。
  ▪ 路由跳转。
  ▪ 路由的导航守卫。
  ▪ 记住在 router.js 和组件页面中的使用方式。
  ▪ 编程式路由
  ▪ 动态路由
  2、vuex：状态管理、数据仓库 store
  ▪ 实例化仓库的 5 大属性的使用。
  ▪ state、getters、mutations、actions、modules。
  ▪ 辅助函数 mapState 等，仓库中计算属性的映射、方便操作。
  ▪ 记住在 store.js 和组件中使用方式。
  VUE 深入、源码阅读
  1、数据响应式原理。
  2、virtual dom。
  3、diff 算法。
  4、nextTick 等等。
  全家桶:
  vue-router:

            vuex
        vue3.0
            1、区别
            2. compotion API

  React
  react 基础:  
   JSX 语法（虚拟 DOM）
  状态
  属性
  ref
  组件
  生命周期
  PureComponent
  Hooks

  服务器渲染
  nuxt.js

- Node 1. koa
  2.express 3.中间件 4.事件机制
  多端开发
  ----- 题 -----
  1、Native 监听页面渲染性能
  2、了解 netflix 如果实现 android 与 ios 共用一套代码

  GIT
  git 基本命令

- 前沿技术
  1、微前端: single-spa\qiankun
  1、ReactNative
  2、快应用
  3、uni-app
  4、flutter
  5、weex
  6、pwa
  7、serverless
  8、dva
  9、umi-app
  10、原生 web component
  11、Electron 跨平台桌面程序的开源库
  12、webAssembly
  13、low code
  14、PWA
  15、GraphQL
  16、cheerio + mysql + nodemailer 个性化新闻爬虫
  17、Deno
  18、LiteElement、svelte、stencil
  19、webComponent
  20、chrome 插件
  21、增强障碍用户的体验
  22、i18n 兼容多语言
  23、f2etest 多浏览器兼容性测试整体解决方案
  24、GraphLearn 神经网络框架

- QA 调试
  前端: 1. debugger 2.事件绑定 3.audits 4.performance 5.timing 6.sourceMap
- 算法
  数据结构： 数组、堆、双向链表、栈、反转单向链表、队列
  递归： 图形绘制、穷举、组合问题、空间优化、重复子问题优化、尾递归、搜索问题（8 皇后）、深度和广度优先搜索
  1、排序算法
  2、动态规划，参见背包问题
  3、二叉树
  4、加油站问题(贪心算法)
  5、二分法
  6、二叉树遍历
  7、单链表反转
  8、取 1000 个数字里面的质数
  9、找出数组中和为给定值的两个元素，如：[1, 2, 3, 4, 5]中找出和为 6 的两个元素。
  10、线性顺序存储结构和链式存储结构有什么区别？以及优缺点
  11、堆、栈
  12、排序 背包
  13、线性规划
  14、位运算
  15、复杂度
  16、cpu、寄存器、内存
  17、填表法、LCS 问题的子结构
  18、构造结果
  ---------题-----------
  1、反转二叉树
  2、解析 Query 字符串
  3、火车排序问题和队列
  4、网格走法动态规划
  5、取 N 个数字为 M
  6、两个栈实现一个队列

- 图形学
  echarts / g6 / threejs
- 安全
  1. crsf / xss / SQL 注入 \
     2、爬虫
     3、文件上传
     4、越权
- 运维
  1.Docker
  2.jenkinks
  3.gitlab CI/CD
  Linux
  1、桥接、NAT、Host-only 等网络连接
  2、快照、克隆、挂载点和分区
  3、vi 编辑器、用户与权限管理、服务管理、软件管理、网络管理、系统命令

  Nginx
  1、模块和基本配置
  2、正向反向代理等
  3、CDN
  4、浏览器缓存
  5、跨域
  6、防盗链
  7、rewrite
  8、负载均衡集群

- 数据库
- 工程能力考察
  项目能力
  1、vue-cli 脚手架搭建和功能配置 vue.config.js。
  2、webpack 的常用配置。
  3、项目构建打包。
  4、熟悉各类框架的文档。
  5、UI 框架：Bootstrap、MUI、Element-ui 等。
  6、常用的插件整理；整理一个自己插件库，封装自己的方法库、组件库。
  7、常用的工具熟练度。
  8、PC 端和移动端开发注意事项。
  9、经验总结：快速确定项目的技术选型。
  10、坑点总结：项目遇到坑坑坑！
  11、项目中的性能优化记录（都是细节点，多记录）。
  12、需求文档的理解，可以结合项目流程图、UML 图。
  13、问题解决能力：bug 定位调试、查找文档、寻求他人。
  14、记录习惯养成。
  模块化、组件化开发能力
  1、项目分类；各类文件整理、分类。
  2、各类功能封装。
  3、组件和功能模块的抽离、解耦、复用。
- 内功考察 1.面向对象的编程思想
  1、类的抽象。
  2、对象的封装、继承。
  3、为了更好的去管理数据、分类数据，实现高内聚、低耦合。 2.设计模式
  设计模式感觉也是将面向对象思想再度抽象成现实中某些特定模式。 3.数据结构和算法
  1、学习常用的排序搜索算法、顺序表、链表、栈、队列、树、堆等。
  2、考验你的抽象思维和数学功底。
  3、将现实需求抽象成计算机代码的思维能力。 4. 编译原理
  5、计算机网络基础
  OSI 七层模型
  TCP/IP 参考模型
  物理层
  数据链路层 - 以太网 - 总线型拓扑 - 冲突检测 - MAC 地址 - 以太网帧 - ARP 协议
  互联网层 - IP 协议 - 选址 - 子网掩码和子网划分
  传输层 - TCP 数据包 - TCP 序列号 - 滑动窗口和拥塞检测 - 三次握手和四次挥手 - UDP 协议
  应用层 - DNS 协议 - HTTP 协议 - HTTPS 协议
  6、操作系统
  7、计算机组成原理
  7、软件测试原理
  8、设计模式
  9、编译原理

  > UML 模型图
  > -- 类图和对象图 【依赖关系、泛化关系、实现关系、关联关系、聚合关系、组合关系】
  > -- 活动图、时序图、协作图、组件图、部署图

  > 设计原则 【开放封闭原则、单一职责原则、里氏转换原则、依赖倒置原则、接口隔离原则、迪米特法则、合成复用原则】
  > 创建型模式 【抽象工程模式(abstract factory)、建造者模式（builder）、工厂方法模式（factory method）、原型模式（prototype）、单利模式（singleton）】
  > 结构型模式 【适配器模式（adapter）、桥接模式（bridge）、组合模式（composite）、装饰模式（decorator）、外观模式（facade）、享元模式（flyweight）、代理模式（proxy）】
  > 行为型模式 【职责链模式（chain of responsibility）、命令模式（command）、解析器模式（interpreter）、迭代器模式（iterator）、中介者模式（mediator）、备忘录模式（memento）、观察者模式（observer）、状态模式（state）、策略模式（strategy）、模版方法模式（template method）、访问者模式（visitor）】

- 后端语言
  1、python、node.js、php 等。
  2、数据库 mysql、redis、mongodb；sql 的操作语句、mongodb 的操作语句、redis 的操作语句。
  3、node + express 搭建本地服务等。
  4、python + django + request + scrapy。
  5、shell.js

- 系统编程
  1、Linux 命令行操作、系统文件管理。
  2、多任务、多线程、多进程、协程、并发、并行、串行、同步、异步等概念的理解。
- 架构模式
  1、BFF - back-end For front-end
  2、业务中台
  3、Paas Iaas [aws gcp] saas - 云计算服务 - Infrastructure as a service = 安装管理应用程序，甚至是有权管理网络组件 - 用户可以在云服务提供商提供的基础设施上部署和运行任何软件，包括操作系统和应用软件– 基础设施即服务 IaaS 服务有虚拟机、虚拟网络、以及存储 - Platform as a service – 平台即服务 - 服务有数据库服务、web 应用以及容器服务。 - Software as a Service – 软件即服务 - 服务有：各类的网盘(Dropbox、百度网盘等)，JIRA，GitLab
- 附加题
  1、无限滚动方案
  2、如何处理兼容性问题
  3、你遇到过最难的问题是什么
  4、ES6 class 与 ES5 function 区别及联系
  5、vue 怎么监听数组
  6、写过 webpack loader 吗
  7、微信网页版登录机制思考
  8、前端性能优化
  页面 DOM 节点太多，会出现什么问题？如何优化？
  如何做性能监测
  9、鉴权
  cookie
  session
  JToken
  10、服务器推送
  1.websocket
  2.ajax 短轮询、长轮询
  3.sse Server-sent-events
  4.websocket [node:socket.io] 11. 瀑布流
  12、图片占位、骨架屏
  13、离线缓存
  14、上传文件
  15、通信方式

项目:
1、规范
2、工程化 - webpack - git commit / git hooks - jenkins / travis CI - Docker / k8s - ci /cd

3、性能优化:骨架屏、ssr、webpack
4、测试: mocha
5、性能监控 > 前端监控目标 > 监控 Js promise 资源加载错误 > 接口异常采集 > 白屏和加载时间 > 性能指标和卡顿 > pv 和 用户停留时间
6、埋点
6、日志:收集用户信息、报错 pm2
7、加密策略
8、用户鉴权
9、存储方案
10、Docker、k8s
11、多端
12、git flow
13、cli 命令行工具
14、npm 包
15、可配置页面

公司架构
启动 node app.js
koa
理解 npm run dev - spa 单页应用
npm run build / 部署到 testing ; 模块 spa , 页面 spa
静态资源处理 组织、打包 md5
passport
页面转化漏斗模型
SEO SEM
实地推广

源码扩展:
jquery
vue
react
lodash [get \ 数组去重]
vue-router
react-router
vuex\redux\flux\mobx

拓展题:
1、语义解析: 解析 template => ast  
2、ssr \ csr \ mpa \ spa 概念理解
3、V8 内存管理： > 1. js 垃圾收集、内存管理 > 2. V8 回收机制分类 > 3. 引用计数、标记清除、增量标记
4、长列表展示 瀑布流
减少 dom
控制位置

必要练习:
1、CI : git hooks -> jenkins [dist] -> 免密 ssh 部署 [scp \ shell [启动 node]]
