# 技术快报

> 业界技术跟进，不限于前端技术，按时间逆序梳理，每周一份，[轮值主编制度参考](./editors.md)


## 1900902-190907

`本周轮值主编`: 陈荣 `下周轮值主编`: 陈明成

> CSS
* [无外链的css开发策略](https://www.zhangxinxu.com/wordpress/2019/08/css-no-external-link/) [from 思源]

> 工具
* [重磅！滴滴跨端框架Chameleon 1.0正式发布](https://juejin.im/post/5d70e76be51d4561fc620ab6) [from 文玲]
* [Video Renderer：高性能移动 Web 端视频编辑器](https://www.infoq.cn/article/2IPZUDVo6JViltmiPfrb) [from 明成]
* [ 19906 ] 一个显示卡通、手绘效果的图标工具 [from 红梅]
    [GitHub 仓库](https://github.com/timqian/chart.xkcd)
    [官方网站](https://timqian.com/chart.xkcd/)
 
* [19906 快速生成波浪形svg工具](https://getwaves.io/) [from 红梅]

* [ 190830 珍藏多年的 Git 问题和操作清单 ](https://mp.weixin.qq.com/s/KD8UeunsBit4jOxPZ02yQQ)
    * 较全面，适合作为随时查看的清单来使用 [from 君毅]
 
* [ 190903 珍藏多年的 Git 问题和操作清单 ](https://dev.to/gajus/my-favorite-css-hack-32g3) [from 君毅]
    * This tip takes a few extra steps, however, and helps you get a better overview, particularly with nested elements

> 干货
* [ 190907 dynamic import — 按需加载](https://github.com/CodeLittlePrince/blog/issues/3)
* [京东 PC 首页 2019 改版前端总结](https://juejin.im/post/5d71c98a6fb9a06ae8362f52)
    * 引入强类型校验
    * 升级资源构建方案
    * 接入自动化测试
    * 完善监控体系
    * 优化页面加载体验：骨架屏
    * 优化信息无障碍体验

## 190826-190831

`本周轮值主编`: 翟思源 `下周轮值主编`: 陈荣  

> 技术干货  

* [ 190830 ] A React component for visualizing profiling data.
<https://react-flame-graph.now.sh/> [ from 建中 ]
* [ 190830 ] Webpack优化——将你的构建效率提速翻倍 <https://mp.weixin.qq.com/s/WmTWXoYn_CvD60nd0_biuQ> [ from 思源 ]
* [ 190830 ] 21个React性能优化技巧 <https://mp.weixin.qq.com/s/iZqV6GAi5zyX5P48hR4VLA> [ from 思源 ]

> CSS  

* [ 190828 ]  66个非常实用的CSS开发小技巧<https://mp.weixin.qq.com/s/ebA7f-3tPkmhEv6KVKlzUQ> [ from 思源 ]
* [ 190830 ] 灵活运用CSS开发技巧 <https://juejin.im/post/5d4d0ec651882549594e7293> [ from 文玲 ]

> 资讯  

* [ 190830 ] 规范使用地图，一点都不能错！2019版标准地图已上线<https://mp.weixin.qq.com/s/91Os-W23Yk3JQce8EfSKzw> [ from 永录 ]

## 190819-190824

`本周轮值主编`: 万子哲 `下周轮值主编`: 翟思源

> 技术干货

* [ 190820 ] Win下最爱效率神器:AutoHotKey <https://www.jeffjade.com/2016/03/11/2016-03-11-autohotkey/> [ from 陈荣 ]

* [ 190823 ]  javascript 的 api 设计原则 <https://mp.weixin.qq.com/s/JGf3fG0AQdwuWJHufioItw> [ from 思源 ]

* [ 190808 ]缓存世界中的三大问题及解决方案 <https://mp.weixin.qq.com/s/uJJKcJsdokDR33pzgGsafw>[ from 君毅 ]
    * 缓存穿透
    * 缓存击穿
    * 缓存雪崩

* [ 180603 ]win10 安装 oh my zsh 和 window git bash 设置别名提高效率<https://www.jianshu.com/p/97f33b7fac80> [ from 君毅 ]

* [ 190823 ]用于3D设计和动画制作的JavaScript库Zdog<https://mp.weixin.qq.com/s/XobCJLTVUXrckGuRBIZjWA>[ from 明成 ]

* [ 190822 ] 记一次webpack打包导致的事故 <https://juejin.im/post/5d5d407cf265da03f66dc53b>[ from 文玲 ]
    * webpack --profile --json > compilation-stat.json
    * package-lock.json 冲突如何处理 <https://www.jianshu.com/p/6ae02901e90f>

* [ 190823 ] 5个 JS 解构有趣的用途 <https://juejin.im/post/5d5f29dde51d456216553519>[ from 文玲 ]
    * 交换变量, [a, b] = [b, a]
    * 访问数组中元素, const [firstColor = 'white'] = [];
    * 不可变操作, const [, ...fooNumbers] = [1,2,3];
    * 解构 iterables, 通过定义`Symbol.iterator`方法来实现可迭代协议
    * 解构动态属性

* [ 190821 ] tapable, Just a little module for plugins. <https://github.com/webpack/tapable>[ from 文玲 ]
        const {
            SyncHook,
            SyncBailHook,
            SyncWaterfallHook,
            SyncLoopHook,
            AsyncParallelHook,
            AsyncParallelBailHook,
            AsyncSeriesHook,
            AsyncSeriesBailHook,
            AsyncSeriesWaterfallHook
        } = require("tapable");

* [ 190823 ] Why I Never Use Shallow Rendering   <https://kentcdodds.com/blog/why-i-never-use-shallow-rendering>[ from 婉如 ]

> CSS3  
    
* [ 190821 ] oasis 3d <https://zhuanlan.zhihu.com/p/79026457?utm_source=wechat_session&utm_medium=social&utm_oi=27607278026752&wechatShare=1&s_r=1&s_s_i=wvsIpVa7xuInTv3Oxxe%2BltBUm64%2FGBIw%2BCkal%2By0fos%3D&from=singlemessage&isappinstalled=0> [ from 民哥 ]

* [ 190823 ] 腾讯css3 ui库 <http://css3lib.alloyteam.com/#animation/CircleHoverEffects> [ from 子哲 ]

* [ 190823 ] 3D按钮 <http://fe:8020/wanzizhe/book/CSS33D/button.html> [ from 子哲 ]

* [ 190823 ] 分层悬浮 <http://fe:8020/wanzizhe/book/CSS33D/hierarchy-suspension.html> [ from 子哲 ]

* [ 140610 ]Everything You Need to Know About the CSS will-change Property<https://dev.opera.com/articles/css-will-change-property/> [ from 君毅 ]
    * The will-change property allows you to inform the browser ahead of time of what kinds of changes you are likely to make to an element, so that it can set up the appropriate optimizations before they’re needed

> 工具 

* [ 190823 ] 基于深度学习的代码补全工具号称支持所有语言 <https://tabnine.com> [ from 建中 ]

## 190812-190817

`本周轮值主编`: 郝海亮 `下周轮值主编`: 万子哲

> 干货

* [ 190816 ] JavaScript中的development模式怎么实现 <https://juejin.im/post/5d56a688f265da039a2883c7> [ from 文玲 ]
    * 本文讲述了使用`process.env.NODE_ENV`>来设置`development`和`production`两种模式的历史原委。
* [ 190816 ] 数组 reduce 一看一整天 <https://juejin.im/post/5d568e23f265da0390052a3d> [ from 文玲 ]
    * JS数组 reduce 相关的方法，原理，应用，还有 polyfill实现的 reduce。
* [ 190816 ] 如何把css'content的操作跟价值发挥到最大 <https://juejin.im/post/5d5638fff265da03cd0a7a51> [ from 文玲 ]
    * content属性需要与before及after伪元>素配合使用，作用是可以定义伪元素所显示的内容，本文主要列举content的可选值及实用的案例与技巧。
* [ 190813 ] 5 Tips to Help You Avoid React Hooks Pitfalls <https://kentcdodds.com/blog/react-hooks-pitfalls> [ from 君毅 ]
    * Pitfall 1: Starting without a good foundation;
    * Pitfall 2: Not using (or ignoring) the ESLint plugin;
    * Pitfall 3: Thinking in Lifecycles;
    * Pitfall 4: Overthinking performance;
    * Pitfall 5: Overthinking the testing of hooks.
* [ 190813 ] Testing Implementation Details <https://kentcdodds.com/blog/testing-implementation-details> [ from 君毅 ]
    * Implementation details are things which users of your code will not typically use, see, or even know about.
    * It can break when you refactor application code
    * It may not fail when you break application code

> CSS  
    
* [ 190816 ] 你所不知道的 CSS 负值技巧与细节 <https://mp.weixin.qq.com/s/YEDpQX0JVzGELXMp4xbrXQ> [ from 思源 ]
* [ 190815 ] 让CSS flex布局最后一行列表左对齐的N种方法 <https://www.zhangxinxu.com/wordpress/2019/08/css-flex-last-align/> [ from 海亮 ]
    * grid布局特点
    	1. 列数不固定
    	2. 子项宽度不固定
    	3. 免计算
    
> 项目

* [ 190816 ] 升级指南 <http://172.17.10.41:8020/fanxiaopeng/update-version.md.html> [ from 晓朋 ]

> 资源

* [190816] 技术相关的开源电子书推荐 <https://www.zhihu.com/question/38836382/answer/79794319?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io> [ from 建中 ]

> 新鲜货

* [ 190814 ] 10分钟，用TensorFlow.js库，训练一个没有感情的“剪刀石头布”识别器 <https://mp.weixin.qq.com/s/ypJexBvbPPyaQ7JvvTKp2g> [ from 明成 ]

> 工具

* [ 190816 ] Color Thief—颜色提取器 <http://172.17.10.41:8020/zhaojunyi/demo/color-thief/color-thief.md.html> [ from 君毅 ]
* [ 190816 ] 重磅！前端也有AI代码补全工具了，这款撸码利器让写前端的程序员们沸腾了！ <https://mp.weixin.qq.com/s/a-Wdmt60VKWql9Q8R9H55Q> [ from 海萍 ]

## 190805-190810

`本周轮值主编`: 刘红梅 `下周轮值主编`: 郝海亮

> 干货
 
* [ 190809 ] 前端新框架 Svelte is a frontend framewor <https://daveceddia.com/svelte-intro/>，github: <https://github.com/sveltejs/svelte>  [ from 红梅 ]
    * 与React、Vue.js或Angular 类似，但又有很多不同
    * 区别1  运行快，只更新发生改变的dom，没用用到虚拟dom，减少了构建虚拟dom树的时间，但又精确的知道哪些dom做了修改；另外组件代码量少
    * 区别2 生成的包大小更小
    * 可能对于大型的应用，优势更加明显
        * Svelte不仅是一个框架，还是一个编译器
        * Reactive 响应式编程
        * 事件标记方式 Event Handlers Start With ‘on:’ on: – on:click, on:mousemove, on:dblclick, and so on 
        * Svelte 也可以编译  CSS，可以在常规的style中写旧的css，另外，也会变异组件范围内的css类名为唯一，不会污染全局样式
        * 动态类  Dynamic Classes with Svelte
        * Detects Unused CSS
        * 其他的一些shorthand的写法
* [ 190809 ] Chrome架构：仅仅打开了1个页面，为什么有4个进程? <https://mp.weixin.qq.com/s/vPYrLEq81goVCHlBubDa1w>  [ from 文玲 ]
    现代chrome浏览器进程：
    * 浏览器进程：负责界面显示、用户交互、子进程管理，同时提供存储等功能
    * 渲染进程：将 HTML、CSS 和 JavaScript 转换为用户可以与之交互的网页，排版引擎 Blink 和 JavaScript 引擎 V8 都是运行在该进程中
    * GPU进程：3D css渲染，UI绘制
    * 网络进程：负责页面的网络资源加载
    * 插件进程：负责插件的运行
* [ 190809 ] 可靠React组件设计的7个准则之封装 <https://juejin.im/post/5d4c329e51882511ed7c203f>  [ from 文玲 ]
    组件的实例和状态对象是封装在组件内部的实现细节。将状态管理的父组件实例传递给子组件会破坏封装。
* [ 190809 ] 纯CSS实现聊天功能 <https://zhuanlan.zhihu.com/p/66442840> <https://github.com/kkuchta/css-only-chat>  [ from 海亮 ]
      * 事件监听使用: .classname:active 伪类来捕获
      * 发送请求: background-image指定某个url, 规则被使用到才会发送请求
      * 实时消息展示
        基于 iframe 的长连接流（stream）模式
        append内容时，显示当前最新的，添加样式隐藏之前的
* [ 190808 ] 关于华为方舟编译器，你想知道的都在这里！ <https://zhuanlan.zhihu.com/p/77108133> [ from 良辰 ]
* [ 190807 ] Learn Regex the easy way  https://github.com/ziishaned/learn-regex  [from 永禄]
    * 正则表达式基础知识，比较全面
* [ 190806 ] The :empty Selector  <https://dev.to/samanthaming/css-empty-selector-b6f> [ from 红梅 ]
     * How to use the :empty selector to style elements with no children or content.
* [ 190806 ] Web Components 入门实例教程 <http://www.ruanyifeng.com/blog/2019/08/web_components.html> [ from 明成 ]
* [ 190801 ] The Ultimate Vim Distribution <http://vim.spf13.com/#>, github: <https://github.com/spf13/spf13-vim>  <iframe src="http://258i.com/gbtn.html?user=spf13&repo=spf13-vim&type=star&count=true" frameborder="0" scrolling="0" width="105px" height="20px"></iframe> [ from 君毅 ]
    * spf13-vim is a distribution of vim plugins and resources for Vim, GVim and MacVim
* [ 190717 ] html指令式实现tooltip文字提示，纯css实现  <https://juejin.im/post/5d2e82976fb9a07ef4443b30>  [ from 婉如 ]

> 新鲜货

* [ 190809 ] 实现react代码在线编辑预览 <https://github.com/uiwjs/react-code-preview> [from 思源]

> 工具类库：

* [ 190809 ] 客户端保存文件的解决方案  <https://github.com/eligrey/FileSaver.js>  [from 红梅]
    * 客户端保存文件的解决方案
    * 大文件或者内存不够时使用StreamSaver.js 的方案
    * 当服务端返回的内容 Content-Disposition attachment response header，建议还是用浏览器文件下载的方式
    * 多浏览器的支持：依赖Blob.js 

> 资讯

* [ 190809 ] 尤雨溪在vueconf的演讲  <https://www.bilibili.com/video/av56093550/>  [from 永禄]
    * 发展现状 chrome devTools插件 90w周活跃用户，对比react: 160w
    * 全球化的影响力: 世界各地的线下聚会、世界各地的Vue主题会议
    * 良好的用户反馈
    * 使用的公司遍布全球
    * 团队： 20人左右的活跃团队，独立运营：资金主要来自赞助
    * 3.0的进展
        * 目标：更小、更快、加强TypeScript支持、加强API设计的一致性、提高自身可维护性、开放更多底层功能
        * 更快和TypeScript的支持是重点
        * Vdom的重构（2.6.10版本 平均每次更新dom 36ms -> 5.44ms）
        * 废弃掉Class Api, 采用Function-based API
* [ 190802 ] 效果惊人！中科院、百度研究院等联合提出UGAN，生成图片难以溯源  <https://mp.weixin.qq.com/s/DLoFJmr5H04R8cLixuCObA> [from 红梅]
    * 新的模型 UGAN 模型，使得新生成的图片与源图相似性降低，无法追踪
    * 多领域图像转换
* [ 190807 ] 电击、警棍、爆头，被骗去柬埔寨的程序员有多惨？<https://mp.weixin.qq.com/s/HML11GgMZemtf_3mqdyQbA>  [from 思源]

> 技术成长

* [ 190809 ] 职业思考：技术人需要突破的 10 个困局 <https://www.yuque.com/sxc/front/gsvr3x> [from 鹏程]
* [ 190809 ] What every computer science major should know <http://matt.might.net/articles/what-cs-majors-should-know/> [from 建中]

## 190729-190803

`本周轮值主编`: 赵君毅 `下周轮值主编`: 刘红梅

> 技巧

* [ 190729 ] 10 个迅速提升你 Git 水平的提示 <https://www.oschina.net/translate/10-tips-git-next-level?cmp&p=1> [ from 君毅 ]
    * git add -p [file_name]：暂存文件的部分改动，对一个文件进行多次修改并想把分别提交时使用
    * git rebase -i HEAD~[number_of_commits]：压缩多个Commit，提交代码进行代码审查时或者创建一次pull request时使用
* [ 190725 ] 如何优雅地取数值的整数和小数部分 <https://github.com/akira-cn/FE_You_dont_know/issues/5> [ from 君毅 ]
    * JavaScript的取模运算%并不限于整数运算，可以对浮点数取模
            console.log(3.75 % 1); // 0.75
            console.log(-3.75 % 1); // -0.75
* [ 190324 ] CSS :focus-visible伪类让我感动哭了 <https://www.zhangxinxu.com/wordpress/2019/03/css-focus-visible/> [ from 君毅 ]
    * :focus-visible所表示的聚焦是浏览器认为键盘访问触发的元素聚焦
* [ 190801 ] 处理 JS 中 undefined 的 7 个技巧 <https://juejin.im/post/5d422cf26fb9a06b1b199f32> [ from 文玲 ]

    undefined的存在是JS的允许性质的结果，它允许使用：
    * 未初始化的变量
    * 不存在的对象属性或方法
    * 访问越界索引的数组元素
    * 不返回任何结果的函数的调用结果

    减少未初始化变量的使用
    * 变量生命周期变短并接近其使用的位置
    * 尽可能为变量分配初始值
    * 多敷衍 const 和 let
    * 使用默认值来表示无关紧要的函数参数
    * 验证属性是否存在或使用默认属性填充不安全对象
    * 避免使用稀疏数组

> 干货

* [190802] 数据结构和算法在前端领域的应用(进阶)  <https://juejin.im/post/5d4289046fb9a06ad229ad21> [ from 红梅 ]
    * 算法在前端领域无处不在
    * 好的数据结构和算法提升性能，实现更优雅
    * 实际业务场景举例：权限系统、状态机
* [ 190605 ] 如何提升JSON。stringify 的性能 <https://zhuanlan.zhihu.com/p/68183339> [ from 君毅 ]
    * 开发者定义 Object 的 JSON scheme
    * 根据 scheme 生成对应的模版方法，模版方法里会对属性与值进行字符串拼接（显然，属性访问与字符串拼接的效率要高多了）
    * 最后开发者调用返回的方法来 stringify Object 即可
* [190802] 离线探索 <http://www.alloyteam.com/2019/07/web-applications-offline/> [ from 建中 ]
    * Application Cache 已经废弃
    * service-worker 类似于拦截器，精细化，https下运行，UIWebView不支持
    * redux-offine 本地储存数据无法方便的和其他非 redux 逻辑共享
    * redux + indexDB 通用 DB 底层操作库
* [ 190713 ] 在阿里一年，我颠覆了曾经坚信不疑的技术思维 <https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655825436&idx=1&sn=25becac0f083ef9fac254807ae555402> [ from 君毅 ]
    * 对于一个程序开发人员非常实用的指南性文章，经常看看养成习惯大有益处
* [ 190802 ] 照片飞入 <http://172.17.10.41:8020/wanzizhe/book/CSS33D/fly-picture.html> [ from 子哲 ]
    * 24张小图片从左上角一个一个飞入，每一个呈现不同的随机旋转角度，点击每一张小图片会展现相应小图片的大图，可以进行左右图片的切换，切换图片的时候切换形式是马赛克的渐变，再次点击大图又会回到原来24张小图片打散的状态
* [ 190731 ] 49 张 GIF 图中学习 49 个 CSS 知识点 <https://mp.weixin.qq.com/s/vJw-dkuULT4O_D28MdCa-w> [ from 思源 ]
    * 借助49张 GIF 一目了然的学习49个 CSS 知识点
* [ 190726 ] 前端协作涉及到的一整套规范 <https://juejin.im/post/5d3a7134f265da1b5d57f1ed> [ from 晓鹏 ]
    * 工作流规范
    * 技术栈规范
    * 浏览器兼容规范
    * 项目组织规范
    * 编码规范
    * 文档规范
    * 测试规范
    * 异常处理，监控规范
    * 前后端协作规范
    * 培训/知识管理/技术沉淀

> 资讯

* [ 190724 ] 62岁程序员锒铛入狱，因植入漏洞重复获取修理费用 <https://www.infoq.cn/article/pYPTwe*3LO7hPW99PyV7> [ from 君毅 ]
    * 一位西门子公司的合同工十年前在给西门子写的电子表格中植入了逻辑炸弹，它会在特定日期之后导致电子表格崩溃，于是西门子就必须再次雇佣该名合同工进行修复，每次都需要重新支付修复费用，持续时间近 3 年
* [ 190730 ] What's New In DevTools (Chrome 77) <https://developers.google.com/web/updates/2019/07/devtools> [ from 君毅 ]
    * Right-click a node in the DOM Tree to copy that DOM node's CSS to your clipboard
    * DevTools can now help developer detect layout shifting
* [ 190802 ] Ant Design 4.0 进行时！ <https://www.yuque.com/ant-design/ant-design/antd4-in-progress#c74ade0c> [ from 君毅 ]
    * 使用最新版本 React API
    * 停止 IE9/10 支持
    * 虚拟滚动
    * 改进无障碍体验
* [ 190712 ] Malicious code in the purescript npm installer <http://topurl.cn/1K8> [ from 永禄 ]
    * 记录了purescript 中引入的流氓代码以及发现解决历程

> 新鲜货

* [ 190801 ] Color Thief <https://lokeshdhakar.com/projects/color-thief/>, github: <https://github.com/lokesh/color-thief> [ from 君毅 ] <iframe src="http://258i.com/gbtn.html?user=lokesh&repo=color-thief&type=star&count=true" frameborder="0" scrolling="0" width="105px" height="20px"></iframe>
    * Grab the color palette from an image. Uses Javascript and the canvas tag to make it happen
* [ 190802 ] Frappe Charts <https://frappe.io/charts>, github: <https://github.com/frappe/charts> [ from 君毅 ] <iframe src="http://258i.com/gbtn.html?user=frappe&repo=charts&type=star&count=true" frameborder="0" scrolling="0" width="105px" height="20px"></iframe>
    * Modern, Open Source SVG Charts. GitHub-inspired simple and modern SVG charts for the web with zero dependencies

> 工具

* [ 190802 ] baidu-netdisk-downloaderx—百度云网盘下载工具 github: <https://github.com/b3log/baidu-netdisk-downloaderx> [ from 思源 ] <iframe src="http://258i.com/gbtn.html?user=b3log&repo=baidu-netdisk-downloaderx&type=star&count=true" frameborder="0" scrolling="0" width="105px" height="20px"></iframe>
    * 一款图形界面的百度网盘不限速下载器，支持 Windows、Linux 和 Mac

> 开心一刻

* [ 190727 ] 程序员是如何面对生产环境中的问题的…… <https://mp.weixin.qq.com/s/zXRcm-tTc3t4CvnyOAZPCw> [ from 子哲 ]

## 190722-190727

`本周轮值主编`: 荣婉如 `下周轮值主编`: 赵君毅

> 干货

* [ 190709 ] 前端 100 问：能搞懂 80% 的请把简历给我 <https://juejin.im/post/5d23e750f265da1b855c7bbe> [ from 聂正杰 ]
* [ 190724 ] 关于 Babel 你必须知道的 <https://mp.weixin.qq.com/s/1OyBkl5NnFO1q86L7GjQwg> [ from 思源 ]
* [ 190711 ]Lodash 严重安全漏洞背后 你不得不知道的 JavaScript 知识：<https://zhuanlan.zhihu.com/p/73186974> [ from 君毅 ]
    * 介绍了原型污染以及避免原型污染的相关知识
* [ 190620 ] 全网最全 Flutter 与 React Native 深入对比分析 <https://juejin.im/post/5d0bac156fb9a07ec56e7f15> [ from 荣婉如 ]
* [ 190725 ] 浏览器去广告正确姿势 <https://juejin.im/post/5d39005451882557af272505> [ from 荣婉如 ]
    * 浏览器插件——Greasemonkey，简称GM，中文俗称为“油猴”，支持Firefox和Chrome浏览器
* [ 190725 ] 领域驱动设计在前端中的应用 <https://juejin.im/post/5d3926176fb9a07ef161c719>
    * 垃圾桶现象
    * 前端开发面临的困难
    * 领域驱动设计理念及实践建议   

> 深度

* [190725] [源码解析React Hook构建过程：没有设计就是最好的设计](https://mp.weixin.qq.com/s/968ukIjEhhEOeLD5SQoKaw)

    1. 从 React Hooks 源码入手，阐述 Hooks 的设计思想

        * 如何在函数组件中使用状态：
            useState 的实现： 借助闭包、两个单向链表（单次 hook 的 update 链表、组件的 hook 调用链表）、透传 dispatch 函数;

        * 跳出渲染生命周期技术思维方式，不再关心渲染本身:
        生命周期的问题：
            a. 同一个副作用的创建和清理逻辑分散在多个不同的地方，对于新编写代码还是要阅读维护代码都带来成本。(解决方案：tunk)
            b. 有些副作用可能要再多个地方写多份。(解决方案：封装逻辑)

    2. useEffect 的实现：和 useState 基本相似，在mount时创建一个 hook 对象，新建一个 effectQueue，以单向链表的方式存储每一个 effect，将 effectQueue 绑定在 fiberNode 上，并在完成渲染之后依次执行该队列中存储的 effect 函数。

        useEffect 小结：

         a. 执行时机相当于componentDidMount和componentDidUpdate，有 return 就相当于加了componentWillUnmount。
         b. 主要用来解决代码中的副作用，提供了更优雅的写法。
         c. 多个 effect 通过一个单向循环链表来存储，执行顺序是按照书写顺序依次执行。
         d. deps 参数是通过循环浅比较的方式来判断和上一次依赖值是否完全相同，如果有一个不同，就重新执行一遍 Effect，如果相同，就跳过本次 Effect 的执行。
         e. 每一次组件渲染，都会完整地执行一遍清除、创建 effect。如果有 return 一个清除函数的话。
         f. 清除函数会在创建函数之前执行。

    3. 更细粒度，更优雅的复用

        1. mixins 不多说了，侵入性太强；
        2. hoc 的缺点是会造成组件嵌套地狱，分不清 props 来源，而且无法实现更加细粒度的逻辑和状态复用；
        3. hooks 组件复用，以及更细粒度的状态逻辑复用--状态逻辑层面的复用为组件复用带来了一种全新的能力，这完全有赖于React Hook基于Function的组件设计，一切皆为函数调用。并且，Function Component也并不排斥HOC，你仍然可以使用熟悉的方法来提供更高阶的能力，只是现在，你的手中拥有了另外一种武器。

     
> 开源

* form-create V2 <https://github.com/xaboy/form-create> [ from 荣婉如 ]
    * form-create 是一个可以通过 JSON 生成具有动态渲染、数据收集、验证和提交功能的表单生成器。并且支持生成任何 Vue 组件。结合内置17种常用表单组件和自定义组件，再复杂的表单都可以轻松搞定
* pc-chat 野火IM解决方案 <https://github.com/wildfirechat/pc-chat> [ from 荣婉如 ]
    * 一套跨平台开源的即时通讯解决方案，能够更加容易地赋予客户IM能力，使客户可以快速的在自有产品上添加聊天功能。使用野火可以替代云通讯产品或减少自研IM的工作量。降低客户使用IM的成本和难度。
* [ 190715 ] 为什么 90% 的开源文化都是失败的？<https://www.infoq.cn/article/NKH5j_Jbe82TT6e7XBwd> `红帽`关于`开源开放`的理解
    * 两个小例子：
        * 两年时间更换logo，作为开放式组织需要客户、合作伙伴、员工共同参与、提供意见
        * 福岛核事故，通过网络快速做出侦测设备找到安全地方
    * `开源`拯救创业公司，使得创业公司能够在开源基础上进行创新
    * 开源开发理念: 勤发布、早发布；Best Idea Wins;
    * 开源社区管理范式：先配置、再赋能、最后参与
    * 红帽开放组织核心原则：协作、透明度
    * 开放领导力思维：参与、包容，即让大家都能参与，并能充分表达意见


> 课程

* [ 190726 ] 你可以不在 BAT，但大厂的眼界不能没有 <https://0x9.me/yZ9si> [ from 文玲 ]

> 资讯

* [ 190726 ] why-plants-dont-die-from-cancer，切尔诺贝利动植物焕发生机 <https://www.pbs.org/newshour/science/why-plants-dont-die-from-cancer> [ from 建中 ]

> 技术

* [190719] HTML静态页面原型交付工具“魔卡” <https://www.zhangxinxu.com/wordpress/2019/07/html-mockup/> [ from 鹏程 ]
    * “魔卡”是个Node.js小工具，开启一些动态特性，帮助前端人员以超高质量超高效率完成高保真静态原型页面，纯原生，无任何安装包依赖，很轻量。
* [190121] 前端工程师身份认知 <https://css-tricks.com/the-great-divide/> [ from 鹏程 ]
    * `前端`工程师分歧，应该分为UX工程师和JavaScript工程师，期望不同要求应也不同
    * 郑重对待`全栈工程师`一词
* 用手控制3D物体 <https://dev.to/teamxenox/javascript-quickies-controlling-3d-objects-with-hands-498n> [ from 明成 ]
    * github:  https://github.com/sarthology/thehandtrick


> 实践

* [ 190726 ] 动态收据 <http://172.17.10.41:8020/wanzizhe/book/CSS33D/fold-receipt.html> [ from 子哲 ]
* [ 190726 ] 折叠照片 <http://172.17.10.41:8020/wanzizhe/book/CSS33D/fold-picture.html> [ from 子哲 ]
* [ 190726 ] CSS3 Patterns Gallery <https://leaverou.github.io/css3patterns/#> [ from 子哲 ]


## 190715-190720

`本周轮值主编`: 崔鹏程 `下周轮值主编`: 荣婉如

* [ 190719 ] web动画系列教程 [ from 崔鹏程 ]
    * 第三期 死亡之舞 <https://juejin.im/post/5d26b1fde51d4577583ddd54>
    * 第四期 密室逃脱<https://juejin.im/post/5d30876bf265da1b6836f450>
    * 你用的那些CSS转场动画可以换一换了 <https://www.zhangxinxu.com/wordpress/2019/05/css-transfer-animation/>
* 介绍下 npm 模块安装机制 <https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/22> [ from 崔鹏程 ]
* 技术栈中的爱马仕？Facebook发布全新JavaScript引擎：Hermes <https://www.jianshu.com/p/206ed11a6b5c> [ from 崔鹏程 ]

    Facebook在Chain React 2019 大会上发布的一个崭新JavaScript引擎
    已开源 & 用于移动端React Native应用的集成

* 2019年6月Github上最热门的JavaScript开源项目！ <https://mp.weixin.qq.com/s/qbfjgc4dWdIo4TkheUw-Hw> [ from 子哲 ]

> 深阅读

* 【干货】Chrome插件(扩展)开发全攻略 <https://www.cnblogs.com/liuxianan/p/chrome-plugin-develop.html> [ from 崔鹏程 ]
* 阿里巴巴的技术专家，是如何画好架构图的？<https://zhuanlan.zhihu.com/p/64881017> [ from 学聪 ]
* 技术路线：前端开发已进入深水区 <https://www.yuque.com/sxc/front/kvokg4> [ from 崔鹏程 ]
* 蚂蚁金服的前端框架和工程化实践 <https://github.com/sorrycc/blog/issues/85> [ from 崔鹏程 ]

> 黑科技

* [ 190627 ] GIAC2019 演讲精选 | 面向未来的黑科技——UI2CODE闲鱼基于图片生成跨端代码 <https://mp.weixin.qq.com/s/hajHNqsy708vfHk1wYUN_w> [ from 文玲 ]
    * 基于图片作为输入源，非sketch或photoshop文件；
    * 目前让机器来解放开发链路的最前面一段，后面在一些弱交互、强展示的部分，从偏确定性的需求实现中解放人力；

> 开源

* [ 190718 ] Chrome 74 发布：可开启原生延迟加载特性 <https://www.infoq.cn/article/SfF-xzswsdrfhAZNAj5G> [ from 文玲 ]
    * img 和 iframe 标签使用loading属性控制和影响默认延迟加载行为
        * lazy：表示这个元素适合延迟加载。
        * eager：表示这个元素不适合延迟加载，需要马上加载。
        * auto：让浏览器来决定是否需要延迟加载。当 loading 属性设置为 auto 时，相当于未设置该属性。
    * lazySizes，跨平台支持延迟加载图片、iframes、scripts <https://afarkas.github.io/lazysizes/index.html>

* [ 190715 ] 轻量可嵌入的 QuickJS 引擎重磅开源，它会是下一个 V8 吗？<https://www.infoq.cn/article/Qzh19YqpqFoSS6_SOlV9>  [ from 文玲 ]
在 MIT 许可下发布的一个轻量可嵌入的 JavaScript 引擎，支持最新的 ES2019 语言规范，特点：
    * 小巧且易于嵌入，无外部依赖
    * 具有极低启动时间的快速解释器
    * 支持ES2019
    * 可以将 Javascript 源编译为没有外部依赖的可执行文件
    * 使用引用计数（以减少内存使用并具有确定性行为）的垃圾收集与循环删除。
    * 数学扩展：BigInt，BigFloat，运算符重载，bigint 模式，数学模式
    * 在 Javascript 中实现的具有上下文着色的命令行解释器。
    * 带有 C 库包装库构建的内置标准库。


## 190708-190713

`本周轮值主编`: 籍学聪 `下周轮值主编`: 崔鹏程

* Linux上，最常用的一批命令解析（10年精选）：https://mp.weixin.qq.com/s/9RbTGQ4k4s92mrSf2xJ5TQ [ from 赵君毅 ]
    * 本文针对对Linux不是很熟悉的同学，介绍了精选的一批必须要搞懂的命令集合。不会教我们具体的用法，只是个引导篇，力求简洁
* 图谱2D渲染引擎四叉树升级介绍：http://172.17.10.41:8020/zhaojunyi/SophonWeb/graph-performance/quad-tree-upgrade.md.html [ from 赵君毅 ]
    * 介绍了2D渲染引擎当前四叉树机制以及优化方案
* [ 190712 ] 今日掘金 <http://zy2071.com/Fun/todayJueJin.html?from=groupmessage> [from 思源]
    * 15分钟一次爬取，列出掘金首页前10篇点赞数大于55的文章
* [ 190712 ] Git 屡试不爽的三个急救命令 <https://mp.weixin.qq.com/s/g-sRwRGySFVdQTpgOeSjNg> [from 思源]
* [ 190712 ] 文档实时编辑并且可以得到json格式输出<https://github.com/codex-team/editor.js> [ from 陈容]
* [ 190712 ] 带你走进 WebGL 的随机美学 <https://www.infoq.cn/article/TC5mR*tll4aZXFj2pZlj> [ from 陈明成 ]
    图形噪声，经常用来模拟自然界中的各种纹理材质
    基础噪声算法主要有两类：1. 梯度噪声；2. 细胞噪声
    梯度噪声产生的纹理具有连续性，所以经常用来模拟山脉、云朵等具有连续性的物质
    细胞噪声可以模拟细胞形态、皮革纹理等
    通过对多个不同频率的同类噪声进行运算，产生更为自然的效果
    加上时间 t 维度，形成动态的噪声
> 干货

* [ 190710 ] Google Chrome 工程师：JavaScript 不容错过的八大优化建议 <https://mp.weixin.qq.com/s/WkVj-8ADIinURJEjCNzoDA>
    * 优化js包时，重点关注三大方面
        * 减少下载时间，降低包的大小，打包拆小包
        * 缩短执行时间
        * 避免使用大型内联脚本（因为它们仍然需要在主线程上进行解析和编译）。经验法则：如果一个脚本超过1KB，就不要将其内联（因为当外部脚本
大小超过1KB时，就会触发代码缓存）。
    * v8通过在`worker线程`上进行流式解析和编译js脚本提高js解析/编译速度

> 安全

* [ 190710 ] Lodash库爆出严重安全漏洞，波及400万+项目 <https://mp.weixin.qq.com/s/tfZq2PZylGfMjOp8h8eeTw>

    原型污染漏洞使攻击者能够修改 Web 应用程序的 JavaScript 对象原型。通过构造函数重载的方式，Lodash 库中的函数“defaultsDeep”很有可能会被欺
骗添加或修改 Object.prototype 的属性，最终可能导致 Web 应用程序崩溃或改变其行为，具体取决于受影响的用例。


> 资讯

* [ 190607 ] 谷歌变坏了？Chrome 已成众矢之的 <https://dwz.cn/varwTnnI> 曾经的青铜，如今的王者, Chrome 控制着标准的制定, 现在大多数主流浏览
器都构建在谷歌维护的 Chromium 基础上。

* [ 190712 ] 前端的意义是什么？番外篇，玉伯是如果把Antd整起来的 <https://www.zhihu.com/question/44812950/answer/722902353> [ from 学聪 ]
    一张图让前端在迷茫一点 <https://www.toutiao.com/a1638820995147780>

## 190624-190629

`本周轮值主编`: 樊晓朋 `下周轮值主编`: 籍学聪

> 专题

* [ 190705 ] web动画系列教程 [ from 晓朋 ]

    * 第一期 <https://juejin.im/post/5d14bcc46fb9a07f0052ecdf>
    * 第二期 <https://juejin.im/post/5d1829c3e51d454fbe24a6c7#heading-13>

* [ 190705 ] 100学习Python <https://github.com/jackfrued/Python-100-Days> [ from 思源 ]

> 框架

* [ 190705 ] 现代框架存在的根本原因 <https://mp.weixin.qq.com/s/50rJft1QAVBdghUOZw8iTA> [ from 晓朋 ]

    * 现代javascript框架解决的主要问题是保持UI与状态同步
    * 使用原生 JavaScript 编写复杂、高效而又易于维护的UI界面几乎是不可能的

* [ 190705 ] 精读《怎么用 React Hooks 造轮子》<https://juejin.im/post/5bf20ce6e51d454a324dd0e6> [ from 陈荣 ]

    * 列出了一些 hooks 真实的使用场景，在了解了 hooks 是什么的基础上，再来看看 hooks 可以做什么，以及怎么做。然后你会发现，hooks 真香！😈👿

> 实践

* [ 190704 ] web-worker 可以使用的功能场景 <https://github.com/deebloo/things-you-can-do-in-a-web-worker> [ from 建中 ]
* [ 190705 ] 地域版本拉分支踩坑记录 <http://fe-doc.sophon.com/haohailiang/branchPitRecord.md.html> [ from 海亮 ]
* [ 190705 ] Web安全漏洞文件之文件上传 <https://mp.weixin.qq.com/s/MNdstO9ahpcXp5JTHErBxg> [ from 海亮 ]

    * 可能漏洞场景

        * 文件名
        * HTML和SVG
        * 软链
        * 服务器磁盘

    * 防御方法

        * 对用户传入的文件名在使用的时候尽量进行白名单过滤，可以的话尽量不要使用用户传入文件名，杜绝从文件名上导致的安全漏洞。
        * 对文件内容本身做好格式验证，黑名单或者白名单的方式都可以，不过白名单的方式安全性会更高点。文件格式不能简单的判断文件后缀或者是表单上传时带有的`Content-Type`字段，因为这两个是用户上传内容，都是可被构造的。最好是通过文件头的魔术数字来读取，配合白名单列表就能避免这方面的问题。比较著名的使用魔术数字来判断文件类型的模块是 https://github.com/sindresorhus/file-type，推荐直接使用。
        * 如果允许用户上传 `.svg` 格式图片的话，需要针对 SVG 内容进行 HTML 解析，过滤掉 `<script>`, `<foreignObject>` 等相关标签。当然，使用白名单的话是最好不过的了。这里提供一个比较全的 SVG 合法标签白名单列表。
* [ 20120806 ] High-Performance, Garbage-Collector-Friendly Code：<http://buildnewgames.com/garbage-collector-friendly-code/> [ from 君毅 ]

    * the process of garbage collection can take anywhere from 10ms to 2000ms. The more things it has to check to be cleaned, and the more cleaning it has to do, the longer it will take

* [ 190701 ] JS 中可以提升幸福度的小技巧 <https://mp.weixin.qq.com/s/oOgdbH87ovn1lDLfiSPJcg> [ from 文玲 ]

> 资讯

* [ 190706 ] 能够脱机工作并支持.sketch文件的原生Windows应用程序 <https://icons8.cn/lunacy> [ from 明成 ]

## 190624-190629

`本周轮值主编`: 赵文玲 `下周轮值主编`: 樊晓朋

> 实践

* [ 170204 ] transfrom会引起字体模糊 <https://www.cnblogs.com/milo-wjh/p/6364138.html> [ from 建中 ]
* [ 190628 ] 编写更好的 JavaScript 条件式和匹配条件的技巧 <https://segmentfault.com/a/1190000019576207> [ from 红梅 ]
    * 自判断链接 <https://github.com/tc39/proposal-optional-chaining>
    * 空合并 <https://github.com/tc39/proposal-nullish-coalescing>
* [ 190628 ] 使用 ThreeJS 构建的 3D 力导向图谱组件: [ from 陈荣 ]
    * [3d-force-graph 4K 节点渲染很顺畅](https://vasturiano.github.io/3d-force-graph/example/large-graph/)
    * [3d-force-graph 仓库地址](https://github.com/vasturiano/3d-force-graph)
* [ 190628 ] 分支实践指南 <http://fe:8020/fanxiaopeng/branch-guide/branch-guide.md.html> [ from 晓朋 ]
    * 目前分支存在的一些问题
    * 主版本分支升级时机
* [ 190627 ] CSS优秀起来真没JS什么事 <https://juejin.im/post/5d148f64f265da1bae390ce3> [ from 婉如 ]
* [ 190508 ] 十分钟实现灭霸打响指灰飞烟灭的效果 <https://juejin.im/post/5cd2b57ef265da039f0f292c> [ from 海亮 ]
    * html2canvas可以把网页转化成图片
    * Element.animate()[JS原生API动画接口，试验属性] <https://developer.mozilla.org/zh-CN/docs/Web/API/Element/animate>


> 资讯

* [ 190628 ] 《Web动画周报》第一期 <https://juejin.im/post/5d14bcc46fb9a07f0052ecdf> [ from 婉如 ]
* [ 190622 ] 滴滴小程序框架Mpx发布2.0：可直接转换已有微信小程序 <https://mp.weixin.qq.com/s/1egWKpHBIXuFQ7YKHj3dSg> <https://github.com/didi/mpx> [ from 大民 ]
* [ 190624 ] 微软开源web版代码编辑器——Monaco Editor <https://www.toutiao.com/a6705700615323910663/> [ from 大民 ]

> 深度

* [ 190629 ] CSS 属性选择器的深入挖掘 <https://github.com/chokcoco/iCSS/issues/65> [ from 明成 ]
* [ 190622 ] 漫谈5G时代的云游戏：<https://mp.weixin.qq.com/s/rsQdtyXR2j-Z10OeruFGkA> 实现机制类似于直播，截取服务端游戏换面，启动流服务实现画面实时传输，在保证低延迟的情况下让用户通过一台轻薄的上网本或一个低配的手机，游玩游戏大作成为可能 [ from 君毅 ]
    * github <https://github.com/chunying/gaminganywhere>
* [ 190623 ] 干货分享：蚂蚁金服前端框架和工程化实践 <https://www.infoq.cn/article/CaXvurFIN*DqvW4iEh1H> [ from 大民 ]
    * umi - bigfish
    * 插件体系，全生命周期：编译时、运行时以及编辑时
    * 拳头功能：
        * 资产市场 - 组件、业务组件、区块以及页面模板
        * 微前端
    * 专题研究
        * 路由，按需编译
        * 编译提速
        * 性能优化
        * 补丁方案
        * 编辑器插件
        * 测试
        * 监控体系

* [ 190624 ] 终于有人把中台说清楚了 <https://mp.weixin.qq.com/s/hgmHOGGbAjTdAWqQ9majqA> 所谓的“中台”，并不是阿里巴巴首先提出的词语，从字面意思上理解，中台是基于前台和后台之间。阿里通过多年不懈的努力，在业务的不断催化滋养下，将自己的技术和业务能力沉淀出一套综合能力平台，具备了对于前台业务变化及创新的快速响应能力。阿里人将“中台战略”形象地比喻成陆海空三军立体化协同作战。他们将中台分为6类： [ from 大民 ]
    * 业务中台，提供重用服务，例如用户中心、订单中心之类的开箱即用可重用能力，为战场提供了空军支援能力，随叫随到，威力强大；
    * 数据中台，提供数据分析能力，帮助从数据中学习改进，调整方向，为战场提供了海军支援能力；
    * 算法中台，提供算法能力，帮助提供更加个性化的服务，增强用户体验，为战场提供了陆军支援能力，随机应变，所向披靡；
    * 技术中台，提供自建系统部分的技术支撑能力，帮助解决基础设施，分布式数据库等底层技术问题，为前台特种兵提供了精良的武器装备；
    * 研发中台，提供自建系统部分的管理和技术实践支撑能力，帮助快速搭建项目、管理进度、测试、持续集成、持续交付，是前台特种兵的训练基地；
    * 组织中台，为项目提供投资管理、风险管理、资源调度等，是战场的指挥部，战争的大脑，指挥前线，调度后方。
    中台就是**公共服务平台**。

> 技术成长

* [ 190624 ] 蚂蚁金服玉伯：从前端到体验，如何把格局做大？ <https://www.toutiao.com/a6705943708342157831/> [ from 大民 ]

> 其他

* [ 190622 ] npm已落伍，下一代包管理器Tink正在孵化 <https://mp.weixin.qq.com/s/wDMcKSYUsZDtx9sSzSDyBg> [ from 文玲 ]
    * Tink 特性：`Virtual node_modules`, 运行时包管理器, 不需要物理node模块以及单一全局缓存保存文件; 自动下载依赖项;
    * 新包管理API：获取独立文件取代压缩包; 减少多达 40% 的数据传输需求, 加快安装流程; 懒加载文件、缓存策略; 改进单个存储库的发布流程；
    * 支持TypeScript、ESM、JSX 和 Wasm
* [ 190622 ] bitmap算法：如何在20亿个非负整数中如何判断一个数是否存在？<https://www.toutiao.com/a6705196655190213123/> [ from 大民 ]
* [ 190626 ] 视错觉骗局，俩小球颜色一样却有千万人看错 <https://www.toutiao.com/a6706801644597690888/> [ from 大民 ]

> 开源

* [ 190629 ] windows terminal <https://github.com/microsoft/Terminal> <iframe src="http://258i.com/gbtn.html?user=microsoft&repo=Terminal&type=star&count=true" frameborder="0" scrolling="0" width="105px" height="20px"></iframe> [ from 大民 ]



## 190617-190622

`本周轮值主编`: 黄良辰 `下周轮值主编`: 赵文玲

> 资讯

- [ 190618 ] facebook发布网络加密货币libra https://github.com/libra/libra https://libra.org/zh-CN/ [from 良辰]
   * 安全、可扩展和可靠的区块链
   * 基础实际的资产储备为担保
   * 独立的 Libra 协会治理

> 技术

- [ 190617 ] JS中的内存管理 https://juejin.im/post/5d0706a6f265da1bc23f77a9 [from 鹏程]  
   * 引用计数垃圾收集、循环引用用标记清除算法
   * 常见的内存泄露，意外的全局变量、被遗忘的定时器和回调函数、闭包、DOM 引用
- [ 190620 ] 如何做好微交互，来提升产品的用户体验？https://www.toutiao.com/i6569004767572394503 [from 文玲]
- [ 190603 ] 8个你不知道的DOM功能 https://segmentfault.com/a/1190000019364550 [from 正杰]
- [ 190411 ] 编写更快的 React 代码（一）：memoize-one https://www.jianshu.com/p/b123bbe0330c [from 君毅]
   * 基于 memoize-one 对 render 方法进行优化，可以达到减轻不必要 render 复杂度的效果
- [ 190621 ] 科普一下CORS以及如何节省一次 OPTIONS 请求 https://dwz.cn/0R0KY7Ee [from 晓鹏]
   * 跨域OPTION请求 http://172.17.10.41:8020/fanxiaopeng/option-request.md.html [from 晓鹏]

> 实践

- [ 190621 ] leaflet 绘制路径时如何以实际距离为半径，而不是以像素值为半径 http://172.17.10.41:8020/chenmingcheng/leaflet_route.html [from 明成]
- [ 190613 ] Drawing Realistic Clouds with SVG and CSS https://css-tricks.com/drawing-realistic-clouds-with-svg-and-css/ [from 大民]
   * 这是一篇使用SVG滤镜和CSS3特性结合，来创造云朵特效的实践文章

> 深度

- [ 190612 ] Vue Function-based API RFC https://zhuanlan.zhihu.com/p/68477600 [from 君毅]
   * 尤雨溪亲自对vue 3.0 最重要的 RFC 翻译成了中文





## 190603-190615

`本周轮值主编`: 吴海萍 `下周轮值主编`: 黄良辰

> 资讯

- [ 190613 ] Vim 和 NeoVim 曝出高危漏洞 <http://www.cnbeta.com/articles/tech/856951.htm>   [from 大民]


> 技术

- [ 190614 ] 图谱2D渲染引擎实体节点绘制方式升级介绍：http://172.17.10.41:8020/zhaojunyi/SophonWeb/graph-performance/image-data-upgrade.md.html  [from 君毅]
  * 介绍了智子图谱2D渲染引擎实体绘制方式的升级实践
- [ 190513 ] A pure CSS onclick context menu：https://www.simonewebdesign.it/pure-css-onclick-context-menu/   [from 君毅]
   * Has no dependencies;
   * Can be triggered with a click/tap on any element;
   * Is fully cross-browser;
   * Doesn’t need JavaScript!
- [ 190613 ]  Vue Function-based API RFC 中文版：https://zhuanlan.zhihu.com/p/68477600  [from 明成]
  * 可以关注下：mixin和HOC之外，vue 3.0 如何设计逻辑复用


> 深度

- [ 190609 ] 2020年你应该知道的8种前端JavaScript趋势和工具 <https://mp.weixin.qq.com/s/XUkLCdTaXbtBKRWd4N9bLw>   [from 大民]
    * 框架无关的Web组件
    * 框架战争的未来
    * 组件隔离、重用和组合
    * ES模块和CDN
    * **组件级状态管理**


> 新鲜货

- [ 190605 ] 命令行的艺术 <https://github.com/jlevy/the-art-of-command-line/blob/master/README-zh.md> <iframe src="http://258i.com/gbtn.html?user=jlevy&repo=the-art-of-command-line&type=star&count=true" frameborder="0" scrolling="0" width="105px" height="20px"></iframe> [from 大民]
- [ 190614 ] OS.js - WEB桌面，提供窗口管理、应用API、GUI工具集以及文件系统的抽象功能。后端基于nodejs，与VS Code Server版类似  <https://github.com/os-js/OS.js> 在线Demo <https://demo.os-js.org/v3/>  [from 大民]
- [ 190614 ] node-gitlab: GitLab API NodeJS library with full support of all the Gitlab API services. <https://github.com/jdalrymple/node-gitlab> <iframe src="http://258i.com/gbtn.html?user=jdalrymple&repo=node-gitlab&type=star&count=true" frameborder="0" scrolling="0" width="105px" height="20px"></iframe>  [from 大民]
- [ 190614 ] actionview - 开源的类jira工具 <https://github.com/lxerxa/actionview>  [from 大民]


> 会议  

- [ 190604 ]  尤大大带来的Vue3.0技术分享：https://zhuanlan.zhihu.com/p/68099662?utm_source=wechat_session&utm_medium=social&utm_oi=807167234526056448  [from 文玲]
- [ 190613 ]  VueConf 的演讲视频： https://node.fequan.com/playvideo/701606bc91ece45fc7650b5ac92653ae_7?from=timeline&isappinstalled=0 [from 明成]
- [ 190608 ] VueConf 2019 <https://vue.w3ctech.com>   [from 大民]
   * State of Vue - 尤雨溪 <https://img.w3ctech.com/VueConf2019SH_Evan.pdf>
   * vue rfcs - <https://github.com/vuejs/rfcs> Request For Comments


> 小技巧

- [ 190612 ]  chrome 开发者工具的 11 个技巧：https://mp.weixin.qq.com/s/-_rhL1UPDpk1HxSySgS86A [from 海萍]



## 190527-190601

`本周轮值主编`: 聂正杰 `下周轮值主编`: 吴海萍

> 资讯

- [ 190528 ] w3c和whatwg签署协议，统一html和dom规范 https://www.w3.org/blog/news/archives/7753 [from 良辰]
- [ 190531 ]  Angular重大版本升级： 8.0正式发布!支持更多Web标准 https://mp.weixin.qq.com/s/W_j0hb3xLkNvpk6Cq6AXgg [from 海萍]

> 技术

- [ 190530 ] 多端统一开发框架，支持用 React 的开发方式编写一次代码，生成能运行在微信/百度/支付宝/字节跳动小程序、H5、React Native 等的应用 https://github.com/NervJS/taro [from 建中]  
- [ 190528 ] 响应式布局提高篇 - 图片正确的打开方式 https://mp.weixin.qq.com/s/-ntx38cG6iFyMVZq38hAmA [from 文玲]
    - 概念：物理像素（设备像素），逻辑像素（CSS 像素、设备独立像素）,设备像素比（Device Pixel Ratio，DPR）
    - 媒体查询提供对设备的视口大小进行判断的方法，可以根据不同的设备特征应用不同样式。
    - 实现响应式图片的两个方向：分辨率切换（resolution switching），艺术方向（art direction）  
- [ 190530 ] [新世界的大门]这还是我了解的那个HTML标签吗？https://juejin.im/post/5cef3fd65188250726641538 [from 婉如]
    - `<ruby>` 拼音显示
    - `<details>` 挂件-收缩折叠
    -  `<meter>` 计量器
    - `<picture>` 图片元素
    - `<track>`媒体元素-字幕功能  
- [ 190530 ] impress.js:  It's a presentation framework based on the power of CSS3 transforms and transitions in modern browsers and inspired by the idea behind prezi.com. https://github.com/impress/impress.js [from 明成]

> 实践

- [ 190519 ] JavaScript Clean Code - Best Practices JS编码最佳实践 https://devinduct.com/blogpost/22/javascript-clean-code-best-practices [from 大民]
    1. strong type checks
    2. variables
    3. functions
    4. conditionals
    5. ES classes
    6. avoid in general: don't write duplicated code
- [ 190601 ] 青桔单车 chameleon 跨平台实践分享 https://mp.weixin.qq.com/s/N8PpxRHHtlIHVlemQ1Gepg [from 大民]
- [ 190522 ] WebAssembly at eBay: A Real-World Use Case：
Saying “No” to 99 things and “Yes” to the one thing that really matters to our customers https://www.ebayinc.com/stories/blogs/tech/webassembly-at-ebay-a-real-world-use-case/ [from 君毅]
- 代码的味道__智子代码萃取 http://172.17.10.41:8020/sophon/code-guide/code-practice.md.html [from 陈荣]
- 小tips: 如何借助content属性显示CSS var变量值 https://www.zhangxinxu.com/wordpress/2019/05/content-css-var/ [from 婉如]

> 教程

- Three.js入门指南 http://www.ituring.com.cn/book/miniarticle/58552 [from 正杰]

> 框架  

- [ 190520 ] San 为什么会这么快 https://efe.baidu.com/blog/san-perf/ [from 大民]

> 可视化

- [ 190520 ] Folding the DOM 用CSS 3D效果来达到DOM折叠的效果。比如翻书效果，表达折叠成信封发送等 https://www.joshwcomeau.com/posts/folding-the-dom/ [from 大民]

> 杂谈

- [ 190525 ] 太舒服的事情，是危险的：下意识警惕一切试图让我们「沉浸」的事物 https://mp.weixin.qq.com/s/Q0O69kPSg6XsXEtLpo9LXw [from 君毅]
- [ 190530 ] 比能力重要100倍的，是这3个底层思维 https://www.toutiao.com/a6696700441113133572/ [from 大民]
    - 当你牛到一定程度，底层能力可以迁移
    - 用更高的版本要求自己
    - **攻其一点，不及其余**
    - **越努力，越自由**；越努力，越有选择权
- [ 190530 ] 中国程序员现状调查分析又一波幽默漫画 https://www.toutiao.com/a6696630700012995076/ [from 大民]

## 190520-190525

`本周轮值主编`: 大民 `下周轮值主编`: 聂正杰

> 资讯

* [ 190521 ] 【重磅】Chameleon 开放跨端扩展标准协议 <https://mp.weixin.qq.com/s/MuNpQLKg2IuwOAvjJHwl3Q> chameleon 基于对跨端工作的积累， 规范了一套跨端标准，称之为 **MVVM+协议** ；开发者只需要按照标准扩展流程，即可快速扩展任意 MVVM 架构模式的终端 [ from 文玲 ]
* [ 190517 ] 华为面向全球发布AI-Native数据库 <https://www.huawei.com/en/press-events/news/2019/5/huawei-launches-ai-native-database> <https://mp.weixin.qq.com/s/hFrkvEcmYtSDTxrpVHxBlQ> 继2018年发布AI战略和全栈全场景AI解决方案后，华为公司15日在京面向全球发布了**人工智能原生（AI-Native）数据库GaussDB**和业界性能第一的**分布式存储FusionStorage 8.0**，秉承“数据+智能”的理念重定义数据基础设施 [ from 大民 ]
* [ 190516 ] V8 release 7.5 <https://v8.dev/blog/v8-release-75> 对应Chrome 75，关键更新WebAssembly、Numeric separators、Performance  [ from 大民 ]
* [ 190516 ] Announcing TypeScript 3.5 RC <https://devblogs.microsoft.com/typescript/announcing-typescript-3-5-rc/> `$ npm install -g typescript@rc` [ from 大民 ]
    * Speed improvements
    * The Omit helper type
    * Improved excess property checks in union types
    * The *--allowUmdGlobalAccess* flag
    * Smarter union type checking
    * Higher order type inference from generic constructors
    * Breaking changes
* [ 190516 ] W3C Invites Implementations of WoT Thing Description and WoT Architecture <https://www.w3.org/blog/news/archives/7745> [ from 大民 ]
    * Web of Things (WoT) Thing Description <https://www.w3.org/TR/2019/CR-wot-thing-description-20190516/>
    * Web of Things (WoT) Architecture <https://www.w3.org/TR/2019/CR-wot-architecture-20190516/>
* [ 190524 ] tc39 proposals <https://github.com/tc39/proposals> [ from 大民 ]
* [ 190513 ] New Electron Release Cadence <https://electronjs.org/blog/12-week-cadence> 新的发布节奏，每12周发布一次stable版本，尽量追赶Chromium内核步调

> 新鲜货

* [ 161209 ] (Git)合并多个commit <https://segmentfault.com/a/1190000007748862> 在使用 Git 作为版本控制的时候，我们可能会由于各种各样的原因提交了许多临时的 commit，而这些 commit 拼接起来才是完整的任务。那么我们为了避免太多的 commit 而造成版本控制的混乱，通常我们推荐将这些 commit 合并成一个 [ from 王建中 ]
        $ git rebase -i HEAD~3
        $ git rebase -i 3a4226b
        $ git rebase --continue
        $ git rebase --abort
* [ 180531 ] Alfred神器使用手册 <http://louiszhai.github.io/2018/05/31/alfred/>. 我曾经耗费巨大的精力，试图在计算机的使用效率上找到一条优化的捷径，一直以来都收效甚微。直到遇上 alfred，它强大的工作流机制，彻底解决了输入输出的痛点，极大的减少了程序之间的切换成本和重复按键成本，这才让我明白，原来计算机可以这么玩 [ from 陈荣 ]


> 深度

* [ 190515 ] JavaScript Engines: How Do They Even Work? From Call Stack to Promise, (almost) Everything You Need to Know <https://www.valentinog.com/blog/engines/> [ from 大民 ]
    * Global Memory ( also called Heap ), Global Execution Context, Call Stack
    * single-threaded
    * Callback queue and the Event Loop: setTimeout()
    * ES6 Promises and Error Handling
    * ES6 Promises and Microtask queue
    * ES8 async/await

> 架构实践

* [ 190517 ] Nebula 来了，支付宝 App 跨平台动态化框架 <https://mp.weixin.qq.com/s/lwVfTI7mRMlU7eSGeKCD3g> 支付宝APP从工具型APP，到平台型APP，再到超级APP的架构演化过程；目前支付宝的架构解说；由Nebula和小程序提供的动态化支持；mPaaS技术架构使得支付宝可以向第三方提供动态化能力，例如12306、苏州银行、上海地铁等
* [ 190523 ] 滴滴杜欢：大型微服务框架设计实践 <https://mp.weixin.qq.com/s/vOYhlpRaN-uF0DIrZ-sM-w> 滴滴大型业务系统微服务架构实践，使用Go语言开发，实现要点：框架与业务正交；隔离层屏蔽业务与底层的联系；使用FSM劫持thrift protocol；跨服务边界的context；防雪崩等

> 可视化

* [ 190523 ] 看完这篇，你也可以实现一个360度全景插件 <https://mp.weixin.qq.com/s/pKJBH4Ce68nfnmYbQlaSKw> [ from 文玲 ]
* [ 190524 ] 教程：Three.js Fundamentals <https://threejsfundamentals.org/threejs/lessons/threejs-fundamentals.html>
* [ 190521 ] <https://paveldogreat.github.io/WebGL-Fluid-Simulation/> 太酷了，WebGL流体模拟 [ from 永禄 ]
* [ 190514 ] draw 10,000 objects on canvas javascript：<https://stackoverflow.com/questions/23468218/draw-10-000-objects-on-canvas-javascript> [ from 君毅 ]
    * if you need to draw a ridiculous number of objects on the canvas you can't use drawImage, **pixel manipulation** is your friend
    * canvas—10000个动态元素绘制示例：<https://jsfiddle.net/loktar/63QZz/> 在canvas中以imageData的形式直接绘制10000个元素的动画效果
* **Pixel manipulation** with canvas：<https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Pixel_manipulation_with_canvas> 介绍了在cavans里通过imageData来进行像素级绘制的方式 [ from 君毅 ]
* [ 190524 ] React-Canvas: High performance `<canvas>` rendering for React components <https://github.com/Flipboard/react-canvas> [ from 明成 ]
* [ 150210 ] 介绍性博客文章: <https://engineering.flipboard.com/2015/02/mobile-web> [ from 明成 ]
    * DOM 是一种保留模式(`retained mode`)的API，可以相对容易的渲染复杂层次结构的用户界面，但有性能损耗。
    * `Canvas` 是一种立即模式(`immediate mode`)的渲染API，允许将绘图命令直接发送到GPU，但是使用它来构建用户界面需要更高级别的抽象才能提高效率。
    * `React Canvas` 使用组件化的方式进行 canvas 渲染, 为 React 增加了渲染到 `<canvas>` 的能力。并不是为了完全取代DOM，如果不关心性能的话 DOM 会是更好选择。
