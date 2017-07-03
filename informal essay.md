#### 一. 浏览器与浏览器内核
1. Trident 内核(代表：Internet Exploer),又称IE内核。

    * Trident(又称为MSHTML)，是微软开发的一种排版引擎。
    * 除IE外，许多产品都在使用Trident核心，比如Windows的Help程序、RealPlayer、Windows Media Player、Windows Live Messenger、Outlook Express等等都使用了Trident技术。
    * Trident实际上是一款开放的内核，Trident引擎被设计成一个软件模块，其接口设计成熟，其他软件开发人员可以很容易的将网页浏览功能加到他们自行开发的应用程序中。所以有许多采用IE内核而非IE的浏览器。
    * Trident只能用于Windows平台
    * 使用Trident渲染引擎的浏览器包括：IE、傲游、世界之窗浏览器、Avant、腾讯TT、Sleipnir、GOSURF、GreenBrowser和KKman等。
2. Gecko 内核(代表：Mozilla Firefox)
    * Gecko 是开放源代码，以C++编写的网页排版引擎，由网景公司开发，现在由Mozilla基金会维护。
    * 特点：开源，代码完全公开，可开发程度很高
    * Gecko是一个跨平台内核，可以在Windows.BSD.Linux和Mac OS X中使用
    * 正在和曾经使用Gecko引擎的浏览器有Firefox、网景6～9、SeaMonkey、Camino、Mozilla、Flock、Galeon、K-Meleon、Minimo、Sleipni、Songbird、XeroBank。Google Gadget引擎采用的就是Gecko浏览器引擎。
3. Webkit 内核(代表：Safari.Chrome)
    * Webkit是一个开源浏览器引擎，最初代码来自KDE的KHTML和KJS
    * 特点：源码结构清晰，渲染速度极快。代表：Safari 和 Google浏览器 Chrome。
    * WebKit内核在手机上应用也十分广泛。例如Google的Android平台浏览器、Apple的iPhone浏览器、Nokia S60浏览器等所使用的浏览器内核引擎，都是基于WebKit引擎的。 
    * WebKit内核也广泛应用于Widget引擎产品，包括中国移动的BAE、Apple的Dashboard以及Nokia WRT在内采用的均为WebKit引擎。
4. Presto内核(代表：Opera)
    * Presto是由Opera Software开发的浏览器排版引擎。
    * Presto是一个动态内核，与Trident和Gecko最大的区别在于脚本处理上，页面的全部或者部分可以在回应脚本事件时被重新解析。
    * Presto是公认的网页浏览速度最快的浏览器内核，代价是牺牲了网页的兼容性。
    * 解析JavaScript速度最快，同等条件下测试执行JavaScript事件仅是Trident和Gecko的1／3.
    * Presto是商业引擎，除了Opera较少浏览器使用Presto内核
