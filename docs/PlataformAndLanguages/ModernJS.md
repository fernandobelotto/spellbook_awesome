# Modern JS / Next-Gen JS

## ES6+ Features
  * [Overview of ECMAScript 6 features](https://github.com/lukehoban/es6features)
  * [Babel REPL](http://babeljs.io/repl/) / [ES6 New Features Comparison](http://es6-features.org/)
## Intro to ES6+
  * [Dr. Axel Rauschmayer's blog](http://2ality.com/)
    * [Exploring ES6](http://exploringjs.com/es6/)
    * [Exploring ES2016 and ES2017](http://exploringjs.com/es2016-es2017/)
  * [ES6 In Depth](https://hacks.mozilla.org/category/es6-in-depth/)
  * Nicholas C. Zakas's [Understanding ECMAScript 6](https://leanpub.com/understandinges6)
## Re-intro to JS
  * Articles
    * MDN
      * [A re-introduction to JavaScript (JS tutorial)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)
      * [Equality comparisons and sameness](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness), [Data types and data structures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures), [Closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures), [Inheritance and the prototype chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
      * [Concurrency model and Event Loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop), [Memory Management](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management)
    * Dmitry Soshnikov
      * [JavaScript. The Core](http://dmitrysoshnikov.com/ecmascript/javascript-the-core/)
      * ECMA-262-3 in detail
        * [Execution Contexts](http://dmitrysoshnikov.com/ecmascript/chapter-1-execution-contexts/), [Variable object](http://dmitrysoshnikov.com/ecmascript/chapter-2-variable-object/), [This](http://dmitrysoshnikov.com/ecmascript/chapter-3-this/), [Scope chain](http://dmitrysoshnikov.com/ecmascript/chapter-4-scope-chain/), [Functions](http://dmitrysoshnikov.com/ecmascript/chapter-5-functions/), [Closures](http://dmitrysoshnikov.com/ecmascript/chapter-6-closures/), [Evaluation strategy](http://dmitrysoshnikov.com/ecmascript/chapter-8-evaluation-strategy/)
        * OOP: [The general theory](http://dmitrysoshnikov.com/ecmascript/chapter-7-1-oop-general-theory/), [ECMAScript implementation](http://dmitrysoshnikov.com/ecmascript/chapter-7-2-oop-ecmascript-implementation/),
      * ECMA-262-5 in detail
        * [Properties and Property Descriptors](http://dmitrysoshnikov.com/ecmascript/es5-chapter-1-properties-and-property-descriptors/), [Strict Mode](http://dmitrysoshnikov.com/ecmascript/es5-chapter-2-strict-mode/)
        * Lexical environments: [Common Theory](http://dmitrysoshnikov.com/ecmascript/es5-chapter-3-1-lexical-environments-common-theory/), [ECMAScript implementation](http://dmitrysoshnikov.com/ecmascript/es5-chapter-3-2-lexical-environments-ecmascript-implementation/)
      * Notes
        * [Equality operators](http://dmitrysoshnikov.com/notes/note-2-ecmascript-equality-operators/), [Default values of parameters](http://dmitrysoshnikov.com/ecmascript/es6-notes-default-values-of-parameters/)
    * Dmitri Pavlutin
      * [equality operator](https://dmitripavlutin.com/the-legend-of-javascript-equality-operator/), [undefined](https://dmitripavlutin.com/7-tips-to-handle-undefined-in-javascript/)
      * [variables hoisting](https://dmitripavlutin.com/javascript-hoisting-in-details/), [variables lifecycle](https://dmitripavlutin.com/variables-lifecycle-and-why-let-is-not-hoisted/)
      * [declare functions](https://dmitripavlutin.com/6-ways-to-declare-javascript-functions/), ['this' keyword](https://dmitripavlutin.com/gentle-explanation-of-this-in-javascript/)
      * [three dots](https://dmitripavlutin.com/how-three-dots-changed-javascript/)
      * [array creation](https://dmitripavlutin.com/power-up-the-array-creation-in-javascript/), [object literals](https://dmitripavlutin.com/why-object-literals-in-javascript-are-cool/)
      * [well-known symbols](https://dmitripavlutin.com/detailed-overview-of-well-known-symbols/)
      * [small and plain functions](https://dmitripavlutin.com/the-art-of-writing-small-and-plain-functions/)
      * [unicode](https://dmitripavlutin.com/what-every-javascript-developer-should-know-about-unicode/)
    * Other
      * [The Evolution of JavaScript Modularity](https://github.com/myshov/history-of-javascript/tree/master/4_evolution_of_js_modularity)
      * [About object-oriented design and the “class” & “extends” keywords in ES6](http://blog.wolksoftware.com/about-classes-inheritance-and-object-oriented-design-in-typescript-and-es6)
      * [JavaScript Regular Expression Enlightenment](http://codylindley.com/techpro/2013_05_14__javascript-regular-expression-/)
  * Books
    * [Eloquent JavaScript](http://eloquentjavascript.net/)
    * [Speaking JavaScript](http://speakingjs.com/es5/)
    * [You Don't Know JS (book series)](https://github.com/getify/You-Dont-Know-JS)
## Reference
  * [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
  * [JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
## Important Proposals
  * ESM (ECMAScript Modules)
    * Intro
      * [The state of JavaScript modules](https://medium.com/webpack/the-state-of-javascript-modules-4636d1774358)
      * [ECMAScript 6 modules: the final syntax](http://2ality.com/2014/09/es6-modules-final.html)
      * [ES6 Modules in Depth](https://ponyfoo.com/articles/es6-modules-in-depth#the-es6-module-system)
    * Browsers
      * [ECMAScript modules in browsers](https://jakearchibald.com/2017/es-modules-in-browsers/)
    * Node.js
      * [Node.js, TC-39, and Modules](https://hackernoon.com/node-js-tc-39-and-modules-a1118aecf95e)
      * [.mjs](https://nodejs.org/api/esm.html)
        * [Using ES modules natively in Node.js](http://2ality.com/2017/09/native-esm-node.html)
      * [esm](https://www.npmjs.com/package/esm)
        * [ES Modules in Node Today!](https://medium.com/web-on-the-edge/es-modules-in-node-today-32cff914e4b)
  * [Dynamic Import (`import()`)](https://github.com/tc39/proposal-dynamic-import)
  * [Class Fields & Static Properties](https://github.com/tc39/proposal-class-public-fields/issues/46#issuecomment-239031422)
  * [Decorators](https://github.com/wycats/javascript-decorators)
  * [async/await](https://github.com/yortus/asyncawait), [Promise](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Promise), [Promise Promote](https://www.promisejs.org/), [Promises/A+](https://promisesaplus.com/implementations)
  * [Observables](https://github.com/tc39/proposal-observable)
  * [Static Typing](https://ecmascript-daily.github.io/pages/status-of-static-typing-in-ecmascript/)
  * Concurrent JS / Parallel JavaScript
    * [Concurrent JavaScript: It can work!](https://webkit.org/blog/7846/concurrent-javascript-it-can-work/)
    * [The Path to Parallel JavaScript](https://blog.mozilla.org/javascript/2015/02/26/the-path-to-parallel-javascript/)
      * [A Taste of JavaScript’s New Parallel Primitives](https://hacks.mozilla.org/2016/05/a-taste-of-javascripts-new-parallel-primitives/)
      * [A cartoon intro to ArrayBuffers and SharedArrayBuffers](https://hacks.mozilla.org/2017/06/a-cartoon-intro-to-arraybuffers-and-sharedarraybuffers/)
## Functional Programming
  * [Functional Programming for JavaScript People](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504)
  * [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon)
  * [Composing Software](https://medium.com/javascript-scene/the-rise-and-fall-and-rise-of-functional-programming-composable-software-c2d91b424c8c)
  * Books
    * [Professor Frisby's Mostly Adequate Guide to Functional Programming](https://drboolean.gitbooks.io/mostly-adequate-guide)
    * [Functional-Light JavaScript](https://github.com/getify/functional-light-js)
  * [Lodash's FP Guide](https://github.com/lodash/lodash/wiki/FP-Guide)
  * [Introduction to Immutable.js and Functional Programming Concepts](https://auth0.com/blog/intro-to-immutable-js/)
  * [Why Ramda?](http://fr.umio.us/why-ramda/)
    * [The Philosophy of Ramda](http://fr.umio.us/the-philosophy-of-ramda/)
    * [Favoring Curry](http://fr.umio.us/favoring-curry/)
    * [Thinking in Ramda](http://randycoulman.com/blog/2016/05/24/thinking-in-ramda-getting-started/)
  * [Fantasy Land](https://github.com/fantasyland/fantasy-land)
    * [From Callback to Future -> Functor -> Monad](https://hackernoon.com/from-callback-to-future-functor-monad-6c86d9c16cb5)
    * [ADT (Algebraic Data Types)](http://blog.jenkster.com/2016/06/functional-mumbo-jumbo-adts.html)
    * [JavaScript and Type Thinking](https://medium.com/@yelouafi/javascript-and-type-thinking-735edddc388d)
    * [Functors, Applicatives, And Monads In Pictures](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html)
## FRP (Functional Reactive Programming)
  * [The introduction to Reactive Programming you've been missing](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)
  * [How Is Reactive Different From Procedural Programming?](http://insights.dice.com/2014/01/13/how-is-reactive-different-from-procedural-programming/)
  * [A General Theory of Reactivity](https://github.com/kriskowal/gtor)
  * [Learn RxJS](https://www.learnrxjs.io/)
    * [Rx Book](http://xgrommx.github.io/rx-book/index.html)
    * [Functional Programming in JavaScript](http://reactivex.io/learnrx/)
    * [RxMarbles](http://rxmarbles.com/)
## Static Typing
  * Intro
    * [Why use static types in JavaScript?](https://medium.freecodecamp.com/why-use-static-types-in-javascript-part-1-8382da1e0adb)
    * [You Might Not Need TypeScript (or Static Types)](https://medium.com/javascript-scene/you-might-not-need-typescript-or-static-types-aa7cb670a77b)
  * [Flow](https://flow.org/en/docs/)
    * [Flow Runtime](https://codemix.github.io/flow-runtime/)
    * [Flow Comments](https://flow.org/blog/2015/02/20/Flow-Comments/)
  * [TypeScript](http://www.typescriptlang.org/)
    * [TypeScript Playground](https://www.typescriptlang.org/play/)
    * [DefinitelyTyped](http://definitelytyped.org/), [TypeSearch](http://microsoft.github.io/TypeSearch/)
  * [tcomb](https://www.npmjs.com/package/tcomb)
  * [JSDoc Tags](https://github.com/google/closure-compiler/wiki/Annotating-JavaScript-for-the-Closure-Compiler)
    * [jsdoc-to-assert](https://github.com/azu/jsdoc-to-assert)
## Concurrent JS / Parallel JavaScript
  * [Napa.js](https://github.com/Microsoft/napajs/)
## Code Style
  * [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
  * [Node.js Style Guide](https://github.com/felixge/node-style-guide)
  * [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript)
  * [JavaScript Clean Coding Best Practices](https://blog.risingstack.com/javascript-clean-coding-best-practices-node-js-at-scale/)

