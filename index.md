# 技术快报

> 业界技术跟进，不限于前端技术，按时间逆序梳理，每周一份，[轮值主编制度参考](./editors.md)


## 210118-200123

> `本周轮值主编`：君毅 `下周轮值主编`：晓朋

> 干货

* [ 210120 ] 2020 中国开源年度报告 <https://juejin.cn/post/6919729106779275272>  [ from 文玲 ]
    * 开源大发展以及由实向虚进发的趋势
    * 中国开源崛起以及开源世界分裂的趋势
    * 开源向善以及我们尚未做好准备
* [ 210121 ] 图可视化之图布局 <https://segmentfault.com/a/1190000039054038>  [ from 红梅 ]
    * 主要探讨了各种不同场景的布局解决方案

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
