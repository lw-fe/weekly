# 技术快报

> 业界技术跟进，不限于前端技术，按时间逆序梳理，每周一份，[轮值主编制度参考](./editors.md)

## 210125-200129

> `本周轮值主编`：晓朋 `下周轮值主编`：良辰

> 干货

* [ 210205 ]如何在不用JS代码情况下实现一个实时聊天功能   <https://mp.weixin.qq.com/s/et_8zUM_zgHvbSOChi4fDg> [from 红梅]
* [ 210204 ]尤雨溪 3 天 10 更的 Vite 究竟有什么魔力？<https://juejin.cn/post/6924997323214815240> [ from 韩硕 ]
* [ 210204 ] * [ 210204 ] Games on GitHub <https://github.com/leereilly/games>  [ from 君毅 ]

    *  a list of open source games and game-related projects that can be found on GitHub
* [ 210118 ] 这些js中强大的操作符，总有几个你没听说过 < https://juejin.cn/post/6918902650964557838 >  [ from 雪松 ]

> 工具

*  [ 210202 ] CodeReview 下一代：基于 KAITIAN 的纯前端 CR IDE <https://mp.weixin.qq.com/s/9lL2ytPUPzVtfj0lIEIxFg>[from 晓朋 ]

> 职业发展

* [ 210203 ] 阿里大牛分享：如何对 P5/P6/P7 做职业规划和技术培养 <https://mp.weixin.qq.com/s/z0eI2SuluTxG-dLWxnrkOg> [from 文玲]


## 210125-200129

> `本周轮值主编`：海萍 `下周轮值主编`：红梅

> 干货

* [ 210128 ]  就是要让你搞懂Nginx，这篇就够了！<https://mp.weixin.qq.com/s/eF5LcW2GI6ZylDJNIK4nzw> [ from 凌云 ]
* [ 210128 ] sketch搭配蓝湖高效率开发！ <https://tieba.baidu.com/p/6757832764>  [ from 韩硕 ]
   * sketch蓝湖插件：https://lanhuapp.com/mac/
* [ 210126 ] 教你用PixiJs实现复杂动画 <https://mp.weixin.qq.com/s/IzCAzswK50BbfNHqE8vIxQ> [ from 红梅 ]
* [ 210126 ] grid布局 <https://juejin.cn/post/6922062483196903438>  [ from 雪松 ]


> 技巧

* [ 210105 ］前端常见内存泄漏及解决方案 <https://juejin.cn/post/6914092198170460168>  [ from 良辰 ]
* [ 180930 ] echarts 图例 两行展示 <https://blog.csdn.net/rebooting_now/article/details/82909177> [ from 海萍 ]
   * 合理利用width/height属性，配合orient,实现图例多列布局


> 新鲜物

* [ 210128 ] 拼图也能写代码？快来试试这个谷歌开源的工具！<https://mp.weixin.qq.com/s/7FtHn1vAYW1TCv3PcuB6Bw> [ from 文玲 ]
* [ 210126 ] Mozilla 推出 Open Web Docs，用于编写 Web API 文档  <https://mp.weixin.qq.com/s/YFn0-zyUvCpIzaGCnBrf4Q> [ from 红梅]
* [ 210106 ] 2021 年 Web 开发的 7 大趋势 <https://www.infoq.cn/article/74pTclrdFoCakANU3YRB>  [ from 君毅 ]
    * 深色主题 UI，语音识别技术...


## 210118-200123

> `本周轮值主编`：君毅 `下周轮值主编`：晓朋->海萍

> 干货

* [ 210120 ] 2020 中国开源年度报告 <https://juejin.cn/post/6919729106779275272>  [ from 文玲 ]
    * 开源大发展以及由实向虚进发的趋势
    * 中国开源崛起以及开源世界分裂的趋势
    * 开源向善以及我们尚未做好准备
* [ 210121 ] 图可视化之图布局 <https://segmentfault.com/a/1190000039054038>  [ from 红梅 ]
    * 主要探讨了各种不同场景的布局解决方案
* [ 210118 ] CSS 奇思妙想边框动画 https://juejin.cn/post/6918921604160290830  [ from 雪松 ]
* [ 210122 ] width: 100%和width: auto有什么区别 <https://juejin.cn/post/6894068581854478349> [ from 凌云 ]
* [ 210122 ] MockXMLHttpRequest在处理二进制流类型的response时的结果与源生方法不一致  <https://github.com/nuysoft/Mock/issues/299> [ from 韩硕 ]
* [ 210122 ] 26种JavaScript优化技术 <https://juejin.cn/post/6918607242359619592>  [ from 芳朝 ]

> 新鲜物

* [ 210101 ] My year in data <https://samplesize.one/blog/posts/my_year_in_data>  [ from 君毅 ]
    * 以可视化方式汇总统计了2020年的时间都用在哪里

> 讲座

* [ 200218 ] TED演讲：数据可视化的重要性，如何使抽象的数据更容易让人理解 <https://www.ixigua.com/6794718337415774723?wid_try=1>  [ from 君毅 ]
    *  拼接细碎的数据，以叙述性结构讲述成一个故事，从而产生意义

## 210111-200115

> `本周轮值主编`：文玲 `下周轮值主编`：晓朋

> 干货
* [ 210112 ] transform属性对普通元素的N多影响 <https://www.zhangxinxu.com/wordpress/2015/05/css3-transform-affect/#comments> [ from 雪松 ]
    * 咱们项目中大量使用了transform属性结合定位来实现居中效果，可能给后续开发造成很大影响
    * 最直接的影响就是子孙元素fix定位降级为absolute且无法溢出，还有层级混乱
    * lego-ui的Modal组件也使用了transform实现居中，在几天前的开发中给我造成过很大困扰
* [ 210111 ] pure CSS digital clock <https://www.quaxio.com/pure_css_digital_clock.html />  [ from 君毅 ]
    *  纯 CSS 实现的时钟，巧妙的利用了 border 与动画实现
* [ 210114 ] 【CSS】骨架屏 Skeleton 效果  <https://juejin.cn/post/6915763034069663752> [ from 韩硕 ]
* [ 210101 ] JavaScript ES2021 的新特性以及简单示例   <https://medium.com/better-programming/javascript-es2021-features-with-simple-examples-ada723b55355> [ from 良辰 ]
* [ 181029 ] 用 CSS 背景混合模式制作高级效果 <https://zhuanlan.zhihu.com/p/47946810> [ from 海萍 ]
* [ 180419 ] 妙用 scale 与 transfrom-origin，精准控制动画方向 <https://juejin.cn/post/6844903593137405959> [ from 凌云 ]

> 性能优化
* [ 210114 ] 拯救你的年底 KPI：前端性能优化总结 <https://mp.weixin.qq.com/s/vj9oRJYv8YGmjWy7lYY6XA > [ from 文玲 ]
    * 调试工具
    * WEB API
    * 雅虎军规
    * 压缩
    * webpack优化
    * 骨架屏
    * 窗口化
    * 缓存
    * 预加载 && 懒加载
    * ssr && react-snap
    * 体验优化

> 周刊统计
* [ 210114 ] 2020 周刊分享汇总 <http://fe.lvwan-inc.com/liuhongmei/weekly/weekly-stat-2020.md.html>  [ from 红梅 ]



## 210104-210109

> `本周轮值主编`：红梅 `下周轮值主编`：文玲

* [ 210108 ] 腾讯文档表格：大型前端项目架构优化探索之路 <https://mp.weixin.qq.com/s/_OWUjY4q9KkTjxrk59VJSg >   [ from 文玲 ]
    * 管理复杂的依赖关系
    * 支持异步依赖关系管理
    * 支持模块分层单向依赖
    * 支持模块全生命周期管理
* [ 210107 ]  探秘 flex 上下文中神奇的自动 margin  https://mp.weixin.qq.com/s/XxOdENyx9j_TNrmQJWYVCw  [ from 凌云 ]
* [ 201221 ] 强制锁定项目及node_modules下的依赖版本 http://gitlab.lvwan-inc.com/sophon-wiki/sophon-docs/blob/master/wangxuesong/sophon-web/dependent-version-change/index.md [ from 雪松 ]
* [ 201221 ] Depix 将打马赛克的文字还原 <https://github.com/beurtschipper/Depix />  [ from 君毅 ]
    *  the technique-of-choice is to pixelize similar data and check if it matches
* [ 210108 ] CSS mask遮罩 <https://juejin.cn/post/6915269572018831374> [ from 雪松 ]
    * 详细：https://blog.csdn.net/qq_44607694/article/details/90551133
* [ 200107 ] <http://www.alloyteam.com/2021/01/15358/>   前端资源加载失败优化 [ from 良辰 ]
* [ 200107 ] 剖析 lottie-web 动画实现原理 <https://segmentfault.com/a/1190000038863374> [ from 红梅 ]
