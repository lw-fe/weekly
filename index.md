# 技术快报

> 业界技术跟进，不限于前端技术，按时间逆序梳理，每周一份，[轮值主编制度参考](./editors.md)

## 200831-200905

`本周轮值主编`: 红梅 `下周轮值主编`：良辰

> 干货

* [ 200904 ] 你还在为项目里的重复请求发愁吗? <https://juejin.im/post/6868530321776705544> 两个工具（repeat-request-minder和repeat-request-minder-webpack-plugin）来辅助我们避免重复的请求。 [from 文玲]
    * 通过改写XMLHttpRequest中的方法来实现监控每个请求是否重复
    * 引入LRU Cache算法来控制缓存的大小
* [200904] 你不知道的前端异常处理 <https://zhuanlan.zhihu.com/p/150262359> [from 凌云]
* [200904] npm 依赖管理中被忽略的那些细节 <https://mp.weixin.qq.com/s/JHDVh9wGj_YaTLtSz4AH7g> from [思源]
* [ 200903 ] BetterScroll 2.0 发布 <https://juejin.im/post/6868086607027650573> [from 文玲]
    * 支持按需加载功能
    * 插件化的架构设计
    * TypeScript实现
* [ 200831 ] 广告短信的退订内幕 <https://daily.zhihu.com/story/9726870> [ from 君毅 ]
    * 运气好他会去通讯录里，手动把回复短信的人的号码搜出来，删掉，之后不再给人家发信息，反之...屁用没有
* [ 200831 ] ts-migrate <http://www.ruanyifeng.com/blog/2020/08/weekly-issue-121.html> [ from 君毅 ]
    * Airbnb 公司新的开源项目，可以将 JavaScript 代码转成 TypeScript 代码
 
> 工具

* [200903]  Chrome 开发工具插件推荐 <https://www.infoq.cn/article/3zoQAl2ZX4pkdEBgsbVf> [from 红梅]

> 新鲜货

* [200903]  教你使用CSS3实现新拟态UI <https://juejin.im/post/6868099832175820808> [from 红梅]
* 新拟态的概念
* 如何实现



## 200824-200829

`本周轮值主编`: 思源 `下周轮值主编`：红梅

> 基础

* [ 200531 ] 图解javascript——基础篇 <https://mp.weixin.qq.com/s/jOjUPR-t-wX0TI9rD3P45Q> [ from 文玲 ]
* [ 200603 ] 图解JavaScript——进阶篇 <https://mp.weixin.qq.com/s/sAKkyR9XNtQIYWL6F0PDIA> [ from 文玲 ]
* [ 200609 ] 图解23种设计模式（TypeScript版）<https://mp.weixin.qq.com/s/GzPqSgna9Fwqal-5Oyg5EA> [ from 文玲 ]

> 干货
* [ 200828 ]  用「增量」思想提升代码检查和打包构建的效率 <https://juejin.im/post/6865101730166767623> [ from 晓朋 ]  
      *  增量方式实现代码规范检测，对于遗留老代码可以做到逐步检查和提高效率
* [ 200828 ] CSS变量对JS交互组件开发带来的提升与变革 <https://www.zhangxinxu.com/wordpress/2020/07/css-var-improve-components> [ from 凌云 ]
* [ 200828 ]  初探视频原理和FFmpeg <https://juejin.im/post/6864520204731285511> [ from 良辰 ]
* [ 200828 ]  React中key的一点总结<https://juejin.im/post/6844903700209598477> [ from 子哲 ]  
      *  运用index作为key的反面举例
> 实践
* [ 200819 ] 从0到1，搭建一个体系完善的前端React组件库 <https://my.oschina.net/u/3247020/blog/4512048> [ from 君毅 ]
    * Npm关联gitlab，通过指定指定分支下特定目录的package.json，实现版本升级后自动发布
    * 在确保代码一定是通过node模块方式加载的时候，只需要打出commonjs2的模块来显著地提升了打包速度，减小打包体积
    * 拆分独立功能包后，可以让我们扩展和组合出更多灵活多样的组件库，让组件库不再单一而臃肿
* [ 200819 ] 开启gzip压缩 <http://gitlab.lvwan-inc.com/sophon-wiki/sophon-docs/blob/master/zhaisiyuan/article/gzip.md> [ from 思源 ]
* [ 200829 ] 提高渲染速度，怎么让资源预加载？ <http://gitlab.lvwan-inc.com/sophon-wiki/sophon-docs/blob/master/zhaisiyuan/article/link-preload.md> [ from 思源 ]


## 200810-200815

`本周轮值主编`: 君毅 `下周轮值主编`：红梅

> 干货
* [ 200821 ] 玩转 CSS 变量 <https://juejin.im/post/6863031374115733518> [ from 红梅]
* [ 200818 ] 精读《Tasks, microtasks, queues and schedules》 https://mp.weixin.qq.com/s/osRVRjMzgEnmlBgQrurd3w [ from 思源 ]
* [ 200821 ] 拒绝JavaScript，这三个CSS技巧你一定用的上 <https://zhuanlan.zhihu.com/p/113159493> [ from 凌云 ]
* [ 200821 ] 通过例子来理解 React 的事件系统 https://juejin.im/post/6863083643427979271 [from 思源]
* [ 200821 ] React 的事件机制 https://zhuanlan.zhihu.com/p/49067231 [from 思源]

> 数据可视化
* [ 170630 ] 遇见大数据可视化：基础研究 <https://cloud.tencent.com/developer/article/1004816> [ from 文玲 ]
* [ 170630 ] 遇见大数据可视化：未来已来，变革中的数据可视化 <https://cloud.tencent.com/developer/article/1005149> [ from 文玲 ]
* [ 170705 ] 遇见大数据可视化：可视化系统搭建 <https://cloud.tencent.com/developer/article/1005260> [ from 文玲 ]

> 开源
* [ 200818 ] Luckysheet， github: <https://github.com/mengshukeji/Luckysheet>  <iframe src="http://258i.com/gbtn.html?user=mengshukeji&repo=Luckysheet&type=star&count=true" frameborder="0" scrolling="0" width="105px" height="20px"></iframe> [ from 君毅 ]
    * 一个网页开源表格库，实现效果类似 Excel，提供了较丰富的功能

> 新鲜货
* [ 200818 ] JS 1024 竞赛 <https://js1024.fun/results/2020#46> [ from 君毅 ]
    * 代码长度不超过1024字节的 JS 程序的比赛，可在线查看 demo，及相关源码

> 资讯
* [ 200821 ] ECMAScript 双月报告：TC39 7月会议提案进度汇总 <https://mp.weixin.qq.com/s/pCVN0WfzQGFY6cry0O8c5Q> [ from 晓鹏 ]

## 200810-200815

`本周轮值主编`: 晓朋 `下周轮值主编`：君毅

> 干货

* [200807] Nginx 配置 HTTPS 服务器 <https://aotu.io/notes/2016/08/16/nginx-https/index.html> from [鹏程]
    *获得 SSL 证书
    *通过 listen 命令 SSL 参数以及引用 example.key 和 example.crt 文件完成 HTTPS 基础配置
    *HTTPS优化
    *HTTP/HTTPS混合服务器配置
    *基于服务器名称（name-based）的 HTTPS 服务器
* [ 200809 ] 前端页面可视化搭建工具业界的轮子 <https://juejin.im/post/6858881797490098190> [from 文玲 ]
    * 业界调研20+项目
* [ 200814 ] 基于相似度分析的组件聚类 <https://mp.weixin.qq.com/s/g9rCzsdsSUmRLapuD3eCzw> [from 大民 ]
* [ 200814 ] Babel 插件开发手册 <https://juejin.im/post/6844904055945314312> from [思源]
* [200814] 6个常见的可访问性问题及解决方案 <https://mp.weixin.qq.com/s/5_elC6uqm6JhBSSECJhkww> [from 良辰 ]
* [ 180904 ] [CSS] svg路径动画 <https://romefrontend.dev/> [ from 君毅 ]
    * 纯 css 借助 offset-path，offset-distance 实现
* [ 160928 ] svg实现自定义路径动画 <https://romefrontend.dev/> [ from 君毅 ]
    * 借助 path 的 getTotalLength 与 getPointAtLength js api 实现
* [200814] 如何衡量前端工程质量 <https://mp.weixin.qq.com/s/_jV3KXXZ_3P7A8FnpaqRHQ> [ from 晓朋 ]

> 总结
* [ 200813 ] 前端行业现状总结 <http://fe.lvwan-inc.com/liuhongmei/others/front-status.md.html> [from 红梅 ]

## 200803-200808

`本周轮值主编`: 文玲 `下周轮值主编`：晓朋

> 干货
* [ 200805 ] 了解 JS 压缩图片，这一篇就够了 <https://mp.weixin.qq.com/s/OTkpetqr0XoY1psjC9z5zQ> [ from 文玲 ]
    * 弄清 Image 对象、data URL、Canvas 和 File（Blob）之间的转化关系；
    * 图片压缩关键技巧；
    * 超大图片压缩黑屏问题。
    * js-image-compressor
* [ 200806 ] 图解作用域，作用域链，闭包 <https://juejin.im/post/6857876880701030408> [ from 文玲 ]
    * [[scope]], 包含了被创建的作用域中的对象的集合，这个集合被称为函数的作用域链
    * 活动对象在作用域链的最前端
* [ 200423 ] 图片懒加载踩坑 <https://juejin.im/post/6844903597172342791> [ from 子哲 ]
* [ 200805 ] 查缺补漏」巩固你的HTTP知识体系 <https://juejin.im/post/6857287743966281736> [ from 子哲 ]
* [ 200801 ] Web Worker 文献综述 <https://mp.weixin.qq.com/s/MyRRIbn-UoruVD1dpvD-QQ> [ from 鹏程 ]
* [ 200715 ] 在浏览器中存储数据 - IndexedDB <https://mp.weixin.qq.com/s/EO10qD9hn4cuH5o74_EPSQ> [ from 鹏程 ]
* [ 200807 ] 你不知道的ES4 <https://mp.weixin.qq.com/s/-Q2bObgW4ZwmrPo7aUQBmA> [ from 思源]
* [ 200210 ] 写出一手烂代码的19条准则 <https://www.toutiao.com/i6791612475751006732/>  [ from 大民 ]


> vue
* [ 200806 ] 图解 Vue 响应式原理 <https://juejin.im/post/6857669921166491662> [ from 文玲 ]
    * 从 Vue 初始化，到首次渲染生成 DOM 的流程。
    * 从 Vue 数据修改，到页面更新 DOM 的流程。
* [ 200806 ] Vue3为何使用Proxy实现数据监听 <https://juejin.im/post/6857877411913990158> [ from 文玲 ]
    * Object.defineProperty，在Vue实例化时遍历所有对象属性，对新增无能为力，容易引起性能问题，需要大内存
    * Proxy，只要你访问对象，就会走到 Proxy 的逻辑中，已有的 key 还是新增的 key，都会监听到
    * Proxy 对 IE 不友好，vue3 在检测到使用 IE 的情况下（包括 IE11），会自动降级为 Object.defineProperty 的数据监听系统

> webpack
* [ 200807 ] 分享 9 条 Webpack 优化策略 <https://mp.weixin.qq.com/s/xFOPrntp0JHrSPdTKuNDIw> [ from 红梅 ]
* [ 191117 ] Webpack 4 Tree Shaking 终极优化指南 <https://www.cnblogs.com/lzkwin/p/11878509.html> [ from 思源]

> 感悟
* [ 200805 ] 我做前端这 10 多年来的感悟 -  蚂蚁金服体验技术部的高级前端专家 <https://www.toutiao.com/i6857349519479144972/> [ from 大民 ]

> 开源
* [ 200807 ] Sugar-Electron, 基于Electron桌面开发平台的自研应用框架 <<https://juejin.im/post/6857402778122190856> [ from 文玲 ]

> 总结
* [ 200807 ] 图谱可视化渲染引擎性能比对 <http://fe.lvwan-inc.com/zhaojunyi/SophonWeb/webgl/product-compare/product-compare.md.html> [ from 君毅 ]
    * 众多主流框架提供了图谱可视化引擎，本篇文章采用同批测试数据主要针对渲染性能进行比对


## 200727-200801

`本周轮值主编`: 良辰 `下周轮值主编`：文玲

> 资讯
*  [ 200727 ] 前端周报 <https://mp.weixin.qq.com/s?__biz=MzUxMzcxMzE5Ng==&mid=2247498302&idx=1&sn=ee2ed71f19cce87e4acedaff80aaf487> [ from 文玲 ]

> 干货
* [ 200731 ] Node.js 在大前端领域的应用分析 <https://mp.weixin.qq.com/s/uSlXCu6IC0Kys6pgOBp47w> [ from 红梅 ]
* [ 200731 ] 你真的知道 React Portal 吗？ <https://juejin.im/post/6844904024378982413> [ from 思源 ]
* [ 200731 ] 传送门：React Portal <https://zhuanlan.zhihu.com/p/29880992> [ from 思源 ]
* [ 200727 ] 精读函数缓存  <https://zhuanlan.zhihu.com/p/164391037> [ from 良辰 ]

> 工具
* [ 200731 ] 前端项目接入云平台ci/cd操作手册  <http://fe.lvwan-inc.com/zhaowenling/cicd/cicd.md.html> [ from 文玲 ]
* [ 200731 ] 百度专网地图  <http://dugis.baidu.com/> [ from 大民 ]

## 200720-200725

`本周轮值主编`: 思源 `下周轮值主编`：良辰

> css
* [ 200724 ] 妙用 CSS变量，让你的 CSS 变得更心动 <https://mp.weixin.qq.com/s/whtfxJFea-mel00Cw3fZ5g> [ from 文玲 ]
* [ 200720 ]  你可能不太熟知的布局技巧 <https://mp.weixin.qq.com/s/HYUgb8jEI-aQhbN4sBajNw> [ from 良辰 ]
> 新东西
* [ 200724 ] Chrome 84 正式发布，支持私有方法、用户空闲检测！<https://mp.weixin.qq.com/s/QQIZcaS0QT8NXjUWXi6o0A>  [ from 文玲 ]
* [ 200724 ] 微信支持 H5 跳转 App、跳转小程序 https://mp.weixin.qq.com/s/wlVdXFtvOX-FSN-mjS2bqg  [ from 文玲 ]
* [ 200724 ] 微前端的现状和趋势 <https://segmentfault.com/a/1190000023365666> [ from 红梅 ]

> 干货
* [ 200708 ] 75行代码入门 WebGL <https://avikdas.com/2020/07/08/barebones-webgl-in-75-lines-of-code.html> [ from 君毅 ]
    * 以75行极简代码介绍运行webgl绘制内容的教程及基本核心元素
* [ 200723 ] Rome <https://romefrontend.dev/> [ from 君毅 ]
    * Rome is a linter, compiler, bundler, and more for JavaScript, TypeScript, HTML, Markdown, and CSS
* [ 200724 ] 什么时候适合使用 Map 而不是 Object <https://mp.weixin.qq.com/s/s2XG4Ly1V5lov1ZciWF0xg> [ from 思源 ]

> 工具
*  [ 200725 ] 介绍 5 款免费在线图像工具  <https://segmentfault.com/a/1190000023371362> [ from 红梅 ]



## 200713-200716

`本周轮值主编`: 红梅 `下周轮值主编`：思源

> 工具
* [ 200713 ] SVG 在线编辑器 <https://svg-editor.6cm.co/> [ from 君毅 ]

> 干货
* [ 200717 ] HTTP的实体数据 <https://mp.weixin.qq.com/s/_RtJYKVWlQ6cFqXgeaP9JA> [ from 思源 ]
* [ 200716 ] code-review之前端代码优化 <https://juejin.im/post/5f0fccdd5188252e65442aea> [ from 文玲 ]
    * if -> switch -> 策略模式
    * includes
    * for in -> for of
    * set实现数组去重
    * 箭头函数绑定this
    * DocumentFragment、innerHTML
    * 防止内存泄露
    * 使用防抖和节流
    * script defer和async属性支持异步加载
* [ 200715 ] Node 服务中如何更好地打日志  <https://juejin.im/post/5f0e5701f265da230e6b68c8>  [ from 红梅 ]

> 经验
* [ 200716 ] 如何实现 Bilibili 视频播放Chrome 媒体控制效果 <https://www.jackpu.com/ru-he-shi-xian-bilibili-shi-pin-bo-fang-chrome-mei-ti-kong-zhi-xiao-guo/> [ from 红梅 ]
* [ 200714 ] 如何精确统计页面停留时长 <https://mp.weixin.qq.com/s/0CBL-pytcOGPtYSbz4WVsw> [ from 良辰 ]
* [ 200701 ] 斗鱼关注人数爬取 ── 字体反爬的攻与防 <https://cjting.me/2020/07/01/douyu-crawler-and-font-anti-crawling> [ from 君毅 ]
    * 把所有网络请求导出为 HAR 格式，方便搜索关键词
    * 通过使用 MutationObserver 我们可以监听任意 DOM 的修改事件



## 200705-200711

`本周轮值主编`: 君毅 `下周轮值主编`：红梅

> 工具
* [ 200709 ] stretchly <https://hovancik.net/stretchly/downloads> [ from 君毅 ]
    * 一个开源桌面软件，隔一段时间（默认25分钟）就跳出一个提示，提醒你离开电脑运动一下
* [ 200518 ] 是时候扔掉 Postman 了，Apifox 真香！ <https://mp.weixin.qq.com/s/n-YiC9hDpTcG_crewDwYaw> [ from 君毅 ]
    * Apifox = Postman + Swagger + Mock + JMeter

> 经验
* [ 200704 ] 高考人生的16条定律 <http://dwz.date/bzKx> [ from 文玲 ]

> 干货
* [ 200708 ] 这份 window.location 备忘单，让你更有条理解决地址路径问题！ <https://mp.weixin.qq.com/s/rsdy33_RpEKS1Kh9JDAYuw> [ from 思源 ]
    * window.location 对象备忘单
* [ 200706 ] 他们所说的 CDN 究竟是什么？ <http://dwz.date/bzG3> [ from 良辰 ]
    * A content delivery network or content distribution network (CDN) is a geographically distributed network of proxy servers and their data centers
* [ 200621 ] 分分钟教会你搭建企业级的 npm 私有仓库 <https://mp.weixin.qq.com/s/Q9JSBXx7eiq3GuAvg1itIw> [ from 君毅 ]
    * 介绍如何借助 cnpmjs.org 搭建私有 npm 仓库
* [ 200620 ] 8 Hacks For Your Next Tech Resume <https://dev.to/gemography/common-mistakes-in-dev-cvs-2a17> [ from 君毅 ]
    * 不要试图提及你掌握的所有技能，这会给人一种"万事通"的感觉
    * 将你的技能分成三个等级："精通"（proficient in）、"有实战经验"（experienced with）、"熟悉"（familiar with）
    * "精通"和"有实战经验"的技能，必须提供细节，要给出项目内容和你的个人成果

> 新鲜货
* [ 200707 ] 离线预渲染OPR：0成本接入 媲美SSR效果 <http://dwz.date/bzHc> [ from 大民 ]
    * 不同于SSR在用户访问阶段的渲染，OPR是一个独立于用户访问流程的渲染服务，它通过Puppeteer定期渲染页面并上传cdn，用户访问到的页面将会是纯静态页面，可以说是结合了SSR和Prerender两种方案
* [ 200708 ] Hightopo提供的响应式可视化大屏 <https://segmentfault.com/a/1190000023139734> [ from 红梅 ]
      * Hightopo 官网demo https://hightopo.com/demos/index.html

## 200629-200704

`本周轮值主编`: 晓朋 `下周轮值主编`：君毅

> 干货
* [200702] JSDOC https://jsdoc.zcopy.site [ from 思源 ]
* [200701] ECharts文档逆天了 https://mp.weixin.qq.com/s/AZINW1uWCFsxvuZScRZyyA [ from 思源 ]
* [ 200630 ] webgl 大规模图谱渲染引擎性能指标 <http://fe.lvwan-inc.com/zhaojunyi/SophonWeb/webgl/bench-mark.md.html> [ from 君毅 ]
    * 基于测试数据集确定新版webgl图谱渲染引擎性能指标
* 你应该知道的 NPM 知识都在这！<https://mp.weixin.qq.com/s/sRhuMQ3f6vjUkabUy_dEYQ> [ from 文玲 ]
* [ 200703 ] 加深对进程和线程的理解 <https://mp.weixin.qq.com/s/TySnUI3IJcY43dcnbtsO0w> [from 晓朋 ]
* [ 200702 ]  十分钟上手小程序开发，史上最全的《入门级》小程序开发 <https://juejin.im/post/5efd4c765188252e362e0d2d> [ from 红梅 ]
     * 小程序开发的整个过程，以及基本概念的介绍
* [ 200407 ]翻译|前端开发人员的10个安全提示 [ from 良辰 ]
 https://blog.zhangbing.site/2020/04/27/10-security-tips-for-frontend-developers/

> 工具
* [ 200615 ] 使用 Chii 调试移动端页面 <https://zhuanlan.zhihu.com/p/144169144> [ from 君毅 ]
    * 一个远程调试网页的工具，只要在网页里面加载这个库，就可以远程打开 Chrome 开发者工具，主要用于调试手机端网页

> 开源
* [ 200703 ] MXFlutter：基于JS的Flutter框架，用JS也能写出Flutter应用 <https://juejin.im/post/5efe9e3ae51d453487680ff3> MXFlutter 是一套基于JavaScript 的 Flutter 框架，可以用极其类似 Dart 的开发方式，通过编写 JavaScript 代码，来开发 Flutter 应用，或者使用 mxjsbuilder 编译器，把现有Flutter 工程编译为JS，运行在 mxflutter 之上。 [ from 文玲 ]
* [ 200701 ] Taro 3 正式版发布：开放式跨端跨框架解决方案 <https://juejin.im/post/5efbdb786fb9a07ea929c967> 支持跨框架（React\Nerv\Vue\jQuery）、跨端（H5、微信、支付宝、百度、字节跳动等小程序） [ from 文玲 ]

## 200622-200628

`本周轮值主编`: 文玲 `下周轮值主编`：晓朋

> 干货
* [ 200622 ] JavaScript 中内存泄漏的原因以及对策 <https://mp.weixin.qq.com/s/ud0lDh3nPW09JwMlOycwNw> [ from 文玲 ]
    * 全局变量
    * 闭包
    * 计时器
    * 事件侦听器
    * 缓存
    * 分离的 DOM 元素
* [ 200627 ] webpack 拍了拍你，给了你一份图解指南（模块化部分）<https://juejin.im/post/5ef754025188252e8f0f1eed> [ from 文玲 ]
    * webpack核心作用：模块隔离、模块依赖加载
* [ 200625 ] JavaScript常用API合集汇总 <https://mp.weixin.qq.com/s/Yo-fHw-9ZjRIfiwzd-2SMg> [ from 思源 ]
* [ 200628 ] 加深对 options 请求的理解   <https://mp.weixin.qq.com/s/zHxpII3LeePfTl4EOjcgCQ> [ from 晓朋 ]
* [ 200628 ] 跨域预检请求(OPTION) <http://fe.lvwan-inc.com/fanxiaopeng/option-request.md.html> [ from 晓朋 ]
* [ 200619 ] JS数组奇巧淫技 <https://juejin.im/post/5d71fff5f265da03e4678328> [ from 红梅 ]

> 开源
* [ 200608 ] 让你纵横 GitHub 的五大神器 <https://mp.weixin.qq.com/s/4BHRA0p2n5pnV2XApgfURw> [ from 思源 ]
* [ 200628 ] 快速生成手绘风格的高亮线条 <https://github.com/rough-stuff/rough-notation> [ from 良辰 ]

> 资讯
* [ 200622 ] Deno将停止使用TypeScript，并公布五项具体理由 <https://mp.weixin.qq.com/s/nl1VwbqpsZhvCsfnv7lj9g> [ from 文玲 ]
    * 变更文件时，typescript导致连续编译过程非常缓慢
    * TypeScript 结构会引发一系列运行时性能问题
    * 增强了代码组织负担
    * 内部代码与运行时 TypeScript 声明必须以手动方式保持同步d.ts文件
    * 维护着两套相似的TS 编译器主机
* [ 200626 ] 2020去中心化Web开发者报告 <https://mp.weixin.qq.com/s/b3c1dLKWYZn0UupU6YZUYw> [ from 文玲 ]
    * 关注点：数据主权、隐私和健壮性（例如抗审查能力）
    * Web 3.0 主要由区块链社区推动，非常关注金融、电子商务、人工智能、安全和企业大数据等业务
    * DWeb 的拥护者（例如 IPFS 和 Internet 档案库）更受意识形态驱动，着重于权力下放、数据主权、安全性、隐私和抗审查能力
    * 核心见解
        * DWeb 产业仍不成熟，正在初期发展之中
        * DWeb 生态系统缺乏业务模型，超过一半的项目没有变现手段
        * 数据隐私、数据主权和技术弹性是 DWeb 最令人期待的特性

