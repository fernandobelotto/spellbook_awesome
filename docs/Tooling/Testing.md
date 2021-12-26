## Unit Testing / Test Runner
  * [Jest](https://facebook.github.io/jest/)
  * [AVA](https://github.com/avajs/ava)
  * [Mocha](https://mochajs.org/) + [Chai](http://chaijs.com/)
  * [Cypress](https://www.cypress.io/)
  * [Karma](https://karma-runner.github.io)
## Web Testing
  * Integration Testing
    * Components - [Enzyme](http://airbnb.io/enzyme/)
    * Reducers
      * [redux-test-utils](https://www.npmjs.com/package/redux-test-utils) + [enzyme-redux](https://www.npmjs.com/package/enzyme-redux)
      * [redux-testkit](https://www.npmjs.com/package/redux-testkit)
  * Functional Testing / E2E Testing
    * Headless Browser Automation
      * DevTools API
        * Headless Chrome - [Puppeteer](https://github.com/GoogleChrome/puppeteer) / [Chromy](https://www.npmjs.com/package/chromy)
          * [End-to-end Tests that Don’t Suck with Puppeteer](https://ropig.com/blog/end-end-tests-dont-suck-puppeteer/)
          * AWS Lambda - [Chromeless](https://www.npmjs.com/package/chromeless)
        * electron-prebuilt - [Nightmare](https://github.com/segmentio/nightmare)
      * WebDriver API - [Selenium WebDriverJS](https://github.com/SeleniumHQ/selenium/wiki/WebDriverJs) / [WebDriverIO](http://webdriver.io/) / [Nightwatch.js](http://nightwatchjs.org/) / [CasperJS](http://casperjs.org/) / [Protractor](http://www.protractortest.org/)
          * AWS Lambda - [Lambdium](https://github.com/smithclay/lambdium)
    * Cloud - [BrowserStack Automate](https://www.browserstack.com/automate) / [Sauce Labs](https://saucelabs.com/open-source#automated-testing-platform)
  * Visual Testing
    * [React Storybook](https://storybooks.js.org/) / [React Cosmos](https://github.com/react-cosmos/react-cosmos)
    * [BrowserStack](https://www.browserstack.com/)
  * Monkey Testing
    * [gremlins.js](https://www.npmjs.com/package/gremlins.js)
  * Headless Browsers
    * Browsers
      * Chromium - [Headless Chrome/Chromium](https://developers.google.com/web/updates/2017/04/headless-chrome)
      * Chromium + Node.js - [electron-prebuilt](https://www.npmjs.com/package/electron)
      * WebKit - [PhantomJS](http://phantomjs.org/)
        * [Why you should stop using PhantomJS](https://blog.phantombuster.com/why-you-should-stop-using-phantomjs-f5c5f2717209)
      * Gecko - [SlimerJS](https://slimerjs.org/)
    * In-memory X11 Display Server
      * [xvfb](https://en.wikipedia.org/wiki/Xvfb) - [xvfb-run](http://manpages.ubuntu.com/manpages/trusty/man1/xvfb-run.1.html) / [headless](https://www.npmjs.com/package/headless)
    * Docker
      * [lighthouse-ci/builder/Dockerfile.headless](https://github.com/ebidel/lighthouse-ci/blob/master/builder/Dockerfile.headless#L16)
      * [electron-headless](https://hub.docker.com/r/dannysu/electron-headless/~/dockerfile/)
## Server-side Testing
  * Functional Testing
    * [supertest](https://www.npmjs.com/package/supertest)
  * Load Testing
    * [k6](https://k6.io/)
    * [loadtest](https://www.npmjs.com/package/loadtest)
## Benchmark Testing
  * JS
    * [Benchmark.js](https://benchmarkjs.com/)
    * [Speedracer](https://github.com/ngryman/speedracer)
    * [stats.js](https://github.com/mrdoob/stats.js)
  * Network
    * [wrk](https://github.com/wg/wrk) / [httpstat](https://github.com/reorx/httpstat)
## [Test Doubles](https://martinfowler.com/bliki/TestDouble.html) ([Fakes, Mocks, Stubs](https://dev.to/milipski/test-doubles---fakes-mocks-and-stubs) and Spies)
  * Fake Data
    * [Faker.js](https://github.com/Marak/Faker.js) / [Chance.js](http://chancejs.com/)
    * [JSON Schema Faker](https://www.npmjs.com/package/json-schema-faker)
    * [placeholder.com](https://placeholder.com/)
  * HTTP Mocking - [Nock](https://www.npmjs.com/package/nock)
  * Monkey Patching - [Mockery](https://www.npmjs.com/package/mockery), [babel-plugin-rewire](https://www.npmjs.com/package/babel-plugin-rewire)
  * [SinonJS](http://sinonjs.org/) / [testdouble.js](https://www.npmjs.com/package/testdouble)
    * [Best Practices for Spies, Stubs and Mocks in Sinon.js](https://semaphoreci.com/community/tutorials/best-practices-for-spies-stubs-and-mocks-in-sinon-js)
    * [testdouble.js vs. sinon.js](http://blog.testdouble.com/posts/2016-03-13-testdouble-vs-sinon.html)
## Analysis
  * Code Coverage
    * [Istanbul](https://istanbul.js.org/)
  * Software Complexity
    * [escomplex](https://www.npmjs.com/package/escomplex) / [complexity-report](https://www.npmjs.com/package/complexity-report)
  * Node.js Security
    * [nsp](https://www.npmjs.com/package/nsp) / [snyk](https://www.npmjs.com/package/snyk)
      * [NSP Advisories](https://nodesecurity.io/advisories/) / [Snyk - Vulnerability DB](https://snyk.io/vuln/)
  * Web Page
    * [Lighthouse](https://developers.google.com/web/tools/lighthouse/) / [pwmetrics](https://github.com/paulirish/pwmetrics)
    * [PageSpeed Insights](https://developers.google.com/speed/pagespeed/)
    * [Varvy SEO tool](https://varvy.com/)

