### Workflow

* Development
  * Micro Generator
    * [Plop](https://plopjs.com)
  * Live Reload / Watch / Preview
    * [webpack-serve](https://github.com/webpack-contrib/webpack-serve)
    * [webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server)
      * [webpack-dashboard](https://www.npmjs.com/package/webpack-dashboard)
      * [webpack-dev-middleware](https://www.npmjs.com/package/webpack-dev-middleware)
    * [Hot Module Replacement](https://webpack.js.org/guides/hot-module-replacement/) / [React Hot Loader](http://gaearon.github.io/react-hot-loader/)
    * [Browsersync](https://www.npmjs.com/package/browser-sync)
    * Electron - [Electron Connect](https://www.npmjs.com/package/electron-connect)
    * React Native - [Expo](https://expo.io/)
    * Node.js - [nodemon](https://www.npmjs.com/package/nodemon)
  * Dev Tools
    * [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/) / [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools) / [Safari Web Inspector](https://developer.apple.com/library/content/documentation/AppleApplications/Conceptual/Safari_Developer_Guide/) / [Microsoft Edge F12 Dev Tools](https://docs.microsoft.com/en-us/microsoft-edge/f12-devtools-guide)
      * Console - [Console API](https://developers.google.com/web/tools/chrome-devtools/console/console-reference), [Command Line API](https://developers.google.com/web/tools/chrome-devtools/console/command-line-reference)
    * Third-party Panels
      * [React DevTools](https://github.com/facebook/react-devtools) / [AngularJS Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) / [Augury](https://chrome.google.com/webstore/detail/augury/elgalmkoelokbchhkhacckoklkejnhcd) / [Vue.js DevTools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)
      * [React Perf](https://chrome.google.com/webstore/detail/react-perf/hacmcodfllhbnekmghgdlplbdnahmhmm)
      * [Redux DevTools](https://github.com/gaearon/redux-devtools)
      * [Immutable DevTools](https://github.com/andrewdavey/immutable-devtools), [Immutable.js Object Formatter](https://chrome.google.com/webstore/detail/immutablejs-object-format/hgldghadipiblonfkkicmgcbbijnpeog)
      * [Apollo Client Devtools](https://github.com/apollographql/apollo-client-devtools), [GraphQL Network](https://github.com/Ghirro/graphql-network)
      * [JWT Inspector](https://jwtinspector.io/)
      * [WebGL Insight](https://github.com/3Dparallax/insight/), [Three.js Editor Extension](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea)
    * [Reactotron](https://github.com/infinitered/reactotron)
    * Electron - [Devtron](https://github.com/electron/devtron)
    * [React Native Debugger](https://github.com/jhen0409/react-native-debugger)
  * HTTP Inspector
    * [Paw](https://paw.cloud/) / [Postman](https://www.getpostman.com/) / [HTTPie](https://github.com/jakubroztocil/httpie)
  * Debugging Proxy
    * [AnyProxy](http://anyproxy.io/en.html) / [Fiddler](http://www.telerik.com/fiddler)
    * [Tamper Chrome](https://github.com/google/tamperchrome)
* Deployment
  * Publishing App
    * Server-side Rendering
      * [Hypernova](https://github.com/airbnb/hypernova)
      * [React Isomorphic Render](https://www.npmjs.com/package/react-isomorphic-render)
      * [React Engine](https://www.npmjs.com/package/react-engine)
      * [Express React Views](https://www.npmjs.com/package/express-react-views)
    * Static Web
      * Dynamic Routing + CDN
        * [Superstatic](https://www.npmjs.com/package/superstatic)
      * Object Storage + CDN
        * Global
          * [Amazon S3 + CloudFront](http://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html) - [aws-sdk](https://www.npmjs.com/package/aws-sdk) / [awscli](https://github.com/aws/aws-cli)
          * [Google Cloud Storage + Cloud CDN](https://cloud.google.com/storage/docs/hosting-static-website) - [google-cloud](https://www.npmjs.com/package/google-cloud) / [gcloud](https://cloud.google.com/sdk/gcloud/)
          * [Firebase Hosting](https://firebase.google.com/products/hosting/) - [firebase-tools](https://www.npmjs.com/package/firebase-tools)
          * [Netlify](https://www.netlify.com/) - [netlify-cli](https://www.npmjs.com/package/netlify-cli)
          * [Surge](https://surge.sh/) - [surge cli client](https://www.npmjs.com/package/surge)
        * China
          * [阿里云 OSS + CDN](https://help.aliyun.com/document_detail/31872.html) - [aliyun-sdk](https://www.npmjs.com/package/aliyun-sdk) / [oss-nodejs-sdk](https://www.npmjs.com/package/ali-oss)
          * [腾讯云 COS + CDN](https://www.qcloud.com/document/product/436/9512) - [cos-nodejs-sdk-v5](https://www.npmjs.com/package/cos-nodejs-sdk-v5)
    * Packaged App
      * [Electron Builder](https://www.npmjs.com/package/electron-builder)
        * [Auto Update](https://github.com/electron-userland/electron-builder/wiki/Auto-Update)
      * [CodePush](https://www.npmjs.com/package/react-native-code-push)
  * DevOps
    * Process Supervisor
      * [pm2](http://pm2.keymetrics.io/)
        * [pm2-docker](http://pm2.keymetrics.io/docs/usage/docker-pm2-nodejs/)
        * [Process File](http://pm2.keymetrics.io/docs/usage/application-declaration/)
    * Containers
      * [Docker](https://docs.docker.com/engine/reference/builder/)
        * Learning
          * [Play with docker classroom](http://training.play-with-docker.com/)
          * [Docker Curriculum](https://github.com/prakhar1989/docker-curriculum)
          * [Docker Cheat Sheet](https://github.com/wsargent/docker-cheat-sheet) / [Docker Cheat Sheet](http://docker.jens-piegsa.com/)
        * [Dockerfile reference](https://docs.docker.com/engine/reference/builder/)
        * [Docker run reference](https://docs.docker.com/engine/reference/run/)
        * [Docker Compose](https://docs.docker.com/compose/overview/)
      * Docker Images
        * [node](https://github.com/nodejs/docker-node) / [risingstack/alpine](https://hub.docker.com/r/risingstack/alpine/) / [keymetrics/pm2-docker-alpine](https://hub.docker.com/r/keymetrics/pm2-docker-alpine/)
        * [docker-lambda](https://github.com/lambci/docker-lambda)
    * Container Clusters
      * [Docker Engine in Swarm Mode](https://docs.docker.com/engine/swarm/)
        * [Compose file reference](https://docs.docker.com/compose/compose-file/)
        * [wait-for-it.sh](https://github.com/vishnubob/wait-for-it) / [dockerize](https://github.com/jwilder/dockerize)
      * [Kubernetes](https://kubernetes.io/)
        * [Kubernetes Cheat Sheet](http://k8s.info/cs.html)
    * PaaS
      * Global
        * [now](https://zeit.co/now)
        * [heroku](heroku.com) - [heroku-cli](https://devcenter.heroku.com/articles/heroku-cli#getting-started)
      * China
        * [LeanCloud-云引擎](https://leancloud.cn/docs/leanengine_overview.html) ([云函数](https://leancloud.cn/docs/leanengine_cloudfunction_guide-node.html), [网站托管](https://leancloud.cn/docs/leanengine_webhosting_guide-node.html)) - [lean-cli](https://leancloud.cn/docs/leanengine_cli.html)
* Monitoring
  * Error Tracking
    * [Capturing client-side JavaScript errors](https://www.thoughtworks.com/radar/techniques/capturing-client-side-javascript-errors), [Front-End Error Handling](https://staticapps.org/articles/front-end-error-handling/)
      * [A Guide to Proper Error Handling in JavaScript](https://www.sitepoint.com/proper-error-handling-javascript/)
    * Services
      * [TrackJS](https://trackjs.com/) / [Errorception](https://errorception.com/)
      * [Sentry](https://sentry.io/for/javascript/) / [Rollbar](https://rollbar.com/docs/notifier/rollbar.js/) / [Bugsnag](https://docs.bugsnag.com/platforms/browsers/) / [Airbrake](https://airbrake.io/languages/javascript_exception_handler) / [Raygun](https://raygun.com/)
  * Logging
    * Global
      * [Amazon CloudWatch](https://aws.amazon.com/cloudwatch/) / [Google Stackdriver](https://cloud.google.com/stackdriver/)
      * [PM2 Plus](https://pm2.io/plus/)
    * China
      * [阿里云-云监控](https://www.aliyun.com/product/jiankong) / [腾讯云-基础监控 BCM](https://www.qcloud.com/product/bcm)
  * APM (Application Performance Management)
    * Global
      * [New Relic](https://newrelic.com/) / [AppDynamics](https://www.appdynamics.com/) / [Datadog APM](https://www.datadoghq.com/apm/)
      * [Pingdom](https://www.pingdom.com/) / [SpeedCurve](https://speedcurve.com/) / [AppNeta](https://www.appneta.com/)
      * [Trace](https://trace.risingstack.com)
    * China
      * [OneAPM](https://www.oneapm.com/) / [听云](http://www.tingyun.com/)
      * [监控宝](https://www.jiankongbao.com/) / [百度云观测](http://ce.baidu.com/) / [360网站服务监控](http://jk.cloud.360.cn/) / [腾讯云-云拨测 CAT](https://www.qcloud.com/product/cat)
      * [阿里云 Node.js 性能平台](https://www.aliyun.com/product/nodejs)
