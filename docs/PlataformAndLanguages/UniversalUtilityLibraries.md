# Universal Utility Libraries

## Standard Library Extensions
  * Utilities
    * [Lodash](https://lodash.com)
    * [is.js](http://is.js.org/)
  * FP
    * [Ramda](http://ramdajs.com/)
      * [ramda-fantasy](https://www.npmjs.com/package/ramda-fantasy)
    * Immutable
      * [immutability-helper](https://www.npmjs.com/package/immutability-helper) + [redux-immutable-state-invariant](https://www.npmjs.com/package/redux-immutable-state-invariant) / [redux-freeze](https://www.npmjs.com/package/redux-freeze)
      * [icepick](https://www.npmjs.com/package/icepick) / [seamless-immutable](https://www.npmjs.com/package/seamless-immutable) / [dot-prop-immutable](https://www.npmjs.com/package/dot-prop-immutable) / [object-path-immutable](https://www.npmjs.com/package/object-path-immutable) / [timm](https://www.npmjs.com/package/timm) / [updeep](https://www.npmjs.com/package/updeep)
      * [ImmutableJS](http://facebook.github.io/immutable-js/)
  * OOP
    * [lodash-decorators](https://www.npmjs.com/package/lodash-decorators)
    * [Stampit](https://www.npmjs.com/package/stampit)
  * Async
    * Observable - [RxJS](https://www.npmjs.com/package/rxjs)
    * Promise - [es6-promisify](https://www.npmjs.com/package/es6-promisify), [Bluebird](http://bluebirdjs.com/docs/features.html)
    * Generator - [Co](https://www.npmjs.com/package/co)
    * Callback - [Async](http://caolan.github.io/async/)
  <!-- * Concurrent / Parallel -->
  * Syntax
    * [XRegExp](https://www.npmjs.com/package/xregexp)
  * Node.js API
    * [node-libs-browser](https://www.npmjs.com/package/node-libs-browser)
    * [EventEmitter3](https://www.npmjs.com/package/eventemitter3)
  * Debugging
    * [debug](https://www.npmjs.com/package/debug) / [pino](https://www.npmjs.com/package/pino)
## Hashing / Generating
  * [uuid](https://www.npmjs.com/package/uuid) / [cuid](http://usecuid.org)
  * [shortid](https://www.npmjs.com/package/shortid) / [punycode](https://www.npmjs.com/package/punycode) / [string-hash](https://www.npmjs.com/package/string-hash)
  * [base64-js](https://www.npmjs.com/package/base64-js) / [sha.js](https://www.npmjs.com/package/sha.js) / [spark-md5](https://www.npmjs.com/package/spark-md5) / [crypto-js](https://www.npmjs.com/package/crypto-js) / [jsrsasign](https://www.npmjs.com/package/jsrsasign)
## Parsing / Manipulating
  * URL
    * URL Parsing - [qs](https://www.npmjs.com/package/qs), [URI.js](https://github.com/medialize/URI.js)
    * IP Address Manipulation - [ip](https://www.npmjs.com/package/ip)
  * Environment
    * UA Sniffing - [UAParser.js](https://github.com/faisalman/ua-parser-js) / [useragent](https://www.npmjs.com/package/useragent)
    * Information - [platform.js](https://www.npmjs.com/package/platform)
    * Runtime Detection - [is-electron-renderer](https://www.npmjs.com/package/is-electron-renderer) / [electron-is](https://www.npmjs.com/package/electron-is)
  * Validator
    * String Validation - [validator.js](https://github.com/chriso/validator.js)
    * Schema Validation - [joi](https://www.npmjs.com/package/joi) / [Ajv](http://epoberezkin.github.io/ajv/)
  * i18n
    * [Intl.js](https://www.npmjs.com/package/intl) + [FormatJS](https://formatjs.io/guides/) / [i18next](https://www.i18next.com/)
  * Date
    * Date Manipulation - [Moment.js](http://momentjs.com)
  * Numbers
    * Number Manipulation - [Numeral.js](http://numeraljs.com/)
    * Money - [accounting.js](http://openexchangerates.github.io/accounting.js/)
  * Color
    * Color Manipulation - [Chroma.js](http://gka.github.io/chroma.js/), [Chromatism](https://www.npmjs.com/package/chromatism), [randomColor](https://www.npmjs.com/package/randomcolor)
    * Color Extraction - [node-vibrant](https://www.npmjs.com/package/node-vibrant) / [Colorify.js](http://colorify.rocks/)
  * Text
    * Text Manipulation - [Voca.js](https://vocajs.com) / [string.js](https://github.com/jprichardson/string.js)
    * Characters - [string-width](https://www.npmjs.com/package/string-width), [string-length](https://www.npmjs.com/package/string-length)
    * HTML Entities - [he](https://www.npmjs.com/package/he)
    * Human-readable Slug - [speakingurl](https://www.npmjs.com/package/speakingurl)
    * XSS Sanitizer - [DOMPurify](https://www.npmjs.com/package/dompurify) / [xss](https://www.npmjs.com/package/xss)
    * HTTP - [mime-types](https://www.npmjs.com/package/mime-types), [content-type](https://www.npmjs.com/package/content-type)
    * JSON Superset - [serialize-javascript](https://www.npmjs.com/package/serialize-javascript), [JSON5](https://www.npmjs.com/package/json5)
    * Markdown - [marked](https://www.npmjs.com/package/marked) / [markdown-it](https://www.npmjs.com/package/markdown-it)
      * [CommonMark](http://commonmark.org/), [A formal spec for GitHub Flavored Markdown](https://githubengineering.com/a-formal-spec-for-github-markdown/)
    * Links Recognition - [linkify-it](https://www.npmjs.com/package/linkify-it)
    * Language Detection - [franc](https://www.npmjs.com/package/franc)
    * Text Differencing - [diff](https://www.npmjs.com/package/diff)
    * JSON Differencing - [deep-diff](https://www.npmjs.com/package/deep-diff)
    * Search - [Fuse.js](http://fusejs.io/) / [fuzzysearch](https://www.npmjs.com/package/fuzzysearch) / [Lunr.js](https://lunrjs.com) / [js-worker-search](https://www.npmjs.com/package/js-worker-search), [regexgen](https://www.npmjs.com/package/regexgen) / [escape-string-regexp](https://www.npmjs.com/package/escape-string-regexp)
    * DSL Parser - [PEG.js](https://pegjs.org/) / [nearley](http://nearley.js.org/)
  * Buffer / Blob
    * Type Detection - [file-type](https://www.npmjs.com/package/file-type), [image-type](https://www.npmjs.com/package/image-type)
    * Size Detection - [probe-image-size](https://www.npmjs.com/package/probe-image-size)
    * Image Manipulation - [jimp](https://www.npmjs.com/package/jimp)
      * Image Crop - [Smartcrop.js](https://www.npmjs.com/package/smartcrop)
    * QR Code / Barcode - [qrcode](https://www.npmjs.com/package/qrcode) / [jsbarcode](https://www.npmjs.com/package/jsbarcode)
## Logic
  * Rate Limiter - [Bottleneck](https://www.npmjs.com/package/bottleneck) / [Limiter](https://www.npmjs.com/package/limiter)
## Network
  * HTTP / XHR
    * Low-level - [Isomorphic Fetch](https://github.com/matthew-andrews/isomorphic-fetch)
    * High-level
      * Based on XHR - [Axios](https://www.npmjs.com/package/axios)
      * Based on Fetch API - [hifetch](https://github.com/dexteryy/Project-WebCube/blob/master/packages/hifetch)
    * GraphQL - [lokka](https://github.com/kadirahq/lokka)
  * TCP
    * [MQTT](https://www.npmjs.com/package/mqtt)
  * UDP / P2P
    * [Simple Peer](https://www.npmjs.com/package/simple-peer) / [JS SIP](https://www.npmjs.com/package/jssip)
    * [WebTorrent](https://www.npmjs.com/package/webtorrent)
## Storage
  * File Database
    * JSON - [Lowdb](https://www.npmjs.com/package/lowdb)
  * IndexedDB / WebSQL / localStorage / Memory
    * MongoDB API - [NeDB](https://www.npmjs.com/package/nedb)
    * CouchDB API - [PouchDB](https://pouchdb.com)
  * Realtime / P2P - [Gun](https://www.npmjs.com/package/gun), [ShareDB](https://www.npmjs.com/package/sharedb)
## Computation
  * [Math.js](http://mathjs.org/), [Simple Statistics](https://simplestatistics.org/), [ndarray](https://www.npmjs.com/package/ndarray), [bignumber.js](http://mikemcl.github.io/bignumber.js/)
## NLP
  * [compromise](https://github.com/nlp-compromise/compromise) / [talisman](http://yomguithereal.github.io/talisman/)
## ML/DL
  * [TensorFlow.js](https://js.tensorflow.org/)
  * [MLJS](https://www.npmjs.com/package/ml), [Synaptic](https://www.npmjs.com/package/synaptic)
