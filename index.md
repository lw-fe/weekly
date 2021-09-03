# 技术快报

> 业界技术跟进，不限于前端技术，按时间逆序梳理，每周一份，[轮值主编制度参考](./editors.md)

## 210830-210903

`本周轮值主编`：赵君毅 `下周轮值主编`：刘红梅

> 干货
* [ 210903 ] 新一代Web技术栈的演进：SSR/SSG/ISR/DPR都在做什么？ <https://mp.weixin.qq.com/s/i9FaQ1NNgj6LjQuCdOAoUg > [ from 文玲 ]
     * CSR：Client Side Rendering，客户端（通常是浏览器）渲染；
     * SSR：Server Side Rendering，服务端渲染；
     * SSG：Static Site Generation，静态网站生成；
     * ISR：Incremental Site Rendering，增量式的网站渲染；
     * DPR：Distributed Persistent Rendering，分布式的持续渲染。
* [ 210902 ] 推荐收藏10个有用的Web资源 <https://juejin.cn/post/7003114103094902792>  [ from 海萍 ]
* [ 210902 ] JavaScript模块化方案 <https://juejin.cn/post/7003285499628486670#heading-5>  [ from 风鑫 ]
* [ 210827 ] 整理的一些 Vue3 知识点 <https://mp.weixin.qq.com/s/P-UxHqnl9SvU7qlIPPbNTg>  [ from 红梅 ]

> 工具
* [ 210830 ] Cross Context Events <https://github.com/mia1024/cross-context-events>  [ from 君毅 ]
    *  Cross context events is a robust, lightweight package providing the option to send and receive events across JS execution context（包含iframe，window tab，node环境）

## 210823-210828

`本周轮值主编`：赵文玲 `下周轮值主编`：赵君毅

> 干货
* [ 210825 ] 浅聊WebRTC视频通话 <https://juejin.cn/post/7000205126719766565 > [ from 文玲 ]
* [ 210816 ] Rust and Webassembly <https://rustwasm.github.io/docs/book/introduction.html>  [ from 君毅 ]
    *  This small book describes how to use Rust and WebAssembly together
* [ 210726 ] 一文读懂cookie、session、token、jwt、单点登录 <https://mp.weixin.qq.com/s/D7tWeUPsUfYsA97au5soNg > [ from 文玲 ]
    * HTTP 是无状态的，为了维持前后请求，需要前端存储标记
    * cookie 是一种完善的标记方式，通过 HTTP 头或 js 操作，有对应的安全策略，是大多数状态管理方案的基石
    * session 是一种状态管理方案，前端通过 cookie 存储 id，后端存储数据，但后端要处理分布式问题
    * token 是另一种状态管理方案，相比于 session 不需要后端存储，数据全部存在前端，解放后端，释放灵活性
    * token 的编码技术，通常基于 base64，或增加加密算法防篡改，jwt 是一种成熟的编码方案
    * 在复杂系统中，token 可通过 service token、refresh token 的分权，同时满足安全性和用户体验
    * session 和 token 的对比就是「用不用cookie」和「后端存不存」的对比
    * 单点登录要求不同域下的系统「一次登录，全线通用」，通常由独立的 SSO 系统记录登录状态、下发 ticket，各业务系统配合存储和认证 ticket

> 工具
*  [ 210827 ] RAWGraphs <https://rawgraphs.io/> [ from 红梅 ]
    * 一个 Web 工具，只要把电子表格的数据复制粘贴到网页上，就可以转成数据可视化图形，不需要编写代码。


## 210816-210820

`本周轮值主编`：师风鑫 `下周轮值主编`：赵文玲

> 干货

* [ 210816 ] html-to-image <https://github.com/bubkoo/html-to-image>  [ from 君毅 ]
    *  Generates an image from a DOM node using HTML5 canvas and SVG.Fork from dom-to-image with more maintainable code and some new features

* [ 210816 ] DataEase <https://github.com/dataease/dataease>  [ from 君毅 ]
    *  一个开源的数据可视化报表大屏搭建工具，支持丰富的数据源连接，能够通过拖拉拽方式，快速制作图表和仪表盘

* [ 210819 ] Vue 3.2 发布了，那尤雨溪是怎么发布 Vue.js 的？ <https://juejin.cn/post/6997943192851054606>  [ from 红梅 ]

* [ 210813 ] 关闭页面时怎么向后台发送消息 <https://juejin.cn/post/6997016317635084319 >[ from 风鑫]

* [ 210818 ] 居然不知道CSS能做3D？天空盒子了解一下，颠覆想象👽 <https://juejin.cn/post/6997697496176820255>  [ from 海萍 ]

## 210809-210813

`本周轮值主编`：孟丰 `下周轮值主编`：师风鑫

> 干货

* [ 210811 ] 15张图，20分钟吃透Diff算法核心原理 <https://juejin.cn/post/6994959998283907102> [ from 文玲 ]

* [ 210812 ] 38个ES6-ES12的开发技巧 <https://juejin.cn/post/6995334897065787422> [ from 文玲 ]
* [ 210809 ] PixiJS <https://pixijs.huashengweilai.com/>  [ from 君毅 ]
    *  2D可视化渲染引擎
* [ 210812 ] 如何在大型代码仓库中删掉废弃的文件和 exports <https://mp.weixin.qq.com/s/VMB9FRMopo0acqkd2ijl_g> [ from 红梅 ]
    * pzavolinsky/ts-unused-exports
    * eslint
    * ts-prune
* [ 210813 ] z-index: 0和z-index: auto的区别 <https://juejin.cn/post/6995006409423192078>[ form 风鑫]

> 新鲜物

* [ 210720 ] 全新短视频智能创作平台重磅上线！1分钟让你搞定视频创作 <https://club.1688.com/unithread/165172755.html>  [ from 君毅 ]
    *  短视频一站式服务平台
* [ 210810 ] 无需安装的Windows11网页版来了，一键带你体验win11！<https://blog.csdn.net/weixin_43314519/article/details/119569103> [GitHub源码](https://github.com/blueedgetechno/windows11)[ from 海萍 ]

## 210802-210807

`本周轮值主编`：吴海萍 `下周轮值主编`：孟丰

> 干货

* [ 210805 ] 多图详解，一次性搞懂Webpack Loader <https://juejin.cn/post/6992754161221632030> [ from 文玲 ]

* [ 210726 ] 自如客APP裸眼3D效果的实现<https://juejin.cn/post/6989227733410644005>  [ from 海萍 ]
  * 非常有创意的banner实现
  * banner图分层，通过传感器获取设备倾斜角，对背景和前景进行移动操作，造成视觉上的景深效果

* [ 210627 ] JS判断图像背景颜色单一还是丰富 <https://www.zhangxinxu.com/wordpress/2021/06/js-image-colorful-or-pure/> [ from 海萍 ]
   * 常见颜色距离计算方法
   * 提取图片主色，计算主色值平均距离

* [ 210127 ] ES6 运算符的扩展 <https://wangdoc.com/es6/operator.html>  [ from 君毅 ]
    *  新增 **，?.，??，||=，&&=，??=





## 210725-210730

`本周轮值主编`：刘红梅 `下周轮值主编`：吴海萍

* [ 210729 ] 我给鸿星尔克写了一个 720° 看鞋展厅
 <https://mp.weixin.qq.com/s/pOfRCqp2SPCB9n3xutxCZw > RealityCapture建模，three.js渲染.  [ from 文玲 ]
* [ 210723 ] 47 张图带你走进浏览器的世界！<https://mp.weixin.qq.com/s/wwaVdXcZjDYgTAwIT7Z84A > 用47张图带你了解「浏览器的发展史」、「浏览器的架构」、「浏览器的   基本原理」以及 「浏览器的其它小知识」。[ from 文玲 ]
* [ 210727 ] 最全数学各个分支简介 <https://mp.weixin.qq.com/s/-YWabenejcw3yNNz5Si5RA > [ from 文玲 ]
*  [ 210729 ] 来看看CSS Functions <https://juejin.cn/post/6990289477201559565?from=main_page> [ from 红梅 ]
*  [ 210730 ] Vue刷新页面有哪几种方式 <https://juejin.cn/post/6990546455282843656?from=main_page> [ from 红梅 ]
* [ 210127 ] 一行CSS实现全站中文简繁转换 <https://www.zhangxinxu.com/wordpress/2021/01/css-simplified-traditional-chinese>  [ from 君毅 ]
    *  font-variant-east-asian: traditional（正常只有mac操作系统有效，或使用苹方字体）

## 210719-210723

`本周轮值主编`：赵君毅 `下周轮值主编`：刘红梅

> 干货
* [ 210720 ] nginx常用配置清单 <https://mp.weixin.qq.com/s/HQB2WEwwjs6NvJtJIt76Bw > [ from 文玲 ]
    * 可视化配置nginx站点 <https://nginxconfig.io/ >
* [ 210720 ] JSON.stringify() <https://mp.weixin.qq.com/s/rdUd3g-8XFQUkIZzM0QO6g > [ from 文玲 ]
    * 支持过滤与格式化缩进

> 话题
* [ 210529 ] 尤雨溪：做技术哪有什么两全之策，都是取舍和平衡 <https://mp.weixin.qq.com/s/_q_SnCbGyXrNnXA876tXbA>  [ from 君毅 ]
    *  聊了聊 Vue、Vite，以及前端工程师的成长等话题

> 经验
*  [ 210720 ] 参考 Codepen，我做了一个基于 iframe 的代码预览系统  <https://segmentfault.com/a/1190000040373631>  [ from 红梅 ]
    * 代码插件 monaco-editor


## 210712-210716

`本周轮值主编`：赵君毅 `下周轮值主编`：赵文玲

> 经验

* [ 210709 ]  关于文件下载相关的问题 <https://mp.weixin.qq.com/s/EmjC646G-KdCkKLbOS24fg>  [ from 红梅 ]
    * ajax如何下载文件
    * 预览图片为啥变成了下载
    * js获取一些response header有些获取不到
* [ 210712 ] 古怪的 JavaScript <https://jsisweird.com>  [ from 君毅 ]
    *  通过25道题，了解js类型转换的古怪
* [ 210715 ] 前端站点一键支持暗色模式 <https://mp.weixin.qq.com/s/FNAdXW7YLGy6o6wOnmiQKw>  [ from 红梅 ]
    * 颜色值相似度的计算 chorma-js

> 工具

* [ 210712 ] Animista <https://animista.net>  [ from 君毅 ]
    *  在线CSS动画生成工具

> 新鲜物

* [ 210712 ] Fluid Paint <https://david.li/paint>  [ from 君毅 ]
    *  基于webgl实现的网页画板工具，可以定制笔刷，产生刷油漆的流体效果

## 210705-210709

`本周轮值主编`：孟丰 `下周轮值主编`：赵文玲

> 干货

* [ 210708 ] 前端工程化实战 - 企业级 CLI 开发  <https://juejin.cn/post/6982215543017193502>  [ from 文玲 ]

* [ 210706 ] 关于性能优化的9大策略和6大指标 <https://juejin.cn/post/6981673766178783262>  [ from 文玲 ]

> 经验

* [ 181230 ] 一篇文章了解广告全链路 <https://segmentfault.com/a/1190000017571939?_ea=5919383>  [ from 君毅 ]
    *  通过描述广告的玩法，让读者对广告有一个整体的概念和印象，同事对广告后台算法逻辑进行了初步介绍
* [ 190107 ] 广告的发展趋势和其中的前端角色 <https://segmentfault.com/a/1190000017785756>  [ from 君毅 ]
    *  从广告的发展趋势和尚存问题讲起，引出前端开发在未来应该逐渐的所处的角色和应该承担的责任

> OS

* [ 210629 ] 鸿蒙开场动画前端实现 <https://juejin.cn/post/6979042510400126983>  [ from 君毅 ]
  * 由于CSS的滤镜属性filter本来就是从SVG那边吸收过来的，所以在CSS中可以使用SVG滤镜

## 210628-210702

`本周轮值主编`：吴海萍 `下周轮值主编`：孟丰

> 干货
* [ 210701 ] 绝了，没想到一个 source map 居然涉及到那么多知识盲区 <https://mp.weixin.qq.com/s/3M48V3yNiuuryle9bW472w> [ from 文玲 ]
* [ 180915 ] Node 定时器详解 <https://mp.weixin.qq.com/s/YLpGdzlKkUDhfi_EhgxG7Q>  [ from 文玲 ]
    * setTimeout()
    * setInterval()
    * setImmediate()
    * process.nextTick()
* [ 210622 ] 从 0 到 1 实现浏览器端沙盒运行环境 <https://mp.weixin.qq.com/s/7CD_F0hEZtYRK0fvBWb_gQ>  [ from 君毅 ]
    *  介绍了如何实现所有页面代码编译在前端完成，具备实时热更新功能的沙盒运行环境
* [ 210629 ] AST抽象语法树 <https://segmentfault.com/a/1190000040260996> [ from 红梅 ]
* [ 181016 ] AST抽象语法树 <https://segmentfault.com/a/1190000016706589?utm_source=sf-similar-article> [ from 红梅 ]


## 210621-210625

`本周轮值主编`：赵君毅 `下周轮值主编`：吴海萍

> 干货
* [ 210614 ] Event Loop 和 JS 引擎、渲染引擎的关系 <https://mp.weixin.qq.com/s/1PCQMgrXt4bPYtW-uVZgHQ> [ from 文玲 ]
* [ 210624 ] mitt, Tiny 200b functional event emitter / pubsub. <https://www.npmjs.com/package/mitt>  [ from 文玲 ]
    * 与Node's EventEmitter使用方式相同
* [ 210625 ] 好消息，CSS text-underline-offset可以用起来了 <https://www.zhangxinxu.com/wordpress/2021/02/css-text-underline-offset> [ from 海萍 ]
* [ 210625 ] 15 张前端高清知识地图，强烈建议收藏 <https://juejin.cn/post/6976157870014332935> [ from 宋浩 ]
* [ 210624 ]  浏览器大容量存储方案-IndexedDB简介 <https://juejin.cn/post/6977370170457063437>  [ from 红梅 ]

> 工具
* [ 210621 ] Introducing WebContainers: Run Node.js natively in your browser <https://blog.stackblitz.com/posts/introducing-webcontainers>  [ from 君毅 ]
    * 借助Webassembly以及浏览器最新的api，支持在浏览器运行node.js服务，使得在本地高校开发编辑nodejs项目成为可能
* [ 210621 ] git-split-diffs <https://github.com/banga/git-split-diffs>  [ from 君毅 ]
    * GitHub style split diffs with syntax highlighting in your terminal（node 版本需要大于12）
* [ 210621 ] Hurl.it <https://www.ruanyifeng.com/blog/2021/06/weekly-issue-161.html>  [ from 君毅 ]
    *  网页版 Postman

## 210614-210618

`本周轮值主编`：刘红梅 `下周轮值主编`：赵君毅

> 干货
* [ 210615 ] React 性能优化 ：包括原理、技巧、Demo、工具使用 <https://mp.weixin.qq.com/s/jaWzs2GpPjN6Et6rapMUzA > [ from 文玲 ]
* [ 210611 ] 明明有了 promise ，为啥还需要 async await ？<https://mp.weixin.qq.com/s/9ga2gpEb6-UdlLGadGqlDw > [ from 文玲 ]
* [ 210615 ] 令人眼前一亮的 Vue 实战技巧 <https://segmentfault.com/a/1190000040180294> [ from 红梅 ]
* [ 210618 ] Grafar <https://thoughtspile.github.io/grafar/#/>  [ from 君毅 ]
    * Grafar is a javascript library for reactive, 3D mathematical visualization (data visualization capabilities coming sometime)
* [ 210615 ]  CSS ::marker 让文字序号更有意思 <https://segmentfault.com/a/1190000040175019> [ from 红梅 ]


## 210607-210611

`本周轮值主编`：赵文玲 `下周轮值主编`：刘红梅

> 论坛
* [ 210602 ] 玉伯、尤雨溪、于冰……他们眼中的大前端趋势 <https://mp.weixin.qq.com/s/ingKHy2TmzDXag2JOfTPlw > [ from 文玲 ]

> 工具
* [ 210531 ] 前端工程师的一大神器：puppeteer <https://mp.weixin.qq.com/s/P5jQZjoMRFFSvjmYgISymw > [ from 文玲 ]

> 干货
* [ 210423 ] 用three.js写一个下雨动画 <https://mp.weixin.qq.com/s/qcHLNoP08G8TwGn-tVgJwA > [ from 文玲 ]
* [ 190324 ] CSS :focus-visible伪类让我感动哭了 <https://www.zhangxinxu.com/wordpress/2019/03/css-focus-visible/comment-page-1>  [ from 君毅 ]
    * 浏览器认为键盘访问触发的元素聚焦才是:focus-visible所表示的聚焦。换句话说，:focus-visible可以让我们知道元素的聚焦行为到底是鼠标触发还是键盘触发
* [ 210428 ] Why We Switched From Webpack To Vite <https://blog.replit.com/vite>  [ from 君毅 ]
    * 借助Go语言实现的esbuild提前构建第三方依赖，使得构建速度比webpack提升10到100倍
    * HMT更新只针对发生改变的文件进行，更新效率很高
* [ 210610 ] 一行代码webpack 加速优化 <https://mp.weixin.qq.com/s/eSf6P3D0L-og2VMmgScvqA> [ from 红梅 ]

> OS
* [ 210610 ] 初窥鸿蒙 <https://segmentfault.com/a/1190000040158589> [ from 红梅 ]


