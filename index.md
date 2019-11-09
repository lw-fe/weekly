# 技术快报

> 业界技术跟进，不限于前端技术，按时间逆序梳理，每周一份，[轮值主编制度参考](./editors.md)

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

