# 学习 Web 浏览器

> Web浏览器 (通常被称为浏览器)是一个在万维网上检索、呈现、遍历信息资源的应用软件。信息资源是由统一资源标识符 (URI/URL) 来标识的，可以是网页、图片、视频或其他内容。资源中存在的超链接能够使用户轻松地将浏览器导航到相关资源。虽然浏览器主要目的是使用万维网，它们同样也可被用来获得专用网络中Web服务器所提供的信息，或者文件系统中的文件。

><cite>&#8212; [维基百科](https://en.wikipedia.org/wiki/Web_browser)</cite>


##### [最常用的浏览器](https://www.sitepoint.com/browser-trends-september-2016-browser-wars/) (任意设备上) 如下：

1. [Chrome](http://www.google.com/chrome/) (引擎: [Blink](https://en.wikipedia.org/wiki/Blink_%28layout_engine%29) + [V8](https://en.wikipedia.org/wiki/V8_%28JavaScript_engine%29))
2. [Firefox](https://www.mozilla.org/en-US/firefox/new/) (引擎: [Gecko](https://en.wikipedia.org/wiki/Gecko_%28software%29) + [SpiderMonkey](https://en.wikipedia.org/wiki/SpiderMonkey_%28software%29))
3. [Internet Explorer](http://windows.microsoft.com/en-us/internet-explorer/download-ie) (引擎: [Trident](https://en.wikipedia.org/wiki/Trident_%28layout_engine%29) + [Chakra](https://en.wikipedia.org/wiki/Chakra_%28JScript_engine%29))
4. [Safari](https://www.apple.com/safari/) (引擎: [Webkit](https://en.wikipedia.org/wiki/WebKit) + [SquirrelFish](https://trac.webkit.org/wiki/SquirrelFish))

![](../images/statcounter.png "http://gs.statcounter.com/#all-browser_version_partially_combined-ww-daily-20160101-20161201-bar")

<cite>图片来源: <a href="http://gs.statcounter.com/#all-browser_version_partially_combined-ww-daily-20160101-20161201-bar">http://gs.statcounter.com/#all-browser_version_partially_combined-ww-monthly-201501-201601-bar</a></cite>

##### 浏览器和Web技术的演进 （即API）：

* [evolutionoftheweb.com](http://www.evolutionoftheweb.com/) [阅读]
* [Web浏览器的时间轴](https://en.wikipedia.org/wiki/Timeline_of_web_browsers) [阅读]

##### 最常用的Headless(无GUI)浏览器：

* [PhantomJS](http://phantomjs.org/) (引擎: [Webkit](https://en.wikipedia.org/wiki/WebKit) + SquirrelFish)
* [SlimerJS](http://slimerjs.org/) (引擎: [Gecko](https://en.wikipedia.org/wiki/Gecko_%28software%29) + [SpiderMonkey](https://en.wikipedia.org/wiki/SpiderMonkey_%28software%29))
* [TrifleJS](http://triflejs.org/) (引擎: [Trident](https://en.wikipedia.org/wiki/Trident_%28layout_engine%29) + [Chakra](https://en.wikipedia.org/wiki/Chakra_%28JScript_engine%29))

##### 浏览器是如何工作的：

* [了解关于浏览器和 Web 的20件事情](http://www.20thingsilearned.com/en-US/foreword/1) [阅读]
* [加速你的CSS：浏览器如何布局网页](http://dbaron.org/talks/2012-03-11-sxsw/master.xhtml) [阅读]
* [浏览器如何工作：现代浏览器的幕后原理](http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/) [阅读]
* [浏览器是如何真正渲染一个网站的？](https://www.youtube.com/watch?v=SmE4OwHztCc) [观看]
* [什么会触发布局和重排](https://gist.github.com/paulirish/5d52fb081b3570c81e3a) [阅读]
* [每位前端开发者必须知道的网页渲染技能](http://frontendbabel.info/articles/webpage-rendering-101/) [阅读]

![](../images/browsers-work.png "http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/")

<cite>图片来源: <a href="http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/">http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/</a></cite>

##### 浏览器优化

* [浏览器渲染优化](https://www.udacity.com/course/browser-rendering-optimization--ud860) [观看]
* [网站性能优化](https://www.udacity.com/course/website-performance-optimization--ud884) [观看]

##### 对比浏览器

* [Web浏览器的比较](https://en.wikipedia.org/wiki/Comparison_of_web_browsers) [阅读]

##### 浏览器 Hacks

* [browserhacks.com](http://browserhacks.com/) [阅读]

##### 浏览器开发

在过去，前端开发者要花费很多时间写代码来兼容几种不同浏览器。 与现在相比，这曾是一个巨大的问题。现在，第三方工具（例如：jQuery、React、 Post-CSS、Babel等等）结合现代浏览器使得浏览器开发相当容易。新的挑战不是用户使用哪个浏览器，而是他们选择哪种设备运行浏览器。

##### 浏览器中的常青树

大多数现代浏览器的最新版本被认为是常青浏览器。也就是说，从理论上讲他们应该不需要用户操作自动更新。自动更新浏览器的这一举措已经反过来淘汰了不自动更新的旧版浏览器。

##### 选择浏览器 [^1]

如今，大多数前端开发人员使用Chrome和“Chrome”开发工具”开发前端代码。然而，最常用的现代浏览器都提供开发工具。使用哪个用于开发是一个主观的选择。最重要的问题是了解你必须支持哪个浏览器，哪个设备，然后适当地进行测试。

***

###### 建议：

[^1]我建议使用Chrome，因为它的开发者工具在持续改进，并且包含了最强大的功能。

























