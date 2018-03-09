# 自己使用的三方库整理记录

| 名字|作用|备注|
|:----|:----|:----|
|[OpenUDID](https://github.com/ylechelle/OpenUDID)|用来生成UUID，在应用第一次启动时调用一 次，然后将该串存储起来，替代UDID来使用。保存在iOS系统里面，如果应用删除了，重装应用之后它的UUID还是一样的，除非系统重置 。|最近一次提交：2013.6.8|
|[urlmanager](https://github.com/gaosboy/urlmanager)|路由跳转的一个库，将每一个控制器作为一个跳转的url|我觉得这个库并不怎么好用，刚开始用起来还可以，等业务复杂的时候，这个库就会搞得耦合性非常大。Star：361|
|[TTTAttributedLabel](https://github.com/TTTAttributedLabel/TTTAttributedLabel)|一个富文本处理库|最近一个提交：2016.11.18|
|[STModalDemo](https://github.com/zhenlintie/STModalDemo)|自定义弹出视图（通知，提示，选择，窗口）|前期引入，后期就去掉了，自己写了一套|
|[TMCache](https://github.com/tumblr/TMCache)|一个数据缓存库|最近一次提交：2015.4.24。建议使用其他库代替|
|[Reachability](https://github.com/tonymillion/Reachability)|一个网络状态监测库|其实苹果也有一个，建议使用[苹果官方](https://developer.apple.com/library/content/samplecode/Reachability/Introduction/Intro.html)的|
|[CrashReporter](https://github.com/ashikase/CrashReporter)|崩溃日志收集库|最近一次提交：2018.2.3|
|[razor](https://github.com/cobub/razor)|用户埋点上传统计库|最近一次提交：2016.7.22|
|[WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge)|一个用于网页（JS代码）和本地代码（OC代码）交互的库||
|[SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh)|一个下拉刷新，上拉加载库|说实话，不怎么好用。|
|[Aspects](https://github.com/steipete/Aspects)|切面编程，使用Runtime进行拦截方法，处理业务的库|这个库还是挺好用的，适用于写一些框架的业务，耦合性小|
