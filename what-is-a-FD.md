# 前端开发者是什么？

> WEB前端开发，亦称作客户端开发，是为网站或网页应用生产 HTML、CSS 和 JavaScript 的实践，这样能让用户能直接看见网站或网页应用并与之交互。与前端开发相关的挑战在于：创建网站前端的工具与技术时常变革，因此开发者需要时常对行业内的发展近况保持清醒。

> 设计网站的目的是：确保用户在打开网站时，以一种易读且相关联的形式浏览信息。这件事情在目前的现状下变得更为棘手：如今用户使用的设备种类繁多，设备对应的屏幕尺寸和方案亦然，这迫使设计者需在开发站点时考虑这些方面。他们要保证站点在不同的浏览器（跨浏览器），不同的操作系统（跨平台）以及不同的设备（跨设备）上正确运行，这要求开发者缜密地制定方案。 

><cite>https://en.wikipedia.org/wiki/Front-end_web_development</cite>


## HTML、CSS 和 JavaScript:

一个前端开发者使用 WEB 技术（例如 HTML、CSS、 DOM 和 JavaScript）来建造和开发网站与应用。这些 WEB 技术运行在 [WEB 平台](https://en.wikipedia.org/wiki/Open_Web_Platform) 或作为非 WEB 系统环境（比如 [NativeScript](https://www.nativescript.org/)）的编译输入。

![what-is-front-end-dev](./images/what-is-front-end-dev.png)

图片来源：[https://www.upwork.com/hiring/development/front-end-developer/](https://www.upwork.com/hiring/development/front-end-developer/)

通常前端开发者通过学习开发 HTML、CSS 和 JS 代码进入前端开发领域。HTML、CSS 和 JS 代码运行在 [WEB 浏览器](https://en.wikipedia.org/wiki/Web_browser)，[无头浏览器（Headless Browsers）](https://en.wikipedia.org/wiki/Headless_browser)，[WebView](http://developer.telerik.com/featured/what-is-a-webview/) 或作为一个原生运行环境的编译输入。我将在稍后解释这四种运行场景。

### WEB 浏览器

WEB 浏览器是用于从[万维网（WWW.）](https://en.wikipedia.org/wiki/World_Wide_Web)检索、呈现和遍历信息的软件。通常浏览器运行在台式、笔记本、平板或手机上，现如今，浏览器可以运行在几乎所有物体（比如冰箱，汽车）上。

最常见的 WEB 浏览器如下（按使用度排序）：
- [Chrome]()
- [IE](https://en.wikipedia.org/wiki/Internet_Explorer)（注：非 [Edge](https://en.wikipedia.org/wiki/Internet_Explorer)，参考自 IE 9 至 IE 11）
- [火狐](https://www.mozilla.org/firefox/)
- [Safari](http://www.apple.com/safari/)

### 无头浏览器（Headless Browsers）

无头浏览器是一种没有用户图形界面的 WEB 浏览器，我们可以通过命令行界面以编程的方式控制该浏览器，用来自动化 Web 页面（比如功能测试、网站检索、单元测试等）。你可以将无头浏览器看作是可供命令行运行来检索、遍历网页的浏览器。

最常见的无头浏览器：
- [PhantomJS](http://phantomjs.org/)
- [slimerjs](http://slimerjs.org/)
- [trifleJS](http://triflejs.org/)

### Webviews

原生操作系统的原生应用中，用 [Webviews](http://developer.telerik.com/featured/what-is-a-webview/) 来运行网页。不妨把 [webview](http://developer.telerik.com/featured/what-is-a-webview/) 想成一个嵌进原生应用的 iframe 或 WEB 浏览器标签，而该原生应用运行在一个设备系统上（比如 IOS、安卓、windows）。

最常见的 webview 开发解决方案如下：
- [Cordova](https://cordova.apache.org/) (通常用于手机、平板的原生应用)
- [NW.js](https://github.com/nwjs/nw.js) (通常用于桌面应用)
- [Electron](https://github.com/nwjs/nw.js) (通常用于桌面应用)

### 基于 WEB 技术的原生应用

最终，前端开发者可以用从 WEB 浏览器开发中学到的东西来编写非浏览器引擎环境的代码。近来，人们正在构思摆脱 web 引擎，运用 web 技术（比如 CSS 和 JS）来构建原生应用。

该种环境的几个例子：
- [NativeScript](https://www.nativescript.org/)
- [React Native](https://facebook.github.io/react-native/)

## 注：

请确认一下你真正明白 “web platform” 的准确含义。查看[ “The Web platform: what it is” ](http://tess.oconnor.cx/2009/05/what-the-web-platform-is) ，同时查看维基百科 [ “Open Web Platform” ](https://en.wikipedia.org/wiki/Open_Web_Platform)
