# 技术快报

> 业界技术跟进，不限于前端技术，按时间逆序梳理，每周一份，[轮值主编制度参考](./editors.md)


## 200608 - 200613

`本周轮值主编`: 海萍 `下周轮值主编`：良辰

> 干货
* [ 200521 ] B站的视频，都是怎么推荐的 <https://mp.weixin.qq.com/s/Jw1Bp6zdIO7aGbMdTNgZyw/> [ from 君毅 ]
    * B站的推荐系统并不会止步于用户已有兴趣的推荐，而是会在探索中鼓励用户发现自身更多元化的兴趣，这就是基于用户的协同推荐要优于基于内容的协同的地方
* [ 200606 ] 通俗易懂的 TypeScript 入门教程 <https://mp.weixin.qq.com/s/oaoZZ6RyIffr0scpWGtSSQ> [ from 文玲 ]
* [ 200608 ] 如何实现高性能的在线 PDF 预览 <https://mp.weixin.qq.com/s/Wx_gJLrZftJ_dm2phoUf8g> [ from 思源 ]
* [ 200610 ] 编写React组件时常见的5个错误 <https://mp.weixin.qq.com/s?__biz=MzUxMzcxMzE5Ng==&mid=2247496262&idx=2&sn=20eb42cb0176a96f1a766d5ccc8ffd30> [ from 良辰]

> 经验
* [ 200606 ] 科技向善---马化腾谈使命愿景 <https://mp.weixin.qq.com/s/krnKp91WbLGbbiucpM9miA> [ from 晓朋 ]
        * 科技是一种能力，向善是一种选择
* [ 200608 ] 面试官问我：一个 TCP 连接可以发多少个 HTTP 请求？我竟然回答不上来... <https://mp.weixin.qq.com/s/EkWOXAcuzkUexWAyra_PwA> [ from 思源 ]
    * 现代浏览器在与服务器建立了一个 TCP 连接后是否会在一个 HTTP 请求完成后断开？什么情况下会断开？
    * 一个 TCP 连接可以对应几个 HTTP 请求？
    * 一个 TCP 连接中 HTTP 请求发送可以一起发送么（比如一起发三个请求，再三个响应一起接收）？
    * 为什么有的时候刷新页面不需要重新建立 SSL 连接？
    * 浏览器对同一 Host 建立 TCP 连接到数量有没有限制？
* [ 200608 ] 前端如何在项目中做出亮点 <https://mp.weixin.qq.com/s/mlbgKrv8cn6k8nO1x19NfA> [ from 文玲 ]     
* [ 200611 ] 你所不知道的Blob <https://mp.weixin.qq.com/s/MPTTMUXLRK0boeMDYzmaLA> [ from 文玲 ]    

> 新鲜事物
* [ 200610 ] Chrome浏览器支持直接读写本地文件了 <https://segmentfault.com/a/1190000022895794> [from 红梅]
    * Chrome 83版本


## 200601 - 200606

`本周轮值主编`: 思源 `下周轮值主编`：海萍

> 干货
* [ 140612 ] 深度掌握SVG路径path的贝塞尔曲线指令 <https://www.zhangxinxu.com/wordpress/2014/06/deep-understand-svg-path-bezier-curves-command/> [ from 君毅 ]
    * 我们的学习可以再往上一层，关心贝塞尔曲线指令，让浏览器去帮我们绘制此指令下的贝塞尔曲线
* [ 200603 ] crontab简介 <http://support.lvwan-inc.com/0216c08361dab7455961aabd65c05418> [ from 思源 ]

> 实践
* [200605] Node.js Best Practices <https://github.com/goldbergyoni/nodebestpractices>  [ from 文玲 ]   
该库对排名较高 Node.js 的最佳实践进行了总结和整理，包括 Node.js + Docker 最佳实践。目前拥有超过80多种最佳实践，风格指南和结构建议等。一些常见的最佳做法包括：
    * 更好地组织项目
    * 错误处理实践
    * 代码风格实践
    * 测试和整体质量实践
    * 进行生产实践等等
* [200605]  修复一个因为 scrollbar 占据空间导致的 bug <https://segmentfault.com/a/1190000022851263> [ from 红梅 ]
* [200605] 前端瀑布流布局如何应用动态规划和贪心算法 <https://github.com/sl1673495/blogs/issues/48?from=groupmessage> [ from 良辰 ]
> 新鲜事物
* [200605] 使用 Nodejs 开发的 SpaceX-API 开源了！<https://juejin.im/post/5ed9cb3ef265da770f5203fa> <https://github.com/r-spacex/SpaceX-APIo>  [ from 文玲 ]  
技术栈如下：
    * 部署在美国中部 Linode 服务器上。
    * 使用了 Nodejs 的 Koa 框架。
    * 使用了 Redis、Nginx 和 Cloudflare 进行内容缓存。
    * 使用了 Jest 和 Supertest 做测试。
    * 使用了 Circle CI 进行持续集成/部署。
    * 所有的数据存储在 MongoDB Atlas 3 节点的副本集集群中。
    * 使用 mongodump 在晚上进行数据备份，在这里查看 https://backups.jakemeyer.sh/。

## 200525 - 200530

`本周轮值主编`: 红梅 `下周轮值主编`：思源

> 干货

* [ 200529 ] <https://mp.weixin.qq.com/s/U8wGi85BavBxFa8DcxAurw> [from 文玲 ]
* [ 200529 ] HTML a标签打开新标签页避免出现安全漏洞，请使用“noopener” <https://juejin.im/post/5ecfc6b5f265da76d53c0c91>  [from 良辰 ]
* [ 200528 ] 打包工具 Snowpack几个特性  <https://mp.weixin.qq.com/s/7Z8U6rGVIpy1R406mNqD6g> [ from 晓朋 ]
   * 内置对 TypeScript、JSX 和 CSS 模块等特性的支持
   * 可与 React、Preact、Vue、Svelte 和所有你喜欢的库一起使用
   * Create Snowpack App（CSA）入门模板
* [ 200519 ] 十个超级实用的git命令 <https://droidyue.com/blog/2020/05/19/cool-git-skills/?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io> [ from 君毅 ]
    * git checkout - （切换回上一个分支）
* [200525] 动态 Import 和 顶层 await <https://mp.weixin.qq.com/s/h69mRSA3_MeTfUgiCwT2LQ> [ from 思源 ]

> 类库

* [ 200528 ] javaScript导出excel文件，并修改文件样式 <https://segmentfault.com/a/1190000022772664> [ from 红梅 ]

> 总结

* [200529] 组件库支持按需加载实现方案 <http://gitlab.lvwan-inc.com/sophon-wiki/sophon-docs/blob/master/zhaisiyuan/article/on-demand-load.md> [ from 思源 ]
* [ 200529 ] 智子目前版本分支情况汇总 <http://fe.lvwan-inc.com/fanxiaopeng/sophon-version-branch/version-branch.md.html> [ from 晓朋 ]

## 200518 - 200523

`本周轮值主编`: 君毅 `下周轮值主编`：红梅

> 干货

* [ 200521 ] 了不起的 Deno 入门教程 <https://dwz.mn/DJXu> [ from 文玲 ]
    * Deno 能够在 macOS、Linux 和 Windows 上运行。Deno 是一个单独的可执行文件，它没有额外的依赖
* [ 200520 ] 浅谈CSS3 动画卡顿解决方案 <https://www.jb51.net/css/653308.html> [ from 君毅 ]
    * 尽量使用 transform 实现动画，避免使用 height, width, margin, padding, top, left 等
* [ 200519 ] 犀牛书作者：最该忘记的JavaScript特性 <https://mp.weixin.qq.com/s/guAN1Cz2gYfKdBhmUpLyVA> [ from 思源 ]
    * arguments，join 拼接字符串，document.write，frame 等
* [ 200522 ] 网页渲染性能优化  <https://zhuanlan.zhihu.com/p/39878259> [ from 思源 ]
* [ 200518 ] gitlab内置的三个工具(持续集成、交付、部署) <https://mp.weixin.qq.com/s/skajt8Lh1UztpdhjdfSutg> [ from 晓鹏 ]
    * GitLab CI/CD 是一个内置在GitLab中的工具，用于通过持续方法进行软件开发
* [ 200512 ] 大规格文件上传优化 <https://aotu.io/notes/2020/05/12/file-upload/index.html> [ from 良辰 ]
    * Blob.slice 将文件切片，并发上传多个切片，所有切片上传后告知服务器合并，实现大文件分片上传

> 资讯

* [ 20200518 ] CSS Containment 规范正式发布 <https://www.infoq.cn/article/lBECNlBbgd81U01aQUMF> [ from 红梅 ]
    * CSS Containment 模块规范的主要目的是，在页面渲染的过程中通过忽略文档中的某些子树来提高页面的渲染性能

> 小工具

* [ 200520 ] WeChatExtension-ForMac <https://github.com/MustangYM/WeChatExtension-ForMac> [ from 君毅 ]
    * Mac版微信的功能拓展(A plugin for Mac WeChat)

> 拓展

* [ 200508 ] 从全国首起暗网案件告破说起——暗网，超乎你想象 <https://xie.infoq.cn/article/15962348e63060bcf7f3b8f67> [ from 君毅 ]
    * “暗网”是指只能通过特殊软件对指定电脑进行授权、进行特别的配置才能访问的网络
    * 暗网里的服务器和数据传输都是“隐形”的，在暗网以外（称之为明网）的搜索引擎上无法检索到，googgle也不行
    * 暗网成员之间的通信有高轻度的隐蔽性、安全性，一般技术手段很难拦截，即使拦截到也难以破解、难以追溯

> 总结

* [ 200518 ] 自定义域名申请使用总结 <http://fe.lvwan-inc.com/zhaojunyi/other/custom-domain/custom-domain.md.html> [ from 君毅 ]
    * 前端项目通常部署在41机器的预览环境，通过不同端口访问不同环境。当我们希望访问路径更加有意义，或者需要在办公网络下从云桌面之外访问时就需要通过申请自定义域名来实现
* [ 200520 ] 大屏开发响应式布局总结 <http://fe.lvwan-inc.com/zhaojunyi/other/big-screen-pc/big-screen-pc.md.html> [ from 君毅 ]
    * 介绍了响应式布局常见技术及绿湾大屏使用的相关方案


## 200511 - 200516

`本周轮值主编`: 晓朋 `下周轮值主编`：君毅

> 干货

* Deno 1.0正式发布！这是来自官方团队的安利 https://mp.weixin.qq.com/s/CiZOtVoFl-LhzHXyLHiJ2Q [ from 文玲 ]
* [200513] 花式解说防抖函数debounce的实现 https://mp.weixin.qq.com/s/JqEXJCmp3WNhm6qICpq4Ww [from 思源]
* [200512] 接地气的react hooks 入门指南 http://gitlab.lvwan-inc.com/sophon-wiki/sophon-docs/blob/master/zhaisiyuan/article/react-hooks.md [from 思源]
* [ 200415 ] 浏览器工作原理 https://segmentfault.com/a/1190000022633988 [ from 红梅 ]
* [ 20100816 ]  js 的Object.assign(),要慎用 <http://www.seotest.cn/jishu/44408.html> [ from 海萍 ]
* 相见恨晚的 Git 命令动画演示 https://mp.weixin.qq.com/s/GiN7Lp-ghF43J1KxkDnmfw [ from 良辰 ]
   * 只对顶层属性做了赋值，没有继续做递归之类的把所有下一层的属性做深拷贝

> 资讯

* [ 200428 ] 苹果往事：乔布斯和 iPod 的诞生：http://www.ruanyifeng.com/blog/2020/04/ipod-history.html [ from 君毅 ]
    * 1999年，乔布斯发现，苹果公司有一种新技术的专利，但是一直没有使用，那就是火线（FireWire）。这种接口的传输速度，比当时流行的 USB 1.1 接口快几十倍（善于发现优势）
    * 乔布斯认为，市场上所有此类产品都很糟糕，非常丑也非常难用，苹果公司有必要开发一个自己的便携式 MP3 播放器（对高标准的不断追求）
    * 乔布斯定下了这个播放器要在2001年圣诞节购物季上市。这只留给法德尔6个月的时间，他必须在6个月里面组建团队、开发产品、制造产品并放上货架（敢于制定充满风险的目标）

## 200427 - 200509

`本周轮值主编`: 文玲 `下周轮值主编`：晓朋

> 干货
* [ 200507 ] 用动画和实战打开 React Hooks系列（1，2，3）
    * useState、useEffect<https://juejin.im/post/5e8d2e06f265da47c801271e>
    * 自定义hook、useCallback <https://juejin.im/post/5e9c5217f265da47c06ed913>
    * useReducer、useContext<https://juejin.im/post/5eb2b8b4f265da7bd802ae8b> [ from 文玲 ]
* [ 200423 ] JS干货知识总结 <https://juejin.im/post/5e9f0bdce51d4546f5791989> [ from 文玲 ]
* [ 200507 ] webpack4 与 webpack5 公共代码抽离方案 <https://juejin.im/post/5eb382c26fb9a04388075b45> [ from 文玲 ]
* [ 200506 ] Web上的图片技巧 <https://mp.weixin.qq.com/s/0_LwuVfj8b5CvEra-cEhgw> [ from 思源 ]
* [ 200506 ] 全新Chrome Devtool Performance使用指南 <https://zhuanlan.zhihu.com/p/29879682> [ from 思源 ]
* [ 200508 ] 基于 qiankun 的微前端最佳实践（图文并茂） - 应用间通信篇 <https://segmentfault.com/a/1190000022583716> [ from 红梅 ]
* [ 200508 ] 项目打包问题总结 <http://fe.lvwan-inc.com/fanxiaopeng/sophon-build-error/sophon-build-error.md.html> [ from 晓朋 ]

> 教程
* [ 200421 ] 大神阮一峰的《Bash 脚本教程》免费发布啦，开源！：<https://mp.weixin.qq.com/s/1QcbRaaNzG064LxEWcbWkg> <https://wangdoc.com/bash/> [ from 君毅 ]
    * 网上找不到简明扼要的中文教程，我很早就想整理一个，方便自己日后使用。我一共写了 20 节，Bash 脚本编程的主要语法，都包括在内了，日常使用应该足够。也欢迎初学者使用这个教程，学习 Bash

> 工具
* [ 200508 ] 一个方便进行各种语言转换的 VS Code 插件 <https://github.com/antfu/i18n-ally/blob/master/README.zh-CN.md> [ from 良辰 ]
* [ 200508 ] js混淆加密工具 <https://www.sojson.com/jsobfuscator.html> [ from 学聪 ]
    * sojson.v5最牛加密脱壳解密破解去混淆 <https://www.yyob.com/202.html>

> 资讯
* [ 200408 ] InfoQ 2020 年 JavaScript 和 Web 开发趋势报告 <https://mp.weixin.qq.com/s/ktxx4TM_oj8Z-FU_2Okgpw> [ from 大民 ]
    * WebAssembly 在 2019 年底达到了稳定的 1.0 W3C 推荐水准
    * ES2020提供自 ES2015 年以来数量最多的新语言特性，包括可选链、BigInt、globalThis、空值合并和动态导入
    * Web component 已经达到了主流成熟阶段
    * TypeScript 已经升级到晚期大众状态
    * JavaScript 客户端框架和库的领域在持续发生着变化

