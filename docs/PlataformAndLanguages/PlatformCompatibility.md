# Platform Compatibility and Proposal Status

## Web
  * Platform Status
    * [Can I Use](http://caniuse.com/)
    * [Chrome](https://www.chromestatus.com/features), [WebKit](https://webkit.org/status/), [Firefox](https://platform-status.mozilla.org/), [Edge](https://developer.microsoft.com/en-us/microsoft-edge/platform/status/), [TBS (China)](http://x5.tencent.com/tbs/guide/w3c.html)
  * Platform Releases
    * [Chrome](https://chromereleases.googleblog.com/), [Safari](https://developer.apple.com/safari/whats-new/) ([Webkit](https://trac.webkit.org/)), [Firefox](https://www.mozilla.org/en-US/firefox/releases/), [Edge](https://developer.microsoft.com/en-us/microsoft-edge/platform/changelog/)
  * Platform Updates
    * [Mozilla Hacks](https://hacks.mozilla.org/)
    * [Web Updates](https://developers.google.com/web/updates/), [Chromium Blog](https://blog.chromium.org/)
    * [Webkit Blog](https://webkit.org/blog/)
    * [Microsoft Edge Dev Blog](https://developer.microsoft.com/en-us/microsoft-edge/community/)
  * [Writing forward-compatible websites](https://developer.mozilla.org/en-US/docs/Web/Guide/Writing_forward-compatible_websites)
    * Polyfill - [What is a Polyfill?](https://remysharp.com/2010/10/08/what-is-a-polyfill)
    * Feature Detection - [Modernizr/feature-detects](https://github.com/Modernizr/Modernizr/tree/master/feature-detects), [feature.js](https://github.com/viljamis/feature.js/blob/master/feature.js)
    * Browser/Device/Runtime Detection - see _[Platforms and Languages > Universal Utility Libraries](#universal-utility-libraries) > Parsing / Manipulating_
    * [Graded Browser Support](https://github.com/yui/yui3/wiki/Graded-Browser-Support) - [Grade components, not browsers](https://www.filamentgroup.com/lab/grade-the-components.html)
  * Email
    * [CSS Support Guide for Email Clients](https://www.campaignmonitor.com/css/) / [Email Client CSS Support](https://templates.mailchimp.com/resources/email-client-css-support/)
    * [Email Design Reference](https://templates.mailchimp.com/) + [HTML Email Templates](https://github.com/mailchimp/Email-Blueprints)
## Node.js
  * Platform Releases
    * [Node.js Release Working Group](https://github.com/nodejs/Release)
## ECMAScript Support
  * [ECMAScript compatibility table](http://kangax.github.io/compat-table/es6/)
  * [Node.js ES2015+ Support](http://node.green/)
    * Node 10.x LTS - Supports ES modules natively (without `--experimental-modules`)
    * [Node.8.5](https://nodejs.org/en/blog/release/v8.5.0/) - Supports ES modules natively (`.mjs` + `--experimental-modules`)
    * [Node 8.3](https://nodejs.org/en/blog/release/v8.3.0/) - [V8 6.0](https://v8project.blogspot.hk/2017/04/v8-release-59.html), [Ignition + Turbofan launched](https://v8project.blogspot.hk/2017/05/launching-ignition-and-turbofan.html)
    * [Node 8.0 LTS](https://nodejs.org/en/blog/release/v8.0.0/) - [V8 5.8](https://v8project.blogspot.hk/2017/03/v8-release-58.html), [Five New Features You Need To Know](http://codingsans.com/blog/node-8)
    * [Node 7.6](https://nodejs.org/en/blog/release/v7.6.0/) - [V8 5.5](https://v8project.blogspot.hk/2016/10/v8-release-55.html), Async functions
    * [Node 6.0 LTS](https://nodejs.org/en/blog/release/v6.0.0/) - [V8 5.0](https://v8project.blogspot.hk/2016/03/v8-release-50.html), 93% of ES6 language features
  * Performance - [Six Speed](https://kpdecker.github.io/six-speed/)
## Proposal Status
  * [W3C WG](https://www.w3.org/Consortium/activities#Working) (World Wide Web Consortium Working Groups)
    * [Web Platform Publication Status](https://www.w3.org/WebPlatform/WG/PubStatus)
      * [JavaScript APIs](https://www.w3.org/standards/techs/js), [Mobile Web Applications](https://www.w3.org/standards/techs/mobileapp), [CSS](https://www.w3.org/standards/techs/css)
    * [CSS current work](https://www.w3.org/Style/CSS/current-work)
    * [Current HTML5 Specifications](http://html5-overview.net/current)
    * Inside
      * [W3C TR (Technical Reports)](https://www.w3.org/2014/Process-20140801/#rec-advance)
      * [An Inside View of the CSS Working Group at W3C](http://fantasai.inkedblade.net/weblog/2011/inside-csswg/)
  * [WICG](https://wicg.github.io/admin/charter.html) (Web Incubator Community Group)
    * [Proposals](https://github.com/WICG)
  * [WHATWG](https://whatwg.org/faq) (Web Hypertext Application Technology Working Group)
    * [WHATWG Live Standards](https://spec.whatwg.org/)
    * Inside
      * [W3C vs. WHATWG HTML5 Specs – The Differences Documented](http://developer.telerik.com/featured/w3c-vs-whatwg-html5-specs-differences-documented/)
  * [ECMA TC39](http://ecma-international.org/memento/TC39.htm) (Ecma International Technical Committee 39)
    * [Status, process, and documents for ECMA262](https://github.com/tc39/ecma262)
      * [ECMAScript Proposals](https://github.com/tc39/proposals) / [TC39 Proposals](https://prop-tc39.now.sh/)
    * Inside
      * [The TC39 Process](http://tc39.github.io/process-document/) / [The TC39 process for ECMAScript features](http://2ality.com/2015/11/tc39-process.html)
  * [Node.js TSC](https://github.com/nodejs/TSC) (Node.js Foundation Technical Steering Committee)
    * [Meeting Notes](https://github.com/nodejs/TSC/tree/master/meetings)
    * Inside
      * [How Node.js created a model open source community](https://readwrite.com/2016/04/15/how-node-js-model-open-source-community-pl1/)
      * [Healthy Open Source](https://medium.com/the-node-js-collection/healthy-open-source-967fa8be7951)
## JS Engine
  * [A Guide to JavaScript Engines for Idiots](http://developer.telerik.com/featured/a-guide-to-javascript-engines-for-idiots/)
  * [V8](https://developers.google.com/v8/)
    * [How the V8 engine works?](http://thibaultlaurens.github.io/javascript/2013/04/29/how-the-v8-engine-works/)
    * Internal
      * [v8: a tale of two compilers](https://wingolog.org/archives/2011/07/05/v8-a-tale-of-two-compilers), \
        [A tour of V8: full compiler](http://jayconrod.com/posts/51/a-tour-of-v8-full-compiler)
      * [A tour of V8: Garbage Collection](http://jayconrod.com/posts/55/a-tour-of-v8-garbage-collection)
    * Next Generation
      * [Ignition + TurboFan launch and Declarative JavaScript](http://benediktmeurer.de/2017/04/03/v8-behind-the-scenes-march-edition/)
        * [Launching Ignition and TurboFan](https://v8project.blogspot.hk/2017/05/launching-ignition-and-turbofan.html)
        * [A tale of TurboFan](http://benediktmeurer.de/2017/03/01/v8-behind-the-scenes-february-edition/)
      * [Ignition + TurboFan and ES2015](http://benediktmeurer.de/2016/11/25/v8-behind-the-scenes-november-edition/)
  * [JSC](https://trac.webkit.org/wiki/JavaScriptCore)
    * [JavaScriptCore, the WebKit JS implementation](https://wingolog.org/archives/2011/10/28/javascriptcore-the-webkit-js-implementation)
    * Internal
      * [Introducing the WebKit FTL JIT](https://webkit.org/blog/3362/introducing-the-webkit-ftl-jit/)
    * Next Generation
      * [JSC Love ES6](https://webkit.org/blog/7536/jsc-loves-es6/)
      * [Introducing the B3 JIT Compiler](https://webkit.org/blog/5852/introducing-the-b3-jit-compiler/)
  * [Chakra](https://github.com/Microsoft/ChakraCore)
    * [Microsoft Edge’s JavaScript engine to go open-source](https://blogs.windows.com/msedgedev/2015/12/05/open-source-chakra-core/)
    * [Architecture Overview](https://github.com/Microsoft/ChakraCore/wiki/Architecture-Overview)
    * [Node-ChakraCore and VM Neutrality in Node.js](https://blogs.windows.com/msedgedev/2016/11/29/node-chakracore-vm-neutrality/)
    * Internal
      * JavaScript performance updates - [2015](https://blogs.windows.com/msedgedev/2015/05/20/delivering-fast-javascript-performance-in-microsoft-edge), [2016](https://blogs.windows.com/msedgedev/2016/06/22/javascript-performance-updates-anniversary-update/), [2017](https://blogs.windows.com/msedgedev/2017/04/20/improved-javascript-performance-webassembly-shared-memory/)
    * Next Generation
      * [Roadmap](https://github.com/Microsoft/ChakraCore/wiki/Roadmap)
  * [SpiderMonkey](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey)
    * [The monkeys in 2013](https://blog.mozilla.org/javascript/2014/01/23/the-monkeys-in-2013/)
  * Benchmarks
    * [The truth about traditional JavaScript benchmarks](http://benediktmeurer.de/2016/12/16/the-truth-about-traditional-javascript-benchmarks/)
    * [Browser Benchmarks](http://browserbench.org/)
## Web Runtime / JS Runtime
  * [Electron](https://electron.atom.io/)
    * Tutorials - [Essential Electron](http://jlord.us/essential-electron/)
  * [Cordova](https://cordova.apache.org/)
    * [Platform Support](https://cordova.apache.org/docs/en/latest/guide/support/index.html)
    * [Top Mistakes by Developers new to Cordova/Phonegap](https://github.com/jessemonroy650/top-phonegap-mistakes/blob/master/new-to-Phonegap.md)
    * Curated Plugins - [Awesome Cordova Plugins](https://github.com/rdn87/awesome-cordova-plugins#list-plugins)
    * Finding Plugins - [plugreg](http://www.plugreg.com/) / [Plugin Search](https://cordova.apache.org/plugins/)
  * [React Native](http://facebook.github.io/react-native/) / [NativeScript](https://www.nativescript.org/) / [Weex](https://weex-project.io/)
    * [React Native Styling Cheat Sheet](https://github.com/vhpoet/react-native-styling-cheat-sheet)
    * [Bridging in React Native - An in-depth look into React Native's core](https://tadeuzagallo.com/blog/react-native-bridge/)
    * Tutorials - [React Native Express](http://www.reactnativeexpress.com/), [React Native Workshop](https://rangle-io.gitbooks.io/react-native-workshop/), [React Native Training](https://unbug.gitbooks.io/react-native-training/content/)
    * Examples - [30 Days of React Native](https://github.com/fangwei716/30-days-of-react-native)
## Device
  * [The Ultimate Guide To iPhone Resolutions](https://www.paintcodeapp.com/news/ultimate-guide-to-iphone-resolutions)
  * [Device Metrics](https://material.io/devices/) / [Screen Sizes](http://screensiz.es/monitor)

