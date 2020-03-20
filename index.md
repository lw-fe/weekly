# 技术快报

> 业界技术跟进，不限于前端技术，按时间逆序梳理，每周一份，[轮值主编制度参考](./editors.md)

## 200314 - 200321

`本周轮值主编`: ：学聪 `下周轮值主编` 鹏程

* [20190823] 用useRef() 保存任何可变值 <https://blog.csdn.net/wu_xianqiang/article/details/100037632> [ from 海萍 ]
   * 用useRef来解决此种问题场景：异步请求回调中setState后，在该回调以及回调中执行的异步方法的回调中无法取到最新state值。
* [ 20200317 ] 考拉前端骨架屏生成技术揭秘<https://mp.weixin.qq.com/s/4DAlmuMzyNjDKvaoOU1GoA> [ from 良辰 ]
* [ 200317 ] 跨域总结:从CORS到Ngnix <https://juejin.im/post/5e6c58b06fb9a07ce01a4199> [ from 文玲 ]
    * 跨域解决方案：jsonp、cors、postMessage、websocket、node中间件代理
    * nginx反向代理
* [20200320] css动画是可以暂停的 <http://www.daqianduan.com/7027.html> [ from 红梅 ]
* [20200320]  从零开始写一个采集图片的chrome插件<https://juejin.im/post/5e745f35e51d4526c80ec11c> [ from 红梅 ]
* [20200320] require相关 && forever进程守护 <http://gitlab.lvwan-inc.com/sophon-wiki/sophon-docs/tree/master/zhaisiyuan/project/hao123> [from 思源]
* [20200317] 100个网络基础知识 <https://mp.weixin.qq.com/s/TPlrJ3X2h3l27HX7juOqcw> [from 思源]
* [ 200320 ] sigmaV2 webgl 学习总结：<http://fe.lvwan-inc.com/zhaojunyi/SophonWeb/webgl/sigma-webgl.md.html> [from 君毅]
    * 介绍了sophon sigmaV2中节点的一些绘制方式
* [ 200311 ] Ant Design 4.0 发布，我们和核心作者聊了聊：<https://www.infoq.cn/article/eudM9WdF9aoYHmcA5rGr> [from 君毅]
    * 介绍了antd 4.0  版本更新背后的一些故事
* [ 20200321 ] High Performance SVGs<https://css-tricks.com/high-performance-svgs/> [ from 学聪 ]
## 200309 - 200314

`本周轮值主编`: 晓朋 `下周轮值主编`：学聪

> 咨询

* [20200310] 前端从业分布与技术关注的一点看法 https://www.zhangxinxu.com/life/2020/02/frontend-should-focus/ [from 思源]
* [20200313] 又来了！Google 和微软在浏览器上的互掐 https://mp.weixin.qq.com/s/kqB19kP6Qow_kEmO6-Z7NQ [from 思源]

> 干货

* [200313] 前端常见的加密算法介绍 https://segmentfault.com/a/1190000022000598 [from 红梅]
    * 对称 AES 开源库： https://github.com/brix/crypto-js
    * 非对称 RSA开源库：https://github.com/travist/jsencrypt
    * hash MD5 加密开源库：https://github.com/blueimp/JavaScript-MD5
* [ 20200313 ] 拒绝JavaScript，这三个CSS技巧你一定用的上  <https://juejin.im/post/5e6b2b9ce51d4526fd069b87> [from 海萍]
* [ 170223 ] webgl开发第一道坎—矩阵与坐标变换：https://www.cnblogs.com/dojo-lzz/p/7223364.html [ from 君毅 ]
    * 介绍了webgl开发中常用的基本知识
* [ 200313 ] React Hooks 响应式布局  <https://juejin.im/post/5e65c1f16fb9a07c9645a64c>[from 文玲]
    * innerWidth
    * hooks + resize
    * 构建useViewport
    * hooks + Context
* [ 20171127 ] moment对象通过JSON.stringify(data)后少了8小时？ <https://segmentfault.com/q/1010000012180458>[from 海萍 ]
    * 合理利用对象的toJSON特性解决Date对象/moment对象转换后会少8小时的问题
* [ 20191210 ] 你不知道的 JSON.stringify() 的威力   <https://juejin.im/post/5decf09de51d45584d238319> [from 海萍 ]
* [ 200313 ] all-in-one的javascript 工具链Rome https://github.com/facebookexperimental/rome [from 良辰]
    * 转换值如果有?toJSON()?函数，该函数返回什么值，序列化结果就是什么值，并且忽略其他属性的值
* [ 200312 ] 如何推动前端团队的基础设施建设 <https://juejin.im/post/5e644a65518825495d69bca6> [from 晓朋 ]


## 200302-200307
`本周轮值主编`: 文玲 `下周轮值主编`: 晓朋

> 干货
* [ 180725 ] ES6的const并非一定为常量 <https://blog.fundebug.com/2018/07/25/es6-const/> [ from 海萍 ]
    * const保证的，并不是变量的值不得改动，而是变量指向的那个内存地址所保存的数据不得改动
* [ 191029 ] 高性能渲染十万条数据(虚拟列表) <https://juejin.im/post/5db684ddf265da4d495c40e5> [ from 良辰 ]
    * antd-4.0 使用的虚拟列表组件 virtual-list <https://github.com/react-component/virtual-list>
* [ 200305 ] 忍法，scroll 翻滚之术！<https://mp.weixin.qq.com/s/rIDxlYtjFznabut_Ew2F2w> [ from 思源 ]
* [ 200304 ] 从零开始做一个图片裁剪组件 <https://juejin.im/post/5e5f5a716fb9a07ca301e3c4> [ from 红梅 ]
* [ 200224 ] 从零手写一套 Express 的源码 <https://juejin.im/post/5e532e65518825490966da43> [ from 文玲 ]
     * 返回核心函数
     * 监听函数
     * 实现get\post\all
     * 中间件\错误中间件\内置中间件
* [ 200224 ] 在async/await 中更好的处理错误 <https://juejin.im/post/5e535624518825496e784ccb> [ from 文玲 ]

> 网络
* [ 200303 ] 计算机网络知识<https://juejin.im/post/5e51febde51d4526c932b390> [ from 晓朋 ]

> 系统
* [ 200304 ] CentOS 入门必备基础知识 <https://juejin.im/post/5e5f13936fb9a07cdf534c62> [ from 思源 ]

> 前瞻
* [ 200306 ] 2020 前端开源领域技术展望 <https://mp.weixin.qq.com/s/3pxBcvfq3SGc2vi_3fGaVA> [ from 大民 ]

> 测试
* [ 200224 ] Make Your Test Fail：<https://kentcdodds.com/blog/make-your-test-fail> [ from 君毅 ]
    * If you're not careful you can write a test that's worse than having no tests at all
* [ 200304 ] React Testing Library：<https://testing-library.com/docs/react-testing-library/intro> [ from 君毅 ]
    * The React Testing Library is a very light-weight solution for testing React components. It provides light utility functions on top of react-dom and react-dom/test-utils, in a way that encourages better testing practices
