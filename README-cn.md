# awesome-android-architecture [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Android架构相关的优秀资源合集

## 架构指南

- [android-architecture  ——by Google](https://github.com/googlesamples/android-architecture) 
![star](http://githubbadges.com/star.svg?user=googlesamples&repo=android-architecture)
![fork](http://githubbadges.com/fork.svg?user=googlesamples&repo=android-architecture&style=flat&color=fff&background=007ec6)  
Google官方提供的一个各种Android优秀架构的代码实现集合（都是实现一个TODO备忘录App），并提供[架构之间的对比，与适用的场景](https://github.com/googlesamples/android-architecture/wiki/Samples-at-a-glance)

- [android-best-practices](https://github.com/futurice/android-best-practices) 
![star](http://githubbadges.com/star.svg?user=futurice&repo=android-best-practices)
![fork](http://githubbadges.com/fork.svg?user=futurice&repo=android-best-practices&style=flat&color=fff&background=007ec6)  
Android开发过程中的注意事项，包括架构设计中的各种坑

## MVP架构

### MVP 框架

- [EasyMVP](https://github.com/6thsolution/EasyMVP) 
![star](http://githubbadges.com/star.svg?user=6thsolution&repo=EasyMVP)
![fork](http://githubbadges.com/fork.svg?user=6thsolution&repo=EasyMVP&style=flat&color=fff&background=007ec6)  
一个帮助搭建MVP的全功能框架，并实现Clean架构的原则。[项目主页](http://6thsolution.github.io/EasyMVP/)

- [mosby](https://github.com/sockeqwe/mosby) 
![star](http://githubbadges.com/star.svg?user=sockeqwe&repo=mosby)
![fork](http://githubbadges.com/fork.svg?user=sockeqwe&repo=mosby&style=flat&color=fff&background=007ec6)  
一个Model-View-Presenter框架。[项目主页](http://hannesdorfmann.com/mosby/)

- [T-MVP](https://github.com/north2014/T-MVP) 
![star](http://githubbadges.com/star.svg?user=north2014&repo=T-MVP)
![fork](http://githubbadges.com/fork.svg?user=north2014&repo=T-MVP&style=flat&color=fff&background=007ec6)  
泛型深度解耦下的MVP大瘦身，为你的项目减少一半代码。（新增apt初始化工厂，替换掉了dagger2。新增aop切片，处理缓存和日志）

- [MVPArms](https://github.com/JessYanCoding/MVPArms) 
![star](http://githubbadges.com/star.svg?user=JessYanCoding&repo=MVPArms)
![fork](http://githubbadges.com/fork.svg?user=JessYanCoding&repo=MVPArms&style=flat&color=fff&background=007ec6)  
一个整合了大量主流开源项目的Android Mvp快速搭建框架, 其中包含 Dagger2, Retrofit, Rxjava以及Rxbinding, RxLifeCycle，RxCache等Rx系三方库, 并且提供UI自适应方案AutoLayot, 本框架将它们全部使用 Dagger2 管理。图片层采用策略模式封装 Glide, Picasso, Fresco。数据层提供一个CacheManager, 有其他需求的可以自己使用数据库实现缓存逻辑并替换.

- [TheMVP](https://github.com/kymjs/TheMVP) 
![star](http://githubbadges.com/star.svg?user=kymjs&repo=TheMVP)
![fork](http://githubbadges.com/fork.svg?user=kymjs&repo=TheMVP&style=flat&color=fff&background=007ec6)  
TheMVP使用Activity作为Presenter层来处理代码逻辑，通过让Activity包含一个ViewDelegate对象来间接操作View层对外提供的方法，从而做到完全解耦视图层

### MVP 案例

- [EffectiveAndroidUI](https://github.com/pedrovgs/EffectiveAndroidUI) 
![star](http://githubbadges.com/star.svg?user=pedrovgs&repo=EffectiveAndroidUI)
![fork](http://githubbadges.com/fork.svg?user=pedrovgs&repo=EffectiveAndroidUI&style=flat&color=fff&background=007ec6)  
MVP 和 MVVM(没有用databinding) 的优秀实践项目

- [androidmvp](https://github.com/antoniolg/androidmvp) 
![star](http://githubbadges.com/star.svg?user=antoniolg&repo=androidmvp)
![fork](http://githubbadges.com/fork.svg?user=antoniolg&repo=androidmvp&style=flat&color=fff&background=007ec6)  
一个简单的 MVP 项目，不过挺经典的

- [UpcomingMoviesMVP](https://github.com/jlmd/UpcomingMoviesMVP) 
![star](http://githubbadges.com/star.svg?user=jlmd&repo=UpcomingMoviesMVP)
![fork](http://githubbadges.com/fork.svg?user=jlmd&repo=UpcomingMoviesMVP&style=flat&color=fff&background=007ec6)  
一个电影列表App, 运用 MVP 和 Material Design。两年没更了，有些过时

### MVP 结合 Clean

- [MvpCleanArchitecture](https://github.com/glomadrian/MvpCleanArchitecture) 
![star](http://githubbadges.com/star.svg?user=glomadrian&repo=MvpCleanArchitecture)
![fork](http://githubbadges.com/fork.svg?user=glomadrian&repo=MvpCleanArchitecture&style=flat&color=fff&background=007ec6)  
一个运用Clean架构和MVP的DEMO

- [EffectiveAndroid](https://github.com/rallat/EffectiveAndroid) 
![star](http://githubbadges.com/star.svg?user=rallat&repo=EffectiveAndroid)
![fork](http://githubbadges.com/fork.svg?user=rallat&repo=EffectiveAndroid&style=flat&color=fff&background=007ec6)  
如何应用 MVP 和 Clean 架构的实例

### MVP 结合 RxJava

- [MVP-RxJava-Hybride](https://github.com/youxin11544/MVP-RxJava-Hybride) 
![star](http://githubbadges.com/star.svg?user=youxin11544&repo=MVP-RxJava-Hybride)
![fork](http://githubbadges.com/fork.svg?user=youxin11544&repo=MVP-RxJava-Hybride&style=flat&color=fff&background=007ec6)  
这是一个Android MVP模型良好的架构设计,同时也做了Android和HTML 5交互架构，用到了RxJava+Retrofit+MVP+泛型缩减mvp+模板模式+命令模式+观察者模式+管理者模式 +简单工厂模式

- [GeekNews](https://github.com/codeestX/GeekNews) 
![star](http://githubbadges.com/star.svg?user=codeestX&repo=GeekNews)
![fork](http://githubbadges.com/fork.svg?user=codeestX&repo=GeekNews&style=flat&color=fff&background=007ec6)  
极客日报，一款纯粹的阅读App，基于Material Design + MVP + RxJava + Retrofit + Dagger2 + Realm + Glide.

- [Elephant](https://github.com/Freelander/Elephant) 
![star](http://githubbadges.com/star.svg?user=Freelander&repo=Elephant)
![fork](http://githubbadges.com/fork.svg?user=Freelander&repo=Elephant&style=flat&color=fff&background=007ec6)  
大象是 PHPHub 社区非官方 Android 客户端, App UI 风格遵循了 Google Material Design 设计风格, 项目架构使用了 MVP 模式, 数据处理使用了 RxJava + Retrofit 技术.

- [TLint](https://github.com/gzsll/TLint) 
![star](http://githubbadges.com/star.svg?user=gzsll&repo=TLint)
![fork](http://githubbadges.com/fork.svg?user=gzsll&repo=TLint&style=flat&color=fff&background=007ec6)  
TLint for 虎扑体育 基于Dagger2+RxJava+Retrofit开发，采用MVP模式

- [Ghost](https://github.com/GeekGhost/Ghost) 
![star](http://githubbadges.com/star.svg?user=GeekGhost&repo=Ghost)
![fork](http://githubbadges.com/fork.svg?user=GeekGhost&repo=Ghost&style=flat&color=fff&background=007ec6)  
微影，一款纯粹的在线视频App，基于Material Design + MVP + RxJava + Retrofit + Realm + Glide


## Clean架构

- [Android-CleanArchitecture](https://github.com/android10/Android-CleanArchitecture) 
![star](http://githubbadges.com/star.svg?user=android10&repo=Android-CleanArchitecture)
![fork](http://githubbadges.com/fork.svg?user=android10&repo=Android-CleanArchitecture&style=flat&color=fff&background=007ec6)  
这是一个关于如何在Android项目中实现 “Uncle Bob Clean架构” 系列博客的示例App

 + [Android 架构 —— Clean的方式?](http://fernandocejas.com/2014/09/03/architecting-android-the-clean-way/)
 + [Android 架构 —— 演变](http://fernandocejas.com/2015/07/18/architecting-android-the-evolution/)
 + [Dagger2 在 Android 中的尝试](http://fernandocejas.com/2015/04/11/tasting-dagger-2-on-android/)
 + [Demo 示例视频](http://youtu.be/XSjV4sG3ni0)

## Fragment 相关架构

### Fragment 辅助

- [Fragmentation](https://github.com/YoKeyword/Fragmentation) 
![star](http://githubbadges.com/star.svg?user=YoKeyword&repo=Fragmentation)
![fork](http://githubbadges.com/fork.svg?user=YoKeyword&repo=Fragmentation&style=flat&color=fff&background=007ec6)  
为"单Activity ＋ 多Fragment","多模块Activity + 多Fragment"架构而生，帮你大大简化使用过程，轻松解决各种复杂嵌套等问题，修复了官方Fragment库中存在的一些BUG。


## 参考

- [Awesome-Android-Architecture](https://github.com/Juude/Awesome-Android-Architecture)
![star](http://githubbadges.com/star.svg?user=Juude&repo=Awesome-Android-Architecture)
![fork](http://githubbadges.com/fork.svg?user=Juude&repo=Awesome-Android-Architecture&style=flat&color=fff&background=007ec6)  
Android架构合集

- [AndroidArchitectureCollection](https://github.com/CameloeAnthony/AndroidArchitectureCollection)
![star](http://githubbadges.com/star.svg?user=CameloeAnthony&repo=AndroidArchitectureCollection)
![fork](http://githubbadges.com/fork.svg?user=CameloeAnthony&repo=AndroidArchitectureCollection&style=flat&color=fff&background=007ec6)  
安卓架构文章合集

