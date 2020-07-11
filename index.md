# 技术快报

> 业界技术跟进，不限于前端技术，按时间逆序梳理，每周一份，[轮值主编制度参考](./editors.md)

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

