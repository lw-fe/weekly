# 技术快报

> 业界技术跟进，不限于前端技术，按时间逆序梳理，每周一份，[轮值主编制度参考](./editors.md)


## 20200217-20200222
`本周轮值主编`: 海萍 `下周轮值主编`: 良辰

> 最佳实践  

* [ 200114 ] 花椒前端用WebAssembly提升前端应用解压缩性能的尝试：<https://mp.weixin.qq.com/s/4lkgmLIkowoPOwgd1g6i0w>  [ from 君毅 ]
   * JavaScript运行时只有一个主线程(UI线程)，而Wasm的加载、编译、实例化、下载压缩包、解压文件这些工作如果都放在主线程执行会严重影响页面性能，所以可以把这些都放进Web Worker中以单独的线程去执行，减轻主线程的压力
* [200109] JavaScript 中的位运算和权限设计  <https://zhuanlan.zhihu.com/p/90618809>  [ from 良辰 ]

> 干货  

* [ 200221 ] immer.js实用文档 <https://juejin.im/post/5c079f9b518825689f1b4e88> [ from 思源 ]
* [ 200221] 将Chrome调试器里的JavaScript变量保存成本地JSON文件 <https://blog.csdn.net/i042416/article/details/82556800> [ from 红梅 ]
* [ 200212 ] 阅读笔记之-《前端性能检查表(Front-End Performance Checklist)》 <https://juejin.im/post/5e4298696fb9a07cae135578> 性能优化大纲与知识体系  [ from 文玲 ]
* [ 180731 ] Data URL与base64 <https://blog.csdn.net/qq_37487977/article/details/81298687>  [ from 晓朋 ]
   * dataurl基本原理
   * 优缺点
   * css中使用dataurl
   * 不同语言将文本转换为base64注意事项

> 其他

* [ 200118 ] 中国开源前端为王？GitHub 5.4亿条日志背后的数据故事 https://mp.weixin.qq.com/s/LUsTU_iLsIOWBP8yYvGdcw [ from 思源 ]


## 20200210-20200215
`本周轮值主编`: 思源 `下周轮值主编`: 海萍

> 最佳实践  

* [ 200214 ] 如何使用css向js传参 <https://www.zhangxinxu.com/wordpress/2020/02/css-params-to-js/> [ from 晓鹏 ]
* [ 200121 ] 高质量前端快照方案：来自页面的「自拍」：https://mp.weixin.qq.com/s/ebxO5MtkQHi-U21MO6LIuA [ from 君毅 ]
    * 从内容完整性、清晰度优化和转换效率，进一步介绍了高质量的快照解决方案
* [ 200212 ] CSS 故障艺术：https://segmentfault.com/a/1190000021730935 [ from 红梅 ]
  *  故障艺术的概念
  *  使用混合模式和 clip-path 实现的故障艺术

> 干货  

* [ 200212 ] 如何让你的 React 『变慢』？探析 Array Diff 的一些边角特性 <https://juejin.im/post/5d9b648ef265da5b9d1eedfc> 
demo <https://codesandarray-diff-example-kw112?fontsize=14> [ from 文玲 ]
    * React实现的是较快解，非最优解
    * Array Diff问题：如何从数组 A 通过最少的变换步骤到数组 B
    * 操作的类型有：删除元素，插入元素，移动元素
    * 求解一下最少移动步数: 最长上升子序列（LIS，Longest Increasing Subsequence）,算法的时间复杂度是 O(n^2)
    * React基于平衡效率与最优解，采用混合算法，牺牲一定正确性的前提下，将复杂度降为O(n)
* [ 200127 ] 纯前端实现人脸检测，给你的头像戴上口罩  <https://zhuanlan.zhihu.com/p/104070435> [ from 海萍 ]
    * demo地址 <https://zamhown.gitee.io/wear-a-mask/>
    * github地址 <https://github.com/zamhown/wear-a-mask>
* [ 200214 ] 什么是 globalThis，为什么要学会使用它？ https://mp.weixin.qq.com/s/tLgYG4_NJU1GNFrT8jOI2A [ from 思源 ]
* [ 200214 ] Tailwind CSS 是一个工具集 CSS 框架<https://www.tailwindcss.cn/> [ from 学聪 ]
* [ 200214] https://github.com/oubenruing/svg-text-animate 输入文本转为svg动画 [ from 良辰 ]

> 其他

* [ 200210 ] 我拆了20款口罩，在防病毒这件事上，希望对你有用 <https://zhuanlan.zhihu.com/p/104232116?utm_source=wechat_session&utm_medium=social&utm_oi=874339868761808896> [ from 思源 ]

## 20200203-20200207

`本周轮值主编`: 红梅 `下周轮值主编`: 思源

> 干货
* [ 200203 ] Popper 2.0: Tooltip & Popover Positioning Engine：https://popper.js.org/  [ from 君毅]
    * No detachment
    * You don't have to change the DOM context of your tooltip or popover element
    * Still lightweight
* [200204] GeoAtlas http://datav.aliyun.com/tools/atlas/# [ from 思源]

> 最佳实践
* [ 200204 ] 前端自动化部署的深度实践 <https://juejin.im/post/5e38ec1ce51d4526c932a4fb> 本文介绍使用conventional-changelog工具自动生成更新日志 [ from 文玲]

> 其他
* [200203] 分析GitHub 上 5.46 亿条日志 <https://www.infoq.cn/article/dCY0AHH71rBBjq3pIfh7> [ from 红梅]

## 20200113-20200120

`本周轮值主编`: 君毅 `下周轮值主编`: 红梅

> 干货
* [ 20200102 ] CSS inherit是继承，那initial和unset呢？<https://www.zhangxinxu.com/wordpress/2020/01/css-initial-unset/> [from 君毅]
    * initial并不能把样式设置为浏览器原始样式，而是设置为初始值
    * unset表示不固定值，特性如下，当前元素浏览器或用户设置的CSS忽略，然后如果是具有继承特性的CSS，如color, 则使用继承值；如果是没有继承特性的CSS属性，如background-color, 则使用初始值
* [ 200118 ] 如何解决 Render Props 的回调地狱 <https://juejin.im/post/5e224ba651882521414ae5e6> [from 文玲]
    * Render prop是一种设计 React 组件的有效技术。然而，影响其可用性的一个问题是回调地狱。函数组合或类组件方法可以解决回调地狱的问题。使用多个 Render prop 回调函数使用彼此的结果，那么react-adopt是一个很好的解决方法
* [ 200114 ] VUE vs React 高手过招！ <https://juejin.im/post/5e1c2ee6f265da3e395838b9> [from 文玲]
    * react和vue在jsx、渲染、事件处理、生命周期等各方面下的比较
* [ 200118 ] 这可能是最好用的 CSS 技巧 <https://juejin.im/post/5e225a0751882536a627fa71> [from 子哲]
* [ 200113 ] 你可能不知道的React Hooks <https://mp.weixin.qq.com/s/M54fR8UP8sBZXuFp-Cy0Jg> [from 思源]
    * 通过实现计数器来熟悉hooks的基本用法
* [ 200113 ] 字节跳动面试官：请你实现一个大文件上传和断点续传 <https://juejin.im/post/5dff8a26e51d4558105420ed> [from 红梅]

> 新鲜货
* [ 200106 ] 清华姚班毕业生开发新特效编程语言，99行代码实现《冰雪奇缘》，网友：大神碉堡！创世的快乐 <https://mp.weixin.qq.com/s/H7YAcOTjM1RSEU4HpQRkkA> [from 君毅]
    * Taichi is a high-performance programming language for computer graphics applications

> 沉淀
* [ 200118 ]  金融中心决策引擎配置中心总结 <http://fe.lvwan-inc.com/zhaojunyi/fin-decision/fin-decision-summary.md.html> [from 君毅]
    * 决策引擎配置中心向风控业务人员提供了风控模型定义，决策规则编写、测试、发布上线、下线、模型运行情况监控分析等功能，从而能够提供自动化的风控决策服务

> 鸡汤
* [ 20191231 ]  2020年，陆奇59岁：我给20、30、40岁年轻人的建议 <https://mp.weixin.qq.com/s/4rB4N_qKEP_9E18Xp1MjQg> [from 君毅]
    * 59岁的陆奇还在试图重构知识体系，20多岁怎能不学？

## 20200106-20200111

`本周轮值主编`: 学聪 `下周轮值主编`: 君毅

* [20200111] C 是 2019 年度编程语言！<https://mp.weixin.qq.com/s/vR8yF_lRIvgEhEZDhkDk7A> [from 文玲]
* [20200111] 第 4 种 Web 语言来了：WebAssembly：15 篇前端热文回看！<https://mp.weixin.qq.com/s/JHv6w4TRyjBq6gzzX7oRSQ> [from 文玲]
* [20200111] 如何答一道惊艳面试官的数组去重问题？<https://mp.weixin.qq.com/s/jJDdFMGSKlqaK_nXAjWULA> [from 文玲]
* [20200109] 美团开源Logan Web：前端日志在Web端的实现 <https://mp.weixin.qq.com/s/j_8_kSQ4BrYR-UzIEIEIbw> [from 思源]
* [20200111] redux的state树应该如何设计？ <https://www.zhihu.com/question/50888321> [from 学聪]
* [ 20200103 ] 程序员"转行"项目经理的二三事：<https://mp.weixin.qq.com/s/EUNmjGbv6DlRFLU03p5A8A> [from 君毅]
    * 一个程序员以项目经理(PM)角色负责落地一个港口的金融项目的经验分享
* [ 20200107 ] 苦练 CSS 基本功——图解辅助线的原理和画法  <https://segmentfault.com/a/1190000021507641>  [from 海萍]
* [ 20200110 ] 横向对比Element-tree、ztree、ivew-tree性能对比分析与源码修改自定义组件 <https://juejin.im/post/5e17c1615188254bee1b452f> [from 红梅]
* [20200111] 2019最佳视觉错觉 <http://illusionoftheyear.com/cat/top-10-finalists/2019/> [ from 良辰]

## 191230-20200104

`本周轮值主编`: 晓朋 `下周轮值主编`: 学聪

> 干货

* [ 200103 ] 图解 JavaScript 垃圾回收 — 现代 JavaScript 教程 <https://juejin.im/post/5e0ddc24f265da5d1805ee6f>  [from 文玲]
    * 垃圾回收是自动完成的，我们不能强制执行或是阻止执行。
    * 当对象是可达状态时，它一定是存在于内存中的。
    * 被引用与可访问（从一个根）不同：一组相互连接的对象可能整体都不可达。

* [ 200101 ] 10行代码看尽redux原理 —— 全面剖析redux | react-redux | redux中间件设计实现 <https://juejin.im/post/5def4831e51d45584b585000> [from 文玲]
* [ 20191128 ] 那些欲罢不能的实用工具：https://isux.tencent.com/articles/design-tools.html  [from 君毅]
  * Magica Voxel 一款快速进行体素建模的3D设计软件，无需任何3D软件基础，像玩游戏一样，类似 Minecraft的操作，体积小巧，免费开源，通过内置的光影引擎，可以快速输出绚丽夺目的 3D作品
  * IconMonstr 可以很方便地在线设置图标颜色、图标格式，一键下载
  [ 20191225 ] 2019年度交互总结：https://mp.weixin.qq.com/s/xaLK-ZgKAg0kU_eMdtOxsw
  * 透过一些产品的设计，回顾了2019年交互设计的趋势

* [ 20191220 ]  腾讯开源内部跨端框架 Hippy，打磨三年，日均 PV 过亿<https://zhuanlan.zhihu.com/p/98945706>

* [ 20200103  ] 基于 CSS3 Animation 使用 React 构建的弹幕组件  <https://github.com/zerosoul/rc-bullets>  [from 海萍]
   * 管理弹幕：暂停、隐藏、清屏等
   * 设置弹幕：速度、循环次数、延迟播放、自定义动画类型等

* [20200101] web性能监控相关知识点 http://www.alloyteam.com/2020/01/14184/ [from 良辰]

> 资讯

* [200103]就在几天前，听说用了 YYYY-MM-dd 的程序员，都在加班改 Bug ! https://mp.weixin.qq.com/s/uKjLwNU9UFZk83YhiTWnVQ [from 思源]
* [20200103] 阿里云杜欢：云上Serverless开发能力将成为前端的“金手指” https://mp.weixin.qq.com/s/mAqxyk4U1YSrwohwPQE3PQ [from 红梅]
* [20200103] 浏览器中原生运行的第四种语言诞生：WebAssembly 1.0 成为 W3C 的推荐标准 https://mp.weixin.qq.com/s/oDjMsrH5k6ufd1Zpron7vA [from 红梅]

## 191223-191228

`本周轮值主编`: 文玲 `下周轮值主编`: 晓朋

> 干货
* [ 191226 ] 解密国内BAT等大厂前端技术体系-完结篇<https://juejin.im/post/5e02c0896fb9a0160770ae9e> 大前端建设脉络：基础设施、服务层、应用层、UI组件库、小程序、跨 >平台动态化、工程智能化 [ from 文玲 ]
* [ 191223 ] Node.js入门指南和实践<https://juejin.im/post/5e0006c251882512795675f9> 13个基础核心模块 [ from 文玲 ]
* [ 191225 ] 用60行代码实现一个高性能的圣诞抽抽乐H5小游戏 <https://juejin.im/post/5e02cddf518825125015fd2f> [ from 文玲 ]
* [ 191227 ] 令人期待的 JavaScript 新特性 <https://mp.weixin.qq.com/s/5Fm2p2sKUBd5Ub4LCzLr1w> [ from 红梅 ]
    * 类的私有变量
    * 可选链操作符
    * 空位合并操作符
    * BigInt
    * static字段
    * Top-level await
    * WeekRef
* [ 191222 ] CSS flex属性深入理解 <https://www.zhangxinxu.com/wordpress/2019/12/css-flex-deep/> [ from 晓朋 ]
* [ 191225 ] 72个炫酷的CSS技巧 <https://juejin.im/post/5e033c946fb9a0164b4ef360> [ from 子哲 ]
* [ 191219 ] 身为前端，你不得不懂的一些HTTP知识：<https://dwz.cn/7LupIalP> [ from 君毅 ]
    * netcat、ss、lsof命令的使用
    * tcp协议的三次握手和四次挥手
    * udp协议的基本表现过程以及icmp报文发送的原因
    * tcpdump、nc命令的使用
    * 三道关于TCP/IP协议的面试题答案

> 资讯
* [ 191226 ] 2019 年 JavaScript 生态圈调查报告出炉！<https://mp.weixin.qq.com/s/TPfSXJX8Ml4xCCbjehX5Wg> [ from 良辰 ]

> 其他
* [ 191220 ] 你绝对想不到柱形图背后有这么多故事 <https://github.com/ProtoTeam/blog/blob/master/201912/1.md> [ from 思源 ]

## 191215-191221

`本周轮值主编`: 良辰 `下周轮值主编`: 文玲

* [ 191219 ] 关于React Hooks和Immutable性能优化的实践 <https://juejin.im/post/5dfa3c65f265da33b47c87bf>  from [文玲]
    immutable 对象数据内部采用是多叉树的结构，凡是有节点被改变，那么它和与它相关的所有上级节点都更新
* [ 191206 ] 2020潘通年度流行色 「经典蓝」新鲜出炉！（附配色方案）：https://www.uisdc.com/2020-classic-blue from [君毅]
    9 套适合进行数字设计的配色方案，并且标注上了相应的 HEX 值便于精准取色，请尽情取用
* [ 191212 ] 面试完50个人后我写下这篇总结 <https://juejin.im/post/5df1e312f265da33d039d06d> css、js、vue、浏览器相关知识点总结 from [文玲]
* [ 191218 ] code clean JavaScript https://github.com/alivebao/clean-code-js from [思源]
* [ 191214 ] 我收集了 12 款自动生成器，效果太逆天！from [子哲]
    https://mp.weixin.qq.com/s?__biz=MzA5MzY4NTQwMA==&mid=2651015300&idx=1&sn=afdb4762f77eb1b75937785690a12437
* [ 191217 ] ant-v柱状图优化 from [良辰]
    https://juejin.im/post/5df894ca518825123509446d

## 191209-191214

`本周轮值主编`: 思源 `下周轮值主编`: 良辰

> 资讯

* [ 191210 ] 2019年前端大事件回顾：流年笑掷，未来可期 <https://juejin.im/post/5def782ce51d4558181d27ce> [from 文玲]
    * 关键词：WebAssembly, GraphQL, Typescript, Css-In-JS, Flutter, Svelte, Deno, AR/VR, 容器化

> 干货

* [ 191211 ] Webpack HMR 原理解析 <https://zhuanlan.zhihu.com/p/30669007> [from 思源]
* [ 191213n] chrome插件开发详细教程 <https://www.cnblogs.com/liuxianan/p/chrome-plugin-develop.html> [ from 晓鹏 ]
* [ 191213 ] React Hooks: Memoization：https://juejin.im/post/5d58ef09e51d456206115a02 [ from 君毅 ]
    * 介绍了对性能有要求或追求的开发者更好地利用hooks的一些tips
* [ 191213 ] ：高质量前端快照方案：来自页面的「自拍」 https://juejin.im/post/5df2e8ab6fb9a0163770816d [ from 红梅 ]
    * 基础方案 html2canvas  canvas2image
    * 几种情况资源跨域、内容未加载完、滚动问题带来的内容不完整如何解决的
    * 清晰度如何优化
    * 转换的效率如何提升
* [ 191212 ] 赏心悦目一下：最佳色彩搭配组合 <https://mp.weixin.qq.com/s/NrTbvD5vKelS1YUnaqfwJw> [ from 海萍 ]
* [ 191205 ] https://tgideas.qq.com/gicp/news/475/8882405.html [ from 良辰 ]
    * 表单体验优化建议


> 工具

* [ 191211 ] Webpack Bundle Analyzer <https://github.com/webpack-contrib/webpack-bundle-analyzer>
* [ 191206 ] Firefox Web Replay - 前端开发者的未来利器：https://mp.weixin.qq.com/s/rAt6lobXvnkp01CFLYg6DA [ from 君毅 ]
    * Firefox Web Replay可以录制Firefox标签页上的行为，并进行重放。这里所说的重放，可不是简单的视觉上的重放，而是高保真的。JavaScript、DOM和CSS的行为都可以精准的重放


## 191202-191206

`本周轮值主编`: 海萍(思源请假，暂代) `下周轮值主编`: 思源

> 知识点

* [ 191206 ] 你可能不知道的15个 Git 命令  <https://segmentfault.com/a/1190000021190289>  [from 海萍]
   * git checkout - 可快速切换到上一分支
* [ 191206 ] 你真的懂package.json吗 <https://juejin.im/post/5dea1095e51d4558083322e2> [from 文玲]
* [ 191204 ] 状态管理之 Flux、Redux、Vuex、MobX（概念篇） <https://juejin.im/post/5de77800518825125503ec27> [from 文玲]

> 最佳实践

* [ 191106 ] React + Typescript 工程化治理实践 <https://github.com/ProtoTeam/blog/blob/master/201911/2.md> [from 君毅]
   * 本文是对一次 React + TypeScript 组件的工程化治理过程所做的总结。如果你的项目也是 React + TypeScript 组件，并且会发布为 NPM package 给其他人使用，那本文应该可以为工程化方面的建设提供一些参考
* [ 191206 ] redux 官方指导，包含推荐模式，最佳实践和建议 <https://redux.js.org/style-guide/style-guide> [from 良辰]


> 新特性
* [ 191206 ] An Introduction to the Picture-in-Picture Web API <https://css-tricks.com/an-introduction-to-the-picture-in-picture-web-api/> [from 红梅]
  * Chrome supports a ‘picture-in-picture’ mechanism for creating floating video windows that continue to play even if a user navigates to a different page. Firefox and Safari have support via proprietary APIs too.

* [ 191203 ] 你即将使用的ES2020新功能  <https://juejin.im/post/5de76f076fb9a0165c710049>  [from 子哲]

> 资讯
* [ 191202 ] Saying goodbye to Flash in Chrome <https://www.blog.google/products/chrome/saying-goodbye-flash-chrome/> [from 君毅]
   * Adobe announced its plans to stop supporting Flash at the end of 2020

> 心得   
* [191202] 别让自己“墙”了自己 <https://coolshell.cn/articles/20276.html> [from 思源]


## 191125-191130

`本周轮值主编`: 红梅 `下周轮值主编`:  思源

> 最佳实践

* [ 191115 ] 蚂蚁前端研发最佳实践 <https://mp.weixin.qq.com/s/BlbXnt-TRGxQwklV87IkzA> [ from 良辰 ]

> 开源
* [ 191129 ] antV G6 Graphin 图的分析洞察 <https://github.com/antvis/graphin>
            <https://antv-graphin.gitee.io/zh/GraphinStudio>  [ from 鹏程 ]

> 干货
* [ 190313 ] 为什么你学不会递归？告别递归，谈谈我的一些经验：<https://mp.weixin.qq.com/s/mJ_jZZoak7uhItNgnfmZvQ>
    * 作者总结了一份递归三大要素，用于简化递归的使用方法 [ from 君毅 ]

* [ 191129 ] 大多数前端工程师了解但并不擅长的HTML语义化 <https://juejin.im/post/5de090ae6fb9a0718d4cb039> [ from 红梅 ]
* [ 191129 ] 几个不错的console调试技巧 <https://juejin.im/post/5ddd373cf265da05d7582ce8> [ from 红梅 ]
* [ 191129 ] 动画: 一个浏览器是如何工作的 <https://juejin.im/post/5de0e4dfe51d45359c14e1af>
    * 图解浏览器工作原理：DNS解析、TCP连接、HTTP请求、构建DOM树、构建CSSOM树、生成渲染树、合成绘制 [ from 文玲 ]
* [ 191129 ] 为什么Vue3.0不再使用defineProperty实现数据监听？<https://mp.weixin.qq.com/s/O8iL4o8oPpqTm4URRveOIA>  [ from 正杰 ]

> 科普
* [ 191129 ] 硬核科普：屏幕到底是怎么显示出画面的？ <https://weibo.com/2214257545/IitxMmcX0> [ from 明成 ]
    * CRT vs LCD vs OLED

> 资讯
* [ 191129 ] The Firefox UI is now built with Web Components <https://briangrinstead.com/blog/firefox-webcomponents/>  [ from 建中 ]

> 新鲜货
* [ 191129 ] 在前端 Word 还能这样玩 <https://segmentfault.com/a/1190000021111457> [from 思源]
    * 纯前端 Word 解析并提取 Word 中的图片

## 191118-191123

`本周轮值主编`: 君毅 `下周轮值主编`:  红梅

> 运维
* [ 191122 ] 写给前端工程师的 docker 简易入门 <https://juejin.im/post/5dd72b16e51d45351409073d> [ from 文玲 ]
  * docker client: 即 docker 命令行工具
  * docker host: 宿主机，docker daemon 的运行环境服务器
  * docker daemon: docker 的守护进程，docker client 通过命令行与 docker daemon 交互
  * container: 最小型的一个操作系统环境，可以对各种服务以及应用容器化
  * image: 镜像，可以理解为一个容器的模板配置，通过一个镜像可以启动多个容器
  * registry: 镜像仓库，存储大量镜像，可以从镜像仓库拉取和推送镜像

> 开源
* [ 191122 ] strapi，Open source Node.js Headless CMS to easily build customisable APIs <https://github.com/strapi/strapi/> Headless CMS 是一种设用于小微企业的业
务'中台'解决方案。通过Strapi 我们可以快速搭建简单的外围业务模型, 复用通用的服务和插件 [ from 文玲 ]
  * 可视化、快速的业务模型创建。类似创建数据库模型（数据库无关），可以灵活地配置各种字段类型(除了原始类型、还支持邮箱、文件上传)以及模型关系。
  * 暴露规范的接口。支持 Restful 和 GraphQL。内置支持排序、分页、过滤、自动生成文档
  * 内置权限控制系统。角色、JWT 鉴权
  * 轻松集成内部系统。可以灵活地与自己的内部系统对接
  * 扩展性。插件系统

> 工具
* [ 191112 ] 运行 JavaScript 代码片段的 20 种工具 <http://xlbd.me/20-kind-of-tools-to-run-javascript> [ from 海萍 ]
  * 如果想运行一段代码得到测试结果，最快的方式会选用浏览器控制台，因为浏览器就是最棒的工具
  * 如果想要写一个 demo 放在博客上，我会选择 jsfiddle、codepen、codesandbox，这里提供了写demo需要的一切
  * 如果想分享漂亮的代码片段，我会使用 Carbonize 生成一张图片，就像博文开头的那张图片
* [ 191123 ] < css-doodle/>一个用于使用CSS绘制图案的Web组件 <https://css-doodle.com/> [ from 正杰 ]
  * The component will generate a grid of divs by the rules (plain CSS) inside it. You can easily manipulate those cells using CSS to come up with a graphic pattern or an animated graph

> 干货
* [ 191121 ] 前端智能漫谈-写给前端的AI白皮书 <https://mp.weixin.qq.com/s/dXjrsR8DSWo1DmDlhw91jA> [ from 君毅 ]
  * 本文从4各部分(第三方接口、重头训练一个模型、使用成熟模型、再次训练)来介绍了前端应用人工智能的方法
* [ 191122 ]  双11模块79.34%的前端代码是怎样智能生成的？ <https://mp.weixin.qq.com/s/hl8mPVQi2vV0WSUIOaAhPw> [ from 晓鹏 ]
  * 本文将通过阿里的实践案例解答了 D2C 如何实现的视图代码和部分逻辑代码的自动生成
* [ 191122 ] 在 React 中使用 TypeScript <https://www.infoq.cn/article/G9HJfXzzWqsPdrqcwt4A> [ from 明成 ]
  * TypeScript 是什么
  * 如何在 React 使用它
  * 为何或为何不使用它
* [ 191121 ] 黄轶：如何成为公司独当一面的工程师 <https://mp.weixin.qq.com/s/ip2bdYEnTuZo00eyiKo1Yg> [ from 思源 ]
  * 从技术能力和业务能力 2 个方面阐述了如何成长为独当一面的工程师

> 资讯
* [ 191112 ] 苹果试图“杀死”Web 技术 <https://www.infoq.cn/article/luANFB6epLu0xREgJJ9S> [ from 君毅 ]
  * 给开发人员在苹果平台上使用基于 Web 技术构建应用的做法设下重重障碍，最终逼迫这些开发者退缩

> 其他
* [ 191106 ] 微软代码女神潘正磊：程序员跟年龄关系真不大 <https://www.infoq.cn/article/14ze3NoAu8eFszbbM3LP> [ from 君毅 ]
  * 技术需要深耕，同时需要扩展宽度
  * 开源虽然有挑战，但能够使代码更好
  * 不能只写代码，对于领域的把握、资深的认知不能缺失
  * 做技术只需管好自己一个人，做管理更多的是管好他人
  * 女性程序员应该更自信，敢于表达，要勇于挑战别人对你不行的偏见
* [ 191016 ] 除了大兴机场，她还给中国留下了哪些奇迹 <https://mp.weixin.qq.com/s/gVzRCmyrd2b74krhBpYD1w> [ from 子哲 ]
  * 由扎哈·哈迪德及其团队设计的中国明星建筑，感受它们给我们带来的视觉冲击与美感
* [ 191117 ] 专访曾鸣：下沉是中国过去创新模式的最后一次爆发，往后大家都得做更辛苦的事 <https://mp.weixin.qq.com/s/3MZ05tX6cT-HuJahPG_IpA> [ from 建中 ]
  * 面向未来，现在的创业者们首先应该调整预期，因为“容易挣的钱，肯定是没了。往后大家都得做更辛苦的事

## 191111-191116

`本周轮值主编`: 学聪 `下周轮值主编`:  鹏程

* [ 20191115 ] 浅谈 React/Vue在 DOM Diff 算法上的异同<http://www.imooc.com/article/295545>[ from 正杰 ]
* [ 20191115 ]  snyk发布了JavaScript 框架状态安全报告2019 <https://snyk.io/blog/javascript-frameworks-security-report-2019/  https://cloud.tencent.com/developer/article/1539159>[ from 红梅 ]
  * Angular vs. React 核心项目安全
  * Angular vs. React模块生态系统安全性
  * Angular vs. React 安全态势
  * 前端生态系统安全性
* [ 190628 ] 用户的常见认知偏误 <https://jdc.jd.com/archives/212987>[ from 良辰 ]
* [ 191108 ] 商业感觉不好，我是不是没救了？<https://mp.weixin.qq.com/s/frw-Wkhty1rpG9cz0x6zGg>[ from 君毅 ]
  * 深入到人民中去，带着人民币回来
* [ 191115 ] videoconverter.js：<https://bgrins.github.io/videoconverter.js/>[ from 君毅 ]
  * videoconverter.js is a program that lets you process videos in your browser.
* [ 191115 ] 我来了我来了我又来了~可能是最全的 “文本溢出截断省略” 方案合集啦<https://juejin.im/post/5dc15b35f265da4d432a3d10#heading-3>[ from 子哲 ]
* [ 191115 ] 文章生成器 <https://suulnnka.github.io/BullshitGenerator/index.html>[ from 建中 ]
* [ 191115 ] 现代JavaScript实践：ECMAScript简史和JavaScript的未来<https://segmentfault.com/a/1190000010074709#articleHeader2>[ from 晓鹏 ]
* [ 191115 ] 重构复杂的 React 组件：编写高效且可读组件的 5 个最佳实践<https://www.infoq.cn/article/Ry4IcKy5CRB1PoKVi0qL> [ from 明成 ]
* [ 191114 ] 你真的了解字体吗？ <https://mp.weixin.qq.com/s/ZwLzXjUFYBiAfN50_52dqw> [ from 思源 ]
* [ 191115 ] web 动画作品集合 <https://github.com/chokcoco/css3-> [ from 文玲 ]
    * css3 3D行星运转<http://chokcoco.github.io/demo/css3demo/html/exampleSolarSystem.html>
    * 使用单标签完成各种图案<http://chokcoco.github.io/magicCss/html/index.html>
    * 圆锥渐变实现酷炫光影效果 <https://codepen.io/Chokcoco/pen/gRRdQq>
    * font-variation-settings 文字动画<https://codepen.io/Chokcoco/pen/oMrWJB>
    * 3D数字计数<https://codepen.io/Chokcoco/pen/qXVxyw>
    * CSS 实现意想不到的按钮效果<https://codepen.io/Chokcoco/pen/MGPwLg>
    * 纯 CSS 实现文字输入效果 <https://codepen.io/Chokcoco/pen/WXGoGB>
* [ 191115 ] [如何写出 point free 风格的代码](https://lambda.academy/clean-code-with-ramda/) [ from 陈荣 ]

  `point free` 就是脱离数据的代码风格。通过做到 `point free`，我们做到了行为和数据的分离，这利于我们写出更安全（组合行为时没有副作用），更易扩展（脱离数据的逻辑容易复用），和更易理解（读高阶函数的组合就像读普通英文一样）的代码。
* [ 191114 ]node http HPE_UNEXPECTED_CONTENT_LENGTH [ from 学聪 ]

  > reaseon: Content-Length can't be present with chunked encoding

  [Transfer-Encoding](https://blog.csdn.net/u014569188/article/details/78912469)
  [node http module commit log](https://github.com/nodejs/node/commit/375f35514c51fa603dae9fac86bb61c0503cb678)

  ***the server is sending both a Content-Length header and a Transfer-Encoding: chunked header, which is a violation of the HTTP spec.***

## 191104-191109

`本周轮值主编`: 晓朋 `下周轮值主编`: 学聪

> css

* [ 全面掌握 Content 的用法] <http://www.imooc.com/article/294954> [ from 正杰 ]
	* 清除浮动
	* 生成一些装饰性的符号或文字
	* 使用 content: attr(data-tip)实现自定义的悬浮提示效果
	* 使用 content: counter(item)实现计数器
	* Counter-reset 属性
	*  Counter-increment
	* 使用 content: counters(item, string)实现复杂的列表嵌套的序号问题

* 【 纯css实现的油画效果，在chrome下是很完美的，别的浏览器看起来呈现出有趣的效果 ] <https://diana-adrianne.com/purecss-lace/> [ from 红梅 ]
* [ 你应该知道的折叠屏收集适配 ] <https://juejin.im/post/5dc4cc0bf265da4d525fdcdb> [ from 文玲 ]
    * 响应式设计9项基本原则
    * 折叠屏常见适配问题
* [ 2019年，是否可以抛弃 CSS 预处理器？ ] <https://dwz.cn/rYjoP0Z3> [ from 海萍 ]

> 框架&库

* [ 打造高品质Axure组件库，就是这么简单！ ] <http://www.woshipm.com/rp/779504.html> [ from 学聪 ]
* [ SWR - React Hooks for Remote Data Fetching：]<https://swr.now.sh> [ from 君毅 ]
	* SWR is a React Hooks library for remote data fetching. With SWR, components will get a stream of data updates constantly and automatically, Thus, the UI will be always fast and reactive
* [ React推出并发模式：可中断渲染、指定加载顺序、并行处理多状态 ] <https://mp.weixin.qq.com/s/dYnARPfMptj1-iHL9HAjug>[ from 思源 ]

> 方法论

* [ 降低软件复杂性的一般原则和方法 ]<https://mp.weixin.qq.com/s/-Gu_XkY2bZq9Lf2ZCJZPtQ> [ from 晓朋 ]
* [ 玉伯：我的前端成长之路 ] <https://www.yuque.com/yubo/morning/grow-up-at-alibaba> [ from 学聪 ]
* [ 重构：代码命名之逆袭女神 ] <https://juejin.im/post/5db94780e51d452a34438f43>[ from 子哲 ]

> 人工智能 & 大数据

* [ 你所不知道的 AI 进展 ] <http://www.ruanyifeng.com/blog/2019/10/artificial-intelligenence.html> [ from 明成 ]

> 资讯

* [ 现代 Web 开发的现状与未来（JSDC 2019 演讲全文）]<https://zhuanlan.zhihu.com/p/88616149> [ from 良辰 ]
* [ 研究估计五成 WebAssembly 网站将其用于恶意目的 ] <https://dwz.cn/uGYE2Gvc> [ from 大民 ]
* [ Edge新的Logo，不再像ie浏览器 ] <https://www.theverge.com/2019/11/2/20944341/microsoft-edge-chromium-browser-logo-icon-wave-surf-new> [ from 红梅 ]
* [ 最近程序员频繁被抓，如何避免面向监狱编程！？] <https://juejin.im/post/5db64bc7f265da4d0c1747d3> [ from 文玲 ]
* [ OpenJS 基金会推出两个 Node.js 证书，只要通过考试就能拿到。以后，JavaScript 开发也有考证了。] <https://openjsf.org/blog/2019/10/22/openjs-foundation-launches-new-professional-certification-program-to-support-the-future-of-node-js-development/> [ from 建中 ]

## 191020-191026

`本周轮值主编`: 赵文玲 `下周轮值主编`: 樊晓朋

> 干货
* [ 191029 ] 你能实现多少种水平垂直居中的布局（定宽高和不定宽高）<https://juejin.im/post/5db706d5f265da4d31073959> [ from 正杰 ]
* [ 191028 ] 200行代码实现前端无痕埋点 <https://juejin.im/post/5db5cf2e6fb9a02074738b25> [ from 鹏程 ]
* [ 190428 ] Git操作中crlf和lf冲突问题 <https://www.cnblogs.com/dahe1989/archive/2019/04/28/10784581.html> [ from 红梅 ]
* [ 191027 ] 对document.readyState和DOMContentLoaded的新认识: <https://www.zhangxinxu.com/wordpress/2019/10/document-readystate/?from=timeline&isappinstalled=0> [ from 海萍 ]
   * document.readyState有3种状态loading， interactive和complete
   * loading状态时，绑定DOMContentLoaded事件才能触发
   * js入口文件放到body底部时，不需要再$(document).ready()
* [ 190114 ] 常见的CSS图形绘制合集 <https://www.zhangxinxu.com/wordpress/2019/01/pure-css-shapes/> [ from 海萍 ]
* [ 191013 ] 耐人寻味的CSS属性white-space <https://segmentfault.com/a/1190000020669781> [ from 子哲 ]
*

> 新鲜货
* [ 191028 ] 了解JavaScript新特性：Optional Chaining <https://mp.weixin.qq.com/s/PC1C8ZcpgbSfzNL1N-Z10A> [ from 思源 ]
* [ 191022 ] Node v13.0.0 <https://nodejs.org/en/blog/release/v13.0.0/> [ from 学聪 ]
* [ 191101 ] [译] Node.js 12 新特性将颠覆 AI、物联网等更多惊人领域 <https://juejin.im/post/5dbb8d70f265da4d12067a3e> [ from 文玲 ]
    * 多线程趋向稳定
    * 支持ES模块
    * 装载新版V8引擎
    * 支持HTTP/2

> 手册
* [ 160613 ] 正则表达式前端使用手册 <http://louiszhai.github.io/2016/06/13/regexp/> [ from 晓朋 ]

> 工具
* [ 191022 ] Electron 7.0 Released <https://electronjs.org/blog/electron-7-0> [ from 红梅 ]
* [ 180201 ] immer.js 简介及源码简析：更简单，更快速的创建不可变数据类型 <https://zhangzhao.name/posts/immer-immutable/> [ from 明成 ]

> 体系建设
* [ 191016 ] 漫谈 Typescript 研发体系建设 <https://mp.weixin.qq.com/s/qcvh9M6xhSm3I8jalxxfVg> [ from 陈荣 ]

> 资讯
* [ 191101 ] 卸载、抵制Notepad++ <https://mp.weixin.qq.com/s/P9XR5LZigDkoZYr8Pgqn0Q> [ from 建中 ]

> 其他
* [ 191101 ] QQ红包 | 趣味新玩法是怎么设计的？<https://isux.tencent.com/articles/qq-red-envelope.html> [ from 良辰 ]
    从'一个顶俩'说起，介绍qq红包的新设计与优化
* [ 170406 ] 大数据行业目前的问题和四大盈利模式 <https://www.jianshu.com/p/7ea590f0ee1e> [ from 君毅 ]
    * 数据源获取困难，数据归属和隐私悖论，无直接商业模式，变现困难等问题是摆在大数据行业前面的难题
