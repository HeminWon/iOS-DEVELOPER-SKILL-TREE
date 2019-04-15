clang / objc runtime / 类对象 / 元类对象 / 动态方法添加 / 动态方法解析 / objc_object / objc_class / isa指针 / method_t

#### questions
- 编译型语言与objc这种动态类型语言之间的区别是什么？
- 消息传递与函数调用有怎样的区别？
- 当我们调用一个方法类没有实现的时候系统是如何为我们进行消息转发过程的？
- 类对象与元类对象分别代表什么，以及实例与类对象之间的关系，以及元类对象与类对象之间的关系？
- OC语言中的消息传递机制是怎样的？
- 当我们进行消息传递的过程中，如何进行缓存的方法查找？
- 消息转发流程是怎样的？
- Method-Swizzing是什么？

#### 应用场景
- [OC-RunTime: 总结消息转发中用到的知识点](http://www.veryitman.com/2018/04/05/OC-RunTime-%E6%80%BB%E7%BB%93%E6%B6%88%E6%81%AF%E8%BD%AC%E5%8F%91%E4%B8%AD%E7%94%A8%E5%88%B0%E7%9A%84%E7%9F%A5%E8%AF%86%E7%82%B9/) by veryitman
- [iOS知识点-Runtime](http://blog.91renb.com/p/20180121-ios-runtime.html) by 91renb 
- [Objective-C Method Swizzling 的最佳实践](http://blog.leichunfeng.com/blog/2015/06/14/objective-c-method-swizzling-best-practice/) by leichunfeng
- [Method Swizzling的各种姿势](http://www.tanhao.me/code/160723.html/) by tanhao
- [探究使用Method Swizzling的正确姿势](https://shixiong.name/2019/03/01/the-right-way-to-swizzling/index.html) by shixiong

#### 参考文章
article list | abstract
:-- | :--:
[Runtime--Runtime的数据结构(一)](https://xiaopengmonsters.github.io/2017/08/16/Runtime--%E7%B1%BB%E5%AF%B9%E8%B1%A1%E4%B8%8E%E5%85%83%E7%B1%BB%E5%AF%B9%E8%B1%A1/) by 怪兽 | ★★★★ |
[Objective-C Runtime](http://yulingtianxia.com/blog/2014/11/05/objective-c-runtime/) by yulingtianxia |
[Objective-C Runtime —— 基础数据结构](https://juejin.im/post/5afea0056fb9a07aa34a8187) by Beyond__JG |
[iOS Runtime之一：Class和meta-class](https://imlifengfeng.github.io/article/390/) by imlifengfeng |
[谈Runtime机制和使用的整体化梳理](https://www.jianshu.com/p/8916ad5662a2) by minggo |
[IOS 面试题: 对 RUNTIME 的理解](https://meniny.cn/posts/iOS_knowledge_018/) by meniny |
[可能碰到的iOS笔试面试题（22）--Runtime](https://www.jianshu.com/p/82860fd8222c) by 谈笑风生Smile |
[runtime - iOS类对象、实例对象、元类对象](https://www.jianshu.com/p/40c0ca04fb20) by GiseriOS |
[Objective-C Runtime 运行时之一：类与对象](http://southpeak.github.io/2014/10/25/objective-c-runtime-1/) by southpeak |
[重识 Objective-C Runtime - 看透 Type 与 Value](http://blog.sunnyxx.com/2016/08/13/reunderstanding-runtime-1/) by sunnyxx |
[iOS 模块详解—「Runtime面试、工作」看我就 🐒 了 ^_^.](https://juejin.im/entry/590832eb5c497d00584ddcb7) by CoderLN |
[从 NSObject 的初始化了解 isa](https://draveness.me/isa) by draveness |
[Objective-C NSInvocation](https://ace.re/2017/objective-c-nsinvocation.html) by ace |
[Associated Objects](https://nshipster.cn/associated-objects/) by nshipster |
[Objective-C Associated Objects 的实现原理](http://blog.leichunfeng.com/blog/2015/06/26/objective-c-associated-objects-implementation-principle/) by leichunfeng |