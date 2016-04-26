# Front-End

<!-- toc -->

* [JavaScript](#javascript)
  * [Aprendizado](#aprendizado)
  * [OOP](#oop)
  * [Padrões](#padrões)
  * [Dicas](#dicas)
  * [Expressões Regulares](#expressões-regulares)
    * [Expressões Regulares: Ferramentas online](#expressões-regulares-ferramentas-online)
  * [Performance](#performance)
    * [Compressão](#compressão)
    * [Ordenação](#ordenação)
  * [Sistema de Dependências e Módulos](#sistema-de-dependências-e-módulos)
    * [Webpack](#webpack)
    * [Browserify](#browserify)
    * [Require.js](#requirejs)
  * [Qualidade de Código](#qualidade-de-código)
  * [Integração Contínua](#integração-contínua)
  * [Útil](#útil)
  * [Bibliotecas](#bibliotecas)
    * [Upload](#upload)
    * [Emulator](#emulator)
    * [Redes Neurais](#redes-neurais)
    * [Compiladores](#compiladores)
    * [Máquinas Virtuais](#máquinas-virtuais)
    * [Text Search](#text-search)
    * [Hash](#hash)
    * [Crypto](#crypto)
    * [Steganography](#steganography)
    * [Gesture](#gesture)
  * [Design API & Biblioteca](#design-api-biblioteca)
  * [Ferramentas](#ferramentas)
    * [Slush](#slush)
    * [Yeoman](#yeoman)
    * [DevTools](#devtools)
  * [Gerenciador de Pacotes](#gerenciador-de-pacotes)
    * [Bower](#bower)
    * [JamJS](#jamjs)
  * [Single Page Application](#single-page-application)
  * [Frameworks](#frameworks)
  * [Babel](#babel)
  * [ECMAScript 6](#ecmascript-6)
  * [ECMAScript 7](#ecmascript-7)

<!-- toc stop -->


## JavaScript

* [Superhero.js](http://superherojs.com/) -  Creating, testing and maintaining a large JavaScript code base is not easy - especially since great resources on how to do this are hard to  find. This page is a collection of the best articles, videos and  presentations we've found on the topic.

* [wtfjs](http://wtfjs.com/) - a little code blog about that language we love despite giving us so much to hate

  * [[GitHub] brianleroux / wtfjs](https://github.com/brianleroux/wtfjs)

--

* [JavaScript World Domination | Medium - by @slsoftworks](https://medium.com/@slsoftworks/javascript-world-domination-af9ca2ee5070) - A Civilization-esque journey through JavaScript history — chronicles of the march from inception to ubiquity


### Aprendizado

* [JS: The Right Way](http://jstherightway.org/)

  * [[GitHub] braziljs / js-the-right-way](https://github.com/braziljs/js-the-right-way) - An easy-to-read, quick reference for JS best practices, accepted coding standards, and links around the Web

* [Happy 18th Birthday JavaScript! | Resin.io](http://resin.io/happy-18th-birthday-javascript/) -  A look at an unlikely past and bright future

* [[GitHub] coodict / javascript-in-one-pic](https://github.com/coodict/javascript-in-one-pic) - Learn javascript in one picture

* [[YouTube] O fantástico mundo do JavaScript - Jean Carlo Emer](http://www.youtube.com/watch?v=Zn7B-X0y5qs)

--

* [[YouTube] Philip Roberts: What the heck is the event loop anyway? | JSConf EU 2014](https://www.youtube.com/watch?v=8aGhZQkoFbQ) - [loupe tool](http://latentflip.com/loupe/)

--

* [JavaScript.com](https://www.javascript.com/) - Learn JavaScript and stay connected with the latest news created and curated by the JavaScript community.

--

* [Javascript Learning Tracks](http://js.startrack.io/)

--

* [Learning Javascript with Object Graphs | How To Node - NodeJS](http://howtonode.org/object-graphs)

--

* [JavaScript for Designers | Rachel Nabors](http://rachelnabors.com/javascript-for-designers/) - An Intro to JS Terms and Concepts

--

* [Cinco conhecimentos essenciais para programadores Javascript | Onetalk Drops — Medium](https://medium.com/onetalk-drops/5-conhecimentos-essenciais-para-programadores-javascript-dae31f3d9bab)

* [Learn JavaScript Essentials (for all skill levels) by Eric Elliott | Medium](https://medium.com/javascript-scene/learn-javascript-b631a4af11f2)

* [Resources for Learning Javascript | @jendmann](http://jennifermann.ghost.io/resources-for-learning-javascript/)

* [[GitHub] hr-14-15 / resources](https://github.com/hr-14-15/resources) - JavaScript resources for and by HR 14 & 15

* [[GitHub] ericelliott / essential-javascript-links](https://github.com/ericelliott/essential-javascript-links) - Essential JavaScript website

--

* [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/) - documentação com recomendações e boas práticas de programação em JavaScript.

* [Eloquent JavaScript](http://eloquentjavascript.net/) - A Modern Introduction to Programming, by Marijn Haverbeke | [second edition](http://eloquentjavascript.net/2nd_edition/)

* [Learn JavaScript | Mozilla Developer Network](https://developer.mozilla.org/en-US/learn/javascript)

* [Learning JavaScript: Essentials And Guidelines](http://www.smashingmagazine.com/learning-javascript-essentials-guidelines-tutorials/)

* [[YouTube] Google Tech Talks 2009 : JavaScript - The Good Parts](https://www.youtube.com/watch?v=hQVTIJBZook)

* [JavaScript: The Extra Good Parts | Wix Engineering](http://engineering.wix.com/2015/04/21/javascript-the-extra-good-parts/)

* [[YouTube] Dos and Don'ts in JavaScript: A few best practices for when you're learning the language](https://www.youtube.com/watch?v=zILmbcIYnfw)

* [A Bit of Advice for the JavaScript Semicolon Haters | Ben Alman](http://benalman.com/news/2013/01/advice-javascript-semicolon-haters/)

* [Summary of Maintainable JavaScript Talk by Nicholas C. Zakas | Alex Kras](http://www.alexkras.com/summary-of-maintainable-javascript/)

* [Estou iniciando em javascript, por onde começo? | JavaScript Brasil](http://javascriptbrasil.com/artigos/estou-iniciando-em-javascript-por-onde-comeco)

* [Basic JavaScript for the impatient programmer | 2ality](http://www.2ality.com/2013/06/basic-javascript.html)

* [Preparando-se para o desenvolvimento JavaScript moderno | iMasters](http://imasters.com.br/linguagens/javascript/preparando-se-para-o-desenvolvimento-javascript-moderno/)

* [[SlideShare] Metaprogramming JavaScript](http://pt.slideshare.net/danwrong/metaprogramming-javascript)

* [[SlideShare] Scalable JavaScript Application Architecture](http://www.slideshare.net/nzakas/scalable-javascript-application-architecture)

--

* [[GitHub] sethvincent / javascripting](https://github.com/sethvincent/javascripting) - Learn JavaScript by adventuring around in the terminal

--

* [21 JavaScript Parts I Struggle To Remember | Tech.Pro](http://tech.pro/tutorial/1669/21-javascript-parts-i-struggle-to-remember-)

--

* [Seven JavaScript Quirks I Wish I’d Known About | Telerik Developer Network](http://developer.telerik.com/featured/seven-javascript-quirks-i-wish-id-known-about/)

* [10 Mistakes That JavaScript Beginners Often Make | Tutorialzine](http://tutorialzine.com/2014/04/10-mistakes-javascript-beginners-make/)

* [10 Common JavaScript Coding Errors | Toptal](http://www.toptal.com/javascript/10-most-common-javascript-mistakes)

* [Catching JavaScript Mistakes with TypeScript - TypeScript Video Tutorial #free | @eggheadio](https://egghead.io/lessons/javascript-catching-javascript-mistakes-with-typescript)

--

* [15 JavaScript Hacks | Underground WebDev](http://udgwebdev.com/15-javascript-hacks/)

--

* [Code Academy - JavaScript](http://www.codecademy.com/pt/tracks/javascript-combined)

* [Codewars](http://www.codewars.com/) - is where developers achieve code mastery through challenge.

* [CodeCombat](http://codecombat.com/) - Learn to Code JavaScript by Playing a Game

--

* [Learn Javascript](http://gitbookio.github.io/javascript/)

* [Javascript Challenges](https://tcorral.github.io/javascript-challenges-book/) - This book will challenge you to learn and understand the most obscure and tricky parts of Javascript

* [Survive JavaScript - a Web Developer's Guide](http://survivejs.com/)

--

* [[GitHub] getify / You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) - A JavaScript book series

  * [You Don't Know JS: Scope & Closures](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20&%20closures/README.md#you-dont-know-js-scope--closures)

  * [You Don't Know JS: this & Object Prototypes](https://github.com/getify/You-Dont-Know-JS/blob/master/this%20&%20object%20prototypes/README.md#you-dont-know-js-this--object-prototypes)

--

* [Para que serve o "use strict" em JavaScript?](http://caioproiete.net/pt/para-que-serve-o-use-strict-em-javascript/)

* [It's time to start using JavaScript strict mode | NCZOnline](http://www.nczonline.net/blog/2012/03/13/its-time-to-start-using-javascript-strict-mode/)

* [Javascript's Slightly Stricter Mode | Glen Maddern](http://geelen.github.io/web-directions-talk)

* [ECMAScript 5 Strict Mode, JSON, and More | John Resig](http://ejohn.org/blog/ecmascript-5-strict-mode-json-and-more/)

--

* [Every Possible Way to Define a Javascript Function | Bryan Braun](http://www.bryanbraun.com/2014/11/27/every-possible-way-to-define-a-javascript-function)

* [Functions Explained | Mark Daggett's Blog](http://markdaggett.com/blog/2013/02/15/functions-explained/)

* [Javascript hoisting explained | Kenneth Truyers](http://www.kenneth-truyers.net/2013/04/20/javascript-hoisting-explained/)

* [Variable and Function Hoisting in JavaScript | Design Pepper](http://designpepper.com/blog/drips/variable-and-function-hoisting)

* [An Introduction to IIFEs - Immediately Invoked Function Expressions | Design Pepper](http://designpepper.com/blog/drips/an-introduction-to-iifes-immediately-invoked-function-expressions)

* [O que é IIFE no JavaScript? | Tutsmais](http://tutsmais.com.br/blog/javascript-2/o-que-e-iife-no-javascript/)

* [What (function (window, document, undefined) {})(window, document); really means | Todd Motto](http://toddmotto.com/what-function-window-document-undefined-iife-really-means/)

* [Os segredos da IIFE | Da2k Blog](http://blog.da2k.com.br/2015/02/20/os-segredos-da-iife/) - 2015/02/20

* [Applicative Programming In JavaScript With lodash.js | Tech.Pro](http://tech.pro/tutorial/1611/functional-javascript)

--

* [[eBook] Professor Frisby's Mostly Adequate Guide to Function Programming | gitbooks](http://drboolean.gitbooks.io/mostly-adequate-guide/)

* [Functional programming with JavaScript | Minko Gechev's blog](http://blog.mgechev.com/2013/01/21/functional-programming-with-javascript/)

* [Functional programming with JavaScript, some concepts | dreyacosta](http://dreyacosta.com/functional-javascript/)

* [[SlideShare] Functional Programming Patterns (BuildStuff '14)](http://www.slideshare.net/ScottWlaschin/fp-patterns-buildstufflt)

* [[YouTube Playlist] Functional programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)

* Getting Functional with Javascript | Dave Atchley

  * [part 1](http://www.datchley.name/getting-functional-with-javascript-part-1/) | [part 2](http://www.datchley.name/getting-functional-with-javascript-part-2/) | [part 3](http://www.datchley.name/getting-functional-with-javascript-part-3/)

* [Functional Refactoring in JavaScript | Medium - Software Craftsman](https://medium.com/software-craftsman/functional-refactoring-in-javascript-c0fe718f4efb) - in too much detail

--

* [Higher-Order Functions | Eloquent JavaScript](http://eloquentjavascript.net/05_higher_order.html)

* [Functional and Object Oriented Programming with Higher Order Functions | Zsolt Nagy](http://www.zsoltnagy.eu/functional-and-object-oriented-programming-with-higher-order-functions/)

* [Entendendo Programação Funcional em JavaScript de uma vez | Medium - by @matheusml](https://medium.com/@matheusml/entendendo-programa%C3%A7%C3%A3o-funcional-em-javascript-de-uma-vez-c676489be08b)

--

* Functional JavaScript | Tech Pro

  * [Part 1: Introduction](http://tech.pro/tutorial/1953/functional-javascript-part-1-introduction)

  * [Part 2: What makes a language "functional"?](http://tech.pro/tutorial/2009/functional-javascript-part-2-what-makes-a-language-functional)

  * [Part 3: .apply(), .call(), and the arguments object](http://tech.pro/tutorial/2010/functional-javascript-part-3-apply-call-and-the-arguments-object)

--

* Felipe N Moura

  * [call, bind e apply no javascript parte 1](http://felipenmoura.org/articles/article/call-bind-e-apply-no-javascript-parte-1)

  * [call, bind e apply no javascript parte 2](http://felipenmoura.org/articles/article/call-bind-e-apply-no-javascript-parte-2)

--

* [JavaScript: arguments explained | Victor Quinn](http://blog.victorquinn.com/javascript-arguments-explained)

* [Optional parameters in Javascript | Mark Hansen](http://www.markhansen.co.nz/javascript-optional-parameters/) - Various ways of simplifying your Javascript API with optional parameters

--

* [Tips for using window in JavaScript | 2ality](http://www.2ality.com/2013/09/window.html)

--

* [[YouTube] Learn The Basics of JavaScript Scope](https://www.youtube.com/watch?v=ZoFlcv2ByBo)

* [Guide to JavaScript Prototypes, Scopes, and Performance | Toptal](http://www.toptal.com/javascript/javascript-prototypes-scopes-and-performance-what-you-need-to-know)

* [JavaScript: What the hell is this!? | VG Tech](http://tech.vg.no/2014/04/16/javascript-what-the-hell-is-this/)

--

* [Common Misconceptions About Inheritance in JavaScript — JavaScript Scene | Medium - Eric Elliott](https://medium.com/javascript-scene/common-misconceptions-about-inheritance-in-javascript-d5d9bab29b0a)

* [Understanding JavaScript Inheritance | Alex Sexton](http://alexsexton.com/blog/2013/04/understanding-javascript-inheritance/)

* [JavaScript: entendendo o this | Tableless](http://tableless.com.br/javascript-entendendo-o-this/) - Conheça mais sobre a palavra reservada this e entenda  como funciona o escopo de um objeto JavaScript.

* [Avoiding the *this* problem in JavaScript | Tech.Pro](http://tech.pro/tutorial/1192/avoiding-the-this-problem-in-javascript)

* [Demystifying *this*](http://toshsharma.github.io/presentation-this) - Understanding the 'this' keyword in JavaScript. by Ashutosh Sharma

* [Tutorial: Context or the "This" Keyword in JavaScript](https://thenewcircle.com/s/post/1564/context_or_the_this_keyword_in_javascript_tutorial) - 4 Screencasts Digging into JavaScript's “this”

* [Javascript without the "this" | Programming - O'Reilly Media](http://programming.oreilly.com/2014/03/javascript-without-the-this.html)

* [Understanding Scope and Context in JavaScript | Flippin' Awesome](http://flippinawesome.org/2013/08/26/understanding-scope-and-context-in-javascript/)

* [Closures: Front to Back | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/closures-front-to-back/)

* [Closures - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)

* [Closures are not magic | Rendered Text](http://renderedtext.com/blog/2015/11/18/closures-are-not-magic/) - 2015/11/18

--

* [An Introduction To DOM Events | Smashing Coding](http://coding.smashingmagazine.com/2013/11/12/an-introduction-to-dom-events/)

* [Rethinking DOM Traversal | Flippin' Awesome](http://flippinawesome.org/2014/05/12/rethinking-dom-traversal/)

--

* [Javascript - Usando temporizadores like a Ninja | Da2k Blog](http://blog.da2k.com.br/2015/01/29/javascript-usando-temporizadores-like-a-ninja/)

--

* [JSDares](http://www.jsdares.com/) - Experimental educational programming environment. Learn Javascript and create your own dares!

--

* [[GitHub] AlexNisnevich / untrusted](https://github.com/AlexNisnevich/untrusted) - A meta-JavaScript adventure game. Won first place at the Berkeley CSUA Spring 2013 Hackathon.

--

* [JavaScript Videos | Toptal](http://www.toptal.com/videos/front-end)

--

* [Javascript - entendendo e criando suas próprias Promises | Da2k Blog](http://blog.da2k.com.br/2015/03/05/javascript-entendendo-e-criando-suas-proprias-promises/)

* [Javascript - Criando um módulo Ajax com Promises - Parte 1 | Da2k Blog](http://blog.da2k.com.br/2015/03/06/javascript-criando-um-modulo-ajax-com-promises/)

* [Javascript - Criando um módulo Ajax com Promises - Parte 2 | Da2k Blog](http://blog.da2k.com.br/2015/03/08/javascript-criando-um-modulo-ajax-com-promises-parte-2/)

* [Javascript - Criando um módulo Ajax com Promises - Parte 3 | Da2k Blog](http://blog.da2k.com.br/2015/03/11/javascript-criando-um-modulo-ajax-com-promises-parte-3/)

* [Javascript - Criando um módulo Ajax com Promises - Parte 4 | Da2k Blog](http://blog.da2k.com.br/2015/03/14/javascript-criando-um-modulo-ajax-com-promises-parte-4/)

--

* [[GitHub] github / fetch](https://github.com/github/fetch) - A window.fetch JavaScript polyfill

* [Introduction to the Fetch API | SitePoint](http://www.sitepoint.com/introduction-to-the-fetch-api/) - 2015/07/02

* [Fetch API - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)

* [Adeus jQuery.ajax. Olá Fetch API. | VivaReal Engenharia](http://engenharia.vivareal.com.br/adeus-jquery-ajax-ola-fetch-api/)

* [Fetch API e o JavaScript | BrazilJS](https://braziljs.org/blog/fetch-api-e-o-javascript/) - 2016/04/10


### OOP

* [Prototypes Are Not Classes](http://raganwald.com/2014/01/19/prototypes-are-not-classes.html)

* [Class Hierarchies? Don't Do That! | raganwald.com](http://raganwald.com/2014/03/31/class-hierarchies-dont-do-that.html)

--

* [Object-Oriented JavaScript - Presentation Slides](http://jordankasper.com/preso/oop-js)

* [OOP In JavaScript: What You NEED to Know](http://javascriptissexy.com/oop-in-javascript-what-you-need-to-know/)

* [JS Objects: Inherited a Mess](http://davidwalsh.name/javascript-objects)

* [Object Playground : The Definitive Guide to Object-Oriented JavaScript](http://www.objectplayground.com/)

* [Understanding JavaScript Inheritance | Alex Sexton](https://alexsexton.com/blog/2013/04/understanding-javascript-inheritance/)

* [Reaproveitando código com JavaScript: herança e protótipos | Caelum](http://blog.caelum.com.br/reaproveitando-codigo-com-javascript-heranca-e-prototipos/)

* [Simple inheritance with JavaScript | Eternal Coding - MSDN Blogs](http://blogs.msdn.com/b/eternalcoding/archive/2014/08/20/simple-inheritance-with-javascript.aspx)

--

* [Topiarist: A JavaScript OO library featuring mixins, interfaces & multiple inheritance | BladeRunnerJS](http://bladerunnerjs.org/blog/topiarist/)


### Padrões

* [Popular Coding Convention on Github - JavaScript](http://sideeffect.kr/popularconvention#javascript)

--

* [Six reasons to define constructors with only one argument | Giulio Canti](https://gcanti.github.io/2014/09/25/six-reasons-to-define-constructors-with-only-one-argument.html) - 2014/09/25

--

* [Principles of Writing Consistent, Idiomatic JavaScript](https://github.com/rwldrn/idiomatic.js)

* [JavaScript Best Practices | CodeProject](http://www.codeproject.com/Articles/580165/JavaScript-Best-Practices)

* [JavaScript Patterns Collection](http://shichuan.github.com/javascript-patterns/)

* [JavaScript: Function Invocation Patterns](http://doctrina.org/Javascript-Function-Invocation-Patterns.html)

* [Learning JavaScript Design Patterns | A book by Addy Osmani](http://addyosmani.com/resources/essentialjsdesignpatterns/book/)

* [Smart JavaScript Techniques and Patterns](http://www.onextrapixel.com/2013/02/21/improve-your-code-with-smart-javascript-techniques-and-patterns/)

* [The Essentials of Writing High Quality JavaScript | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/the-essentials-of-writing-high-quality-javascript/)

* [Writing third-party Javascript | Frontend and beyond — Medium](https://medium.com/frontend-and-beyond/2808a8d85a0a)

* [JavaScript API and its Design Principles | Speaker Deck](https://speakerdeck.com/ariya/javascript-api-and-its-design-principles)

--

* [Design Patterns em JavaScript | Front In Brazil](http://frontinbrazil.com.br/design-patterns-em-javascript/) - 2015/08/21

--

* Simples Ideias

  * [Design Patterns no JavaScript – Singleton](http://simplesideias.com.br/design-patterns-no-javascript-singleton)

  * [Design Patterns no JavaScript – Factory](http://simplesideias.com.br/design-patterns-no-javascript-factory)

  * [Design Patterns no JavaScript – Decorator](http://simplesideias.com.br/design-patterns-no-javascript-decorator)

--

* [JavaScript Design Patterns | Carl Danley](http://carldanley.com/javascript-design-patterns/)

  * [The Module Pattern](http://carldanley.com/js-module-pattern/)

  * [The Revealing Module Pattern](http://carldanley.com/js-revealing-module-pattern/)

  * [The Singleton Pattern](http://carldanley.com/js-singleton-pattern/)

  * [The Observer Pattern](http://carldanley.com/js-observer-pattern/)

  * [The Mediator Pattern](http://carldanley.com/js-mediator-pattern/)

  * [The Prototype Pattern](http://carldanley.com/js-prototype-pattern/)

  * [The Facade Pattern](http://carldanley.com/js-facade-pattern/)

  * [The Factory Pattern](http://carldanley.com/js-factory-pattern/)

--

* 7 Patterns to Refactor JavaScript Applications | Crush & Lovely

  * [Value Objects](http://journal.crushlovely.com/post/88286828068/7-patterns-to-refactor-javascript-applications-value)

  * [Service Objects](http://journal.crushlovely.com/post/88286835473/7-patterns-to-refactor-javascript-applications-service)

  * [Form Objects](http://journal.crushlovely.com/post/89270334848/7-patterns-to-refactor-javascript-applications-form)

  * [Query Objects](http://journal.crushlovely.com/post/89978453593/7-patterns-to-refactor-javascript-applications-query)

  * [View Objects](http://journal.crushlovely.com/post/90568548968/7-patterns-to-refactor-javascript-applications-view)

  * [Policy Objects](http://journal.crushlovely.com/post/91371788978/7-patterns-to-refactor-javascript-applications-policy)

  * Decorators

--

* [JavaScript Observer (Publish/Subscribe) Pattern](http://bumbu.ru/javascript-observer-publish-subscribe-pattern/)

  * [Creating a simple Javascript pub sub | Weslley Araujo](https://weslleyaraujo.github.io/javascript/2015/02/11/creating-a-simple-javascript-pub-sub.html)

* [[GitHub] belfz / PurrSub.js](https://github.com/belfz/PurrSub.js) - An ultra-light, pub-sub module.

--

* [A Deep Dive Into JavaScript Modules](http://toshsharma.github.io/presentation-js-modules) - by Ashutosh Sharma / @zorder

* [JavaScript encapsulation & the module pattern](http://www.aviyehuda.com/blog/2013/01/12/javascript-encapsulation-the-module-pattern-for-beginners/)

* [JavaScript Namespaces and Modules | Kenneth Truyers](http://www.kenneth-truyers.net/2013/04/27/javascript-namespaces-and-modules/)

* [Scalable JavaScript Design Patterns](http://www.addyosmani.com/scalablejs/)

* [Modularização em JavaScript | Tableless](http://tableless.com.br/modularizacao-em-javascript/) - Componentes e módulos nunca foram tão mencionados como ultimamente. Ambos são conceitos antigos que devemos entender e passar a adotar o quanto antes. Quem sabe você possa repensar o seu JavaScript hoje mesmo?

* [Mastering the Module Pattern | Todd Motto](http://toddmotto.com/mastering-the-module-pattern/)

--

* [Implementing Private and Protected Members in JavaScript | Philip Walton](http://philipwalton.com/articles/implementing-private-and-protected-members-in-javascript/)

* [Structs and ImmutableStructs | raganwald.com](http://raganwald.com/2014/06/15/immutable-structs.html)

--

* [A meta style guide for JavaScript | 2ality](http://www.2ality.com/2013/07/meta-style-guide.html)

* [Google JavaScript Style Guide](https://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)

* [[GitHub] rwaldron / idiomatic.js](https://github.com/rwaldron/idiomatic.js) - Principles of Writing Consistent, Idiomatic JavaScript

* [Meteor Style Guide](https://github.com/meteor/meteor/wiki/Meteor-Style-Guide)

* [jsCode](http://jscode.org/) - Custom JavaScript Coding Guidelines

* [JSCS](http://jscs.info/) — JavaScript Code Style

  * [Auto-formatting JavaScript Code Style | Medium - by @addyosmani](https://medium.com/@addyosmani/auto-formatting-javascript-code-style-fe0f98a923b8)

--

* [How to Start Flowing with Flow-based Programming | CoLab Coop](https://colab.coop/blog/how-to-start-flowing-with-flow-based-programming/) - 2015/08/29


### Dicas

* [Learning to Use Google Analytics More Effectively at CodePen | CSS-Tricks](https://css-tricks.com/learning-use-google-analytics-effectively-codepen/)

* [[YouTube] CSS-Tricks Screencast #146: Getting More from Analytics](https://www.youtube.com/watch?v=jSHqlFkJiBI) - 2016/03/07

--

* [[GitHub] loverajoel / jstips](https://github.com/loverajoel/jstips) - This is about one JS tip every day!

* [JS Nice](http://jsnice.org/) - statistical renaming, type inference and deobfuscation

--

* [Determine If A Number Is Prime Using JavaScript](https://blog.nraboy.com/2015/04/determine-if-a-number-is-prime-using-javascript/)

--

* [Medindo a complexidade do seu código JavaScript | Tableless](http://tableless.com.br/medindo-a-complexidade-ciclomatica-do-seu-codigo-javascript/)

* [Defensive JavaScript](http://www.defensivejs.com/)

* [Javascript Hacks for Hipsters | Tal Bereznitskey](http://berzniz.com/post/68001735765/javascript-hacks-for-hipsters)

--

* [label - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/label)

--

* [Javascript Char Codes (Key Codes)](http://www.cambiaresearch.com/articles/15/javascript-char-codes-key-codes)

* [Unicode and JavaScript | 2 ality](http://www.2ality.com/2013/09/javascript-unicode.html)

* [JavaScript ❤ Unicode | FluentConf](http://fluentconf.com/javascript-html-2015/public/content/2015/02/18-javascript-loves-unicode) - JavaScript, HTML5, CSS3 Conference - O'Reilly Fluent, April 20 - 22, 2015, San Francisco, CA

* [Checking whether a value is an integer in JavaScript | 2 ality](http://www.2ality.com/2014/05/is-integer.html)

--

* [Binary in Javascript | @workshydev](http://danthedev.com/2015/07/25/binary-in-javascript/) - 2015/07/25

--

* [Data-binding Revolutions with Object.observe | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/es7/observe/)

* [Two-Way Data Binding | Nikita Vasilyev](http://n12v.com/2-way-data-binding/) - Let’s build a temperature converter app in Backbone, React, Angular, Meteor and vanilla JavaScript.

--

* [Super useful JavaScript functions | RevillWeb](http://www.revillweb.com/tutorials/super-useful-javascript-functions/)

* [Of how to implement transient in JavaScript | Paul Masurel](http://fulmicoton.com/posts/transient/) - Java programmers are probably familiar with the concept of transient as it is a keyword in this language. By marking an object property as transient, you tell Java that this property should be skipped in serialization.

* [JavaScript Once Function | David Walsh](http://davidwalsh.name/javascript-once) - Learn how to ensure your function fires only once with JavaScript!

--

* [The JavaScript console API | 2 ality](http://www.2ality.com/2013/10/console-api.html)

* [5 functions of the Console object you didn’t know | Shelly Cloud](https://shellycloud.com/blog/2014/11/five-functions-of-the-console-object-you-didnt-know)

* [JavaScript Debugging Tips and Tricks | Zsolt Nagy](http://www.zsoltnagy.eu/javascript-debugging-tips-and-tricks/)

--

* [7 JavaScript Basics Many Developers Aren't Using (Properly) | Tech.Pro](http://tech.pro/tutorial/1453/7-javascript-basics-many-developers-aren-t-using-properly)

* [An interesting kind of JavaScript memory leak | Meteor Blog](http://www.meteor.com/blog/2013/08/13/an-interesting-kind-of-javascript-memory-leak)

* [Native equivalents of jQuery functions | Lee Brimelow](http://www.leebrimelow.com/native-methods-jquery/)

* [Useful JavaScript Libraries and jQuery Plugins](http://coding.smashingmagazine.com/2012/09/23/useful-javascript-libraries-jquery-plugins-web-developers/)

* [Javascript Territory - Jster Javascript Catalog](http://jster.net/)

* [SuperAgent - Ajax with less suck](http://visionmedia.github.com/superagent/)

--

* [Optimize Your Workflow: JavaScript Tools and Libraries](http://www.joezimjs.com/javascript/optimize-your-workflow-javascript-tools-and-libraries/)

* [[Speaker Deck] Front-end Tooling Workflows](https://speakerdeck.com/addyosmani/front-end-tooling-workflows) - 2014/11/09

--

* [A guide to publishing JavaScript open source projects | Nightlight](http://www.conductor.com/nightlight/guide-publishing-javascript-open-source-projects/)

--

* [Capturando erros JS LIKE-A-BOSS | Tableless](http://tableless.com.br/capturando-erros-js-like-a-boss/) - window.onerror

* [Capture and report JavaScript errors with window.onerror | Sentry](http://blog.getsentry.com/2016/01/04/client-javascript-reporting-window-onerror.html) - 2016/01/04

* [Strange JavaScript Errors and How to Fix Them | David Walsh Blog](http://davidwalsh.name/fix-javascript-errors)

* [Rethinking JavaScript's Try/Catch | Flippin Awesome](http://flippinawesome.org/2013/09/30/rethinking-javascripts-trycatch/)

--

* [The Dangers of Stopping Event Propagation | CSS-Tricks](http://css-tricks.com/dangers-stopping-event-propagation/)

* [JavaScript Events: Save the Bubbles! | David Walsh Blog](http://davidwalsh.name/javascript-events)

* [Browser Input Events: Can We Do Better Than The Click? | Smashing Magazine](http://www.smashingmagazine.com/2015/03/20/better-browser-input-events/)

--

* [Concurrency in JavaScript | ByteArray.org](http://www.bytearray.org/?p=5607)

* [Handling concurrency and asynchronous JavaScript | Oliver.prototype.blog](http://oli.me.uk/2013/09/11/handling-concurrency-and-asynchronous-javascript/)

--

* [Asynchronous Programming in the browser | Dave Atchley](http://www.datchley.name/asynchronous-in-the-browser/)

--

* [[GitHub] bevacqua / promisees](https://github.com/bevacqua/promisees) - Promise visualization playground for the adventurous

* [Callback Hell](http://callbackhell.com/) - A guide to writing elegant asynchronous javascript programs

* [Staying Sane With Asynchronous Programming: Promises and Generators | colintoh.com](http://colintoh.com/blog/staying-sane-with-asynchronous-programming-promises-and-generators) - Callback Hell no more with Promises and its close ally, Generators.

* [Asynchronous JavaScript Interfaces (Events, Generators, Promises, Streams)](http://medikoo.com/asynchronous-javascript-interfaces/?notes)

* [JavaScript Promises: There and back again | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/es6/promises/)

* [Callbacks, Promises, Signals and Events | Miller Medeiros](http://blog.millermedeiros.com/callbacks-promises-signals-and-events/)

* [Asynchronous JavaScript and Promises | InnoArchiTech](https://medium.com/innoarchitech-innovation-architecture-technology/asynchronous-javascript-and-promises-be4efecf247b)

* [Programação assíncrona com JavaScript | TDC2013 | InfoQ BR](http://www.infoq.com/br/presentations/programacao-assincrona-javascript) - Essa palestra trata de de algumas técnicas de programação assíncrona com JavaScript, principalmente com Callbacks, Futures e Promisses, e Functional Reactive Programming

* [Write Better JavaScript with Promises | David Walsh](http://davidwalsh.name/write-javascript-promises)

  * [Escreva códigos JavaScript melhores com Promises | iMasters](http://imasters.com.br/front-end/javascript/escreva-codigos-javascript-melhores-com-promises/)

* [Patterns for Asynchronous Programming with Promises | Joe Zim's JavaScript Blog](http://www.joezimjs.com/javascript/patterns-asynchronous-programming-promises/)

* [Promises and Error Handling | Making Change.org](http://making.change.org/post/69613524472/promises-and-error-handling)

* [[GitHub] mattdesl / promise-cookbook](https://github.com/mattdesl/promise-cookbook) - a brief introduction to using Promises in JavaScript

--

* [[GitHub] kriskowal / q](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises in JavaScript

* [async](http://bredele.github.io/async/) - A collection of asynchronous patterns for nodejs and browsers

* [promisejs.org](http://www.promisejs.org/) - Introducing the concept of Promises in JavaScript

  * [AMD loader in 30 lines of code](http://curiosity-driven.org/amd-loader-with-promises)

--

* [[YouTube] Netflix JavaScript Talks - Async JavaScript with Reactive Extensions](https://www.youtube.com/watch?v=XRYN2xt11Ek)

* [[Gist]  staltz / introrx.md](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754) - The introduction to Reactive Programming you've been missing

--

* [JS Packer](http://iwantaneff.in/packer/) - compress your Javascript to a tiny file-size

* [JavaScript Byte saving techniques](https://github.com/jed/140bytes/wiki/Byte-saving-techniques)

--

* [Introduction to Map and Reduce in Javascript](http://www.49lights.com/blogg/2013/05/introduction_to_map_and_reduce_in_javascript/)

* [Reducing Filter and Map Down to Reduce | Web Dev .NET](http://www.elijahmanor.com/2013/08/reducing-filter-and-map-down-to-reduce.html)

--

* [Fun with Javascript and function tracing](http://ebobby.org/2013/05/18/Fun-with-Javascript-and-function-tracing.html)

* [Dynamically removing and replacing an external JavaScript or CSS file](http://www.javascriptkit.com/javatutors/loadjavascriptcss2.shtml)

* [Extract info from a web page using JavaScript | Dan Goldin](http://dangoldin.com/2013/08/26/extract-info-from-a-web-page-using-javascript/)

--

* [Parse With The Shunting Yard Algorithm Using JavaScript | Nic Raboy's Code Blog](https://blog.nraboy.com/2015/03/parse-with-the-shunting-yard-algorithm-using-javascript/) - Parse an infix notation equation to reverse polish notation (RPN) using the Shunting Yard algorithm and JavaScript. Prepares for solving math expressions.

--

* [Numbers and JavaScript's Dot Notation | Design Pepper](http://designpepper.com/blog/drips/numbers-and-javascripts-dot-notation)

* [What Every JavaScript Developer Should Know About Floating Points | Flippin' Awesome](http://flippinawesome.org/2014/02/17/what-every-javascript-developer-should-know-about-floating-points/)

* [Random Number Generation in JavaScript | Bocoup](http://weblog.bocoup.com/random-numbers/)

* [Prime Numbers, Factorial, and Fibonacci Series with JavaScript Array](http://ariya.ofilabs.com/2013/07/prime-numbers-factorial-and-fibonacci-series-with-javascript-array.html)

--

* [Date and time in JavaScript | Tech.pro](http://tech.pro/tutorial/2468/date-and-time-javascript)

--

* [Exploring the Abyss of Null and Undefined in JavaScript | Flippin' Awesome](http://flippinawesome.org/2013/12/09/exploring-the-abyss-of-null-and-undefined-in-javascript/)

--

* [Searching with Array.prototype.some](http://ariya.ofilabs.com/2013/08/searching-with-array-prototype-some.html) - ECMAScript 5.1

* [How to remove an element from an array | Simone Web Design](http://simonewebdesign.it/blog/how-to-remove-element-from-array/)

* [Filtering Arrays with Array#filter | Design Pepper](http://designpepper.com/blog/drips/filtering-arrays-with-array-filter)

* [Fun with Native Arrays | Pony Foo](http://blog.ponyfoo.com/2013/11/19/fun-with-native-arrays)

* [Ditch the [].forEach.call(NodeList) hack | toddmotto](http://toddmotto.com/ditch-the-array-foreach-call-nodelist-hack/)

* [Combining JS Arrays | David Walsh](http://davidwalsh.name/combining-js-arrays)

* [Fun with Native Arrays | ponyfoo](https://ponyfoo.com/articles/fun-with-native-arrays)

--

* [Understanding recursion in functional JavaScript programming | Integralist BBC News Engineer](http://www.integralist.co.uk/posts/understanding-recursion-in-functional-javascript-programming/)

--

* [[GitHub] joewalnes / filtrex](https://github.com/joewalnes/filtrex) - A simple, safe, JavaScript Filter Expression compiler for end-users

--

* [A Spreadsheet in 295 bytes of JavaScript](http://aem1k.com/sheet/)

* [[JSFiddle] Tiny Excel-like app in vanilla JS](http://jsfiddle.net/ondras/hYfN3/)

--

* [[GitHub] mauriciosantos / buckets](https://github.com/mauriciosantos/buckets) - A complete, fully tested and documented data structure library written in JavaScript

* [Using Underscore/Lo-Dash and stopping reinvent the wheel | 4waisenkinder](http://4waisenkinder.de/blog/2013/10/12/you-use-underscore-slash-lo-dash/) | [underscore](http://underscorejs.org/) / [lo-dash](http://lodash.com/)

  * [Stop writing For loops. Start using underscore | @jhooks](http://www.joelhooks.com/blog/2014/02/06/stop-writing-for-loops-start-using-underscorejs/)

  * [Underscore.js: a Biblioteca JavaScript que Você Precisa Conhecer | JustCode](http://blog.glaucocustodio.com/2014/02/08/underscore-js-a-biblioteca-javascript-que-voce-precisa-conhecer/)

  * [[GitHub] cht8687 / You-Dont-Need-Lodash-Underscore](https://github.com/cht8687/You-Dont-Need-Lodash-Underscore) - Lists of Javascript methods which you can use natively

  * [You Might Not Need Underscore | Reindex](https://www.reindex.io/blog/you-might-not-need-underscore/)

    * [Lodash ou Underscore? Talvez, nenhum! | Medium by @oieduardorabelo](https://medium.com/@oieduardorabelo/lodash-ou-underscore-talvez-nenhum-4d1534775a2d)


* [[GitHub] elclanrs / essential.js](https://github.com/elclanrs/essential.js) - Functional JavaScript "the right way"

* [Object Equality in JavaScript | Design Pepper](http://designpepper.com/blog/drips/object-equality-in-javascript.html)

* [Equality in JavaScript | JS Comparison Table](http://dorey.github.io/JavaScript-Equality-Table/unified/)

* [Understanding JavaScript types and reliable type checking | Todd Motto](http://toddmotto.com/understanding-javascript-types-and-reliable-type-checking/)

--

* [[Speaker Deck] Categorizing values: typeof, instanceof and beyond | Axel Rauschmayer](https://speakerdeck.com/rauschma/categorizing-values-typeof-instanceof-and-beyond) - You have probably heard of two common ways of categorizing values in JavaScript: typeof and instanceof. In this talk, we first review the basics of this kind of categorization and then move on to quirks and advanced topics: primitive values versus objects; typeof and instanceof (and their quirks); the internal property [[Class]]; the odd nature of the prototypes of built-in constructors; and more.

* [Get Most Out of JavaScript Data Structures | JSter Javascript Catalog](http://jster.net/blog/javascript-data-structures)

* [Sorting Algorithms in JavaScript | Ben's Blog](http://blog.benoitvallon.com/category/sorting-algorithms-in-javascript/)

* [Sorted Maps in JavaScript | JSter Javascript Catalog](http://jster.net/blog/sorted-maps-in-javascript)

* [Protecting objects in JavaScript | 2ality](http://www.2ality.com/2013/08/protecting-objects.html)

* [Javascript’s call v apply v bind — The JavaScript Collection | Medium](https://medium.com/the-javascript-collection/9e6122cde639)

* [Currying in Javascript — The JavaScript Collection | Medium](https://medium.com/the-javascript-collection/ce6da2d324fe)

--

* [Determining if a String Contains a Substring | Design Pepper](http://designpepper.com/blog/drips/determining-if-a-string-contains-another-string-in-javascript-three-approaches)

* [Using String Replace in JavaScript | David Walsh](http://davidwalsh.name/string-replace-javascript)

--

* [Getting input from the keyboard using JavaScript | ANTONOFF](http://www.antonoffplus.com/getting-input-from-the-keyboard-using-javascript/)

--

* [[GitHub] vlandham / js_data](https://github.com/vlandham/js_data) - Data manipulation and processing in JavaScript | [LearnJSData](http://learnjsdata.com/)

--

* [Convert XML to JSON with JavaScript | David Walsh](http://davidwalsh.name/convert-xml-json)

--

* [[GitHub] gmarty / DVD.js](https://github.com/gmarty/DVD.js) - Playing DVD in JavaScript for the sake of interoperability

--

* [[GitHub] felipernb / algorithms.js](https://github.com/felipernb/algorithms.js) - Atwood's Law applied to CS101 - Classic algorithms and data structures implemented in JavaScript

--

* [Sending Emails with the Gmail JavaScript API | SitePoint](http://www.sitepoint.com/sending-emails-gmail-javascript-api/) - 2016/02/15


### Expressões Regulares

* [Regular Expressions Cheat Sheet by DaveChild](http://www.cheatography.com/davechild/cheat-sheets/regular-expressions/)

* [Regex #1: CheatSheet for JavaScript | Gentlenode Studio - Journal](http://journal.gentlenode.com/regex-1-cheatsheet-for-javascript/)

--

* [JavaScript RegExp Object | w3schools.com](http://www.w3schools.com/jsref/jsref_obj_regexp.asp)

* [Regular expressions in JavaScript - Dive Into JavaScript](http://www.diveintojavascript.com/articles/javascript-regular-expressions)

* [JavaScript: an overview of the regular expression API | 2ality](http://www.2ality.com/2011/04/javascript-overview-of-regular.html)

* [Regular Expressions - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/JavaScript/Guide/Regular_Expressions)

* Regular Expressions in JavaScript [part 1](http://james.padolsey.com/javascript/regular-expressions-in-javascript/) | [part 2](http://james.padolsey.com/javascript/regular-expressions-in-javascript-part-2/)

* [The empty regular expression](http://www.2ality.com/2012/09/empty-regexp.html)

* [JavaScript Regex: String Does Not Contain | DWB](http://davidwalsh.name/javascript-regex-string)

* [The flag /g of JavaScript’s regular expressions | 2 ality](http://www.2ality.com/2013/08/regexp-g.html)

* [JavaScript Regular Expressions patterns](http://www.javascriptkit.com/javatutors/redev2.shtml)

* [10+ Useful JavaScript Regular Expression Functions to improve your web applications efficiency](http://ntt.cc/2008/05/10/over-10-useful-javascript-regular-expression-functions-to-improve-your-web-applications-efficiency.html)

* [JavaScript Regular Expression Enlightenment |  Tech.Pro](http://tech.pro/tutorial/1214/javascript-regular-expression-enlightenment)

* [[GitHub] jehna / VerbalExpressions](https://github.com/jehna/VerbalExpressions) - JavaScript Regular expressions made easy

* [[GitHub] slevithan / xregexp](https://github.com/slevithan/xregexp) - Extended JavaScript regular expressions


#### Expressões Regulares: Ferramentas online

* [RegExr](http://regexr.com/) - Create & Test Regular Expressions

  * [[GitHub] gskinner / regexr](https://github.com/gskinner/regexr) - is a HTML/JS based tool for creating, testing, and learning about Regular Expressions

* [Regulex](https://jex.im/regulex/) - JavaScript Regular Expression Visualizer.

* [Scriptular is a javascript regular expression editor](http://scriptular.com/) - online

* [Regexper](http://www.regexper.com/) - Regular expression visualizer using railroad diagrams

* [Debuggex: A beautiful visual regex tester](http://www.debuggex.com/)

* [Build RegEx](http://buildregex.com/)

* [regex101](http://regex101.com/#javascript)


### Performance

* [[YouTube] Google Tech Talks 2009 : Speed Up Your JavaScript](https://www.youtube.com/watch?v=mHtdZgou0qU)

* [[YouTube] Google I/O 2012 – Breaking the JavaScript Speed Limit with V8](https://www.youtube.com/watch?v=UJPdhx5zTaw)

--

* [Native Speed on the Web: JavaScript and asm.js | Alon Zakai](http://kripken.github.io/mloc_emscripten_talk/sloop.html)

* [Fast C++ on the Web using Emscripten and asm.js | Alon Zakai](http://kripken.github.io/mloc_emscripten_talk/gindex.html)

--

* [Web Tracing Framework by Google](http://google.github.io/tracing-framework/) - Rich tools for instrumenting, analyzing, and visualizing web apps | [Github project](http://google.github.io/tracing-framework/)

    * [Web Tracing framework do Google ajuda você se livrar do código porco | Igor Costa](http://www.igorcosta.com/web-tracing-framework-do-google-codigo-porco/)

--

* [jsPerf: JavaScript performance playground](http://jsperf.com/)

* [Panzer Dragoon 1k - JS1K size optimizations tricks](http://greweb.me/2014/03/panzer-dragoon-1k/) - Panzer Dragoon 1k is a 2D remake of Panzer Dragoon in 1k of JavaScript I made for JS1K 2014

* [JavaScript Performance Tips & Tricks | Modus Create](https://moduscreate.com/javascript-performance-tips-tricks/)

* [Building High-Performing JavaScript for Modern Engines | Build 2012 | Channel 9](http://channel9.msdn.com/Events/Build/2012/4-000)

* [Pimp my JS: +200% of performance | Pics.io](http://blog.pics.io/sneak-peeks/pimp-my-js-200-of-performance/)

* [Stop Writing Slow Javascript | I Like Kill Nerds](http://ilikekillnerds.com/2015/02/stop-writing-slow-javascript/)

--

* [Effectively Managing Memory at Gmail scale | HTML5 Rocks](http://www.html5rocks.com/en/tutorials/memory/effectivemanagement/)

--

* [[Speaker Deck] Efficient JavaScript](https://speakerdeck.com/volkan/efficient-javascript)

* [How to Give Your Web Apps a Real Speed Boost | TNW Network](http://thenextweb.com/apps/2013/10/20/give-web-apps-real-speed-boost/)

* [[SlideShare] 5 Tips for Better JavaScript](http://www.slideshare.net/toddanglin/5-tips-for-better-javascript)

* [3 reasons why you should let Google host jQuery for you - Encosia](http://encosia.com/3-reasons-why-you-should-let-google-host-jquery-for-you/)

* [Writing Fast, Memory-Efficient JavaScript | Smashing Coding](http://coding.smashingmagazine.com/2012/11/05/writing-fast-memory-efficient-javascript/)

* [Vazamento de memória em JavaScript | Loop Infinito](http://loopinfinito.com.br/2013/04/19/vazamento-de-memoria-em-javascript/) - Aprenda o que é um vazamento de memória, como identificar um vazamento de memória e como funciona a alocação, uso e liberação de memória no JavaScript.

* [[Slid.es] memory by Gonzalo Ruiz de Villa](http://slid.es/gruizdevilla/memory) - Finding and debugging memory leaks in JavaScript with Chrome DevTools

* [[PDF] Erik Corry: Optimization With V8 JavaScript](http://gotocon.com/dl/jaoo-aarhus-2010/slides/ErikCorry_OptimizationWithV8JavaScript.pdf)

* [Performance Optimizing for Smart Layers | AddThis Blog](http://www.addthis.com/blog/2013/09/17/performance-optimizing-for-smart-layers/)

* [Why I favor while loops](http://blog.millermedeiros.com/why-i-favor-while-loops/)

* [Faster String#repeat method, with ancient Egyptian theory | CoderKeen](http://coderkeen.com/javascript/faster-stringrepeat-method-with-ancient-egyptian-theory)

* [JavaScript object pooling | Qoopido](http://www.qoopido.com/articles/javascript-object-pooling/)

* [How to really defer loading javascript](http://www.feedthebot.com/pagespeed/defer-loading-javascript.html) - Deferring javascript using the method recommended by Google allows for quicker crisper page loads

* [[Speaker Deck] JavaScript Widget Development Best Practices](https://speakerdeck.com/volkan/javascript-widget-development-best-practices)

* [Journey of Discovery - the Global 'window.performance' Object | 4waisenkinder](http://4waisenkinder.de/blog/2013/11/10/discovery-of-window-dot-performance-dot-timing/)

* [Qual a dose certa de JavaScript | Tableless](http://tableless.com.br/qual-dose-certa-de-javascript/) - Um pouco de JavaScript não obstrusivo e quais as estratégias para garantir uma boa performance e acessibilidade em aplicações ricas.

* [The seven rules of unobtrusive JavaScript | Dev.Opera](http://dev.opera.com/articles/view/the-seven-rules-of-unobtrusive-javascrip/)

--

* [Speed up recursive functions with memoization | JSTips](http://www.jstips.co/en/speed-up-recursive-functions-with-memoization/) - 2016/01/29

--

* [NBEAM: How I Wrote an Ultra-Fast DNA Sequence Alignment Algorithm in JavaScript | Medium - Keith Horwood](https://medium.com/@keithwhor/nbeam-how-i-wrote-an-ultra-fast-dna-sequence-alignment-algorithm-in-javascript-c199e936da)

  * [[GitHub] keithwhor / NtSeq](https://github.com/keithwhor/NtSeq) - JavaScript (node + browser) bioinformatics library for nucleotide sequence manipulation and analysis.


#### Compressão

* [UglifyJS](http://lisperator.net/uglifyjs/)

  * [Better Compression with UglifyJS | David Walsh Blog](http://davidwalsh.name/compress-uglify)


#### Ordenação

* [Sorting Algorithm Visualization | Thinking in Crowd](http://www.thinkingincrowd.me/algorithm/)


### Sistema de Dependências e Módulos

* [The mind-boggling universe of JavaScript Module strategies | airpair](https://www.airpair.com/javascript/posts/the-mind-boggling-universe-of-javascript-modules) - This article exposes the foundations of different JavaScript Module strategies such as ad hoc, CommonJS, AMD and ES6 modules, and how to get started with ES6 modules right now.

--

* [JavaScript Module Systems Showdown: CommonJS vs AMD vs ES2015 | Auth0](https://auth0.com/blog/2016/03/15/javascript-module-systems-showdown/) - 2016/03/15

* [Javascript Modules, AMD, and the road ahead. | Yahoo Engineering](http://yahooeng.tumblr.com/post/62383009835/javascript-modules-amd-and-the-road-ahead)

* [[GitHub] wilmoore / frontend-packagers](https://github.com/wilmoore/frontend-packagers) - Front-End Package Manager Comparison

--

* [[GitHub] umdjs / umd](https://github.com/umdjs/umd) - UMD (Universal Module Definition) patterns for JavaScript modules that work everywhere

  * [[GitHub] alexlawrence / grunt-umd](https://github.com/alexlawrence/grunt-umd) - Surrounds code with the universal module definition

* [[GitHub] systemjs / systemjs](https://github.com/systemjs/systemjs) - Universal dynamic module loader

* [Mantri](http://mantrijs.com/) - JavaScript Dependency System

* [[GitHub] jspm / jspm-loader](https://github.com/jspm/jspm-loader) - AMD, CJS & ES6 spec-compliant module loader

  * [jspm.io](http://jspm.io/) - Frictionless Browser Package Management


* [BoxJS](http://boxjs.com/) - A simple package management service


* [Duo.js](http://duojs.org/) - is a next-generation package manager that blends the best ideas from Component, Browserify and Go to make organizing and writing front-end code quick and painless.

  * [[GitHub] duojs / duo](https://github.com/duojs/duo) - A next-generation package manager for the front-end

  * [Duo.js: módulos no frontend de forma simples e direta | Fabio Vedovelli](http://www.vedovelli.com.br/web-development/duo-js-modulos-no-frontend-de-forma-simples-e-direta/)


#### Webpack

* [[GitHub] webpack / webpack](https://github.com/webpack/webpack) - Packs CommonJs/AMD modules for the browser. Allows to split your codebase into multiple bundles, which can be loaded on demand. Support loaders to preprocess files, i.e. json, jade, coffee, css, less, ... and your custom stuff.

* [[GitHub] shama / gulp-webpack](https://github.com/shama/gulp-webpack) - webpack plugin for gulp

--

* [[GitHub] ruanyf / webpack-demos](https://github.com/ruanyf/webpack-demos) - a collection of simple demos of Webpack

* [[GitHub] topheman / webpack-babel-starter](https://github.com/topheman/webpack-babel-starter) - Webpack / Babel starter kit with full development & build workflow

--

* [The ultimate webpack setup | christianalfoni](http://www.christianalfoni.com/articles/2015_04_19_The-ultimate-webpack-setup) - 2015/04/19

  * [[GitHub] christianalfoni / webpack-express-boilerplate](https://github.com/christianalfoni/webpack-express-boilerplate) - A boilerplate for running a Webpack workflow in Node express

* [Webpack 2 Tree Shaking Configuration | Modus Create: Front End Development - Medium](https://medium.com/modus-create-front-end-development/webpack-2-tree-shaking-configuration-9f1de90f3233)

  * [[GitHub] ModusCreateOrg / budgeting-sample-app-webpack2](https://github.com/ModusCreateOrg/budgeting-sample-app-webpack2) - Budgeting - React + Redux + Webpack 2 (tree shaking) Sample App

* [Webpack FTW!!!! | k94n](https://k94n.com/webpack-ftw) - 2016/03/14

  * [[Speaker Dev] Webpack FTW](https://speakerdeck.com/k9ordon/webpack-ftw)

--

* [Browserify VS Webpack - JS Drama | Naman Goel](http://blog.namangoel.com/browserify-vs-webpack-js-drama)


#### Browserify

* [Browserify](http://browserify.org/)

* [Introduction to Browserify | Blake Embrey](http://blakeembrey.com/articles/introduction-to-browserify/)

* [Getting Started with Browserify | SitePoint](http://www.sitepoint.com/getting-started-browserify/) - This article introduces the Browserify tool. It also shows how Browserify can be integrated with Grunt and Gulp

* [A Gentle Browserify Walkthrough | Pony Foo](http://ponyfoo.com/articles/a-gentle-browserify-walkthrough)

* [A collection of useful Browserify resources | learnjs.io](http://learnjs.io/blog/2013/11/24/browserify-resources/)

* [Browserify and the Universal Module Definition | dontkry.com](http://dontkry.com/posts/code/browserify-and-the-universal-module-definition.html)

* [Untangle Your JavaScript with Browserify | Lincoln Loop](http://lincolnloop.com/blog/untangle-your-javascript-browserify/)

* [Browserify - Unix in the browser | thinking_on thinking](http://thinkingonthinking.com/unix-in-the-browser/)

* [Quick Tip: Write Modular JavaScript With Browserify | Tutorialzine](http://tutorialzine.com/2014/02/writing-modular-javascript-browserify/)

* [Speedy Browserifying with Multiple Bundles | Lincoln Loop](http://lincolnloop.com/blog/speedy-browserifying-multiple-bundles/)

* [[Speaker Deck] Browserify All The Things](https://speakerdeck.com/bevacqua/browserify-all-the-things) - This talk is about how to use browserify to develop front-end modular code using Common.JS, and how those modules should be documented, designed, and released using an automated build system. In order to explain these concepts I'll walk you through a few of my own open-source creations, highlighting interesting points as we go along. [2014/08/28]

* [[YouTube] Nicolas Bevacqua - Browserify all the things](https://www.youtube.com/watch?v=uZ_1_fddWns) - Using Browserify to develop front-end modular code using CommonJS; Writing tests for browserified code using 'tap'; Using Testling to run tests in the browser locally, and bringing that to the cloud by setting up continuous integration with Browserling. [2014/09/02]

--

* [A Journey From Require.js to Browserify | Orizen Designs](http://orizens.com/wp/topics/a-journey-from-require-js-to-browserify/)

--

* [Building High-Quality Front-End Modules | Pony Foo](http://blog.ponyfoo.com/2014/08/05/building-high-quality-front-end-modules)

  * [[GitHub] bevacqua / rome](https://github.com/bevacqua/rome) - Customizable date (and time) picker. Opt-in UI, no jQuery!

* [Modularizando Frontend JavaScript com Browserify | Underground WebDev](http://udgwebdev.com/modularizando-frontend-javascript-com-browserify/)

--

* [Browserify-CDN](http://wzrd.in/) - Browserify as a service

  * [[GitHub] jesusabdullah / browserify-cdn](https://github.com/jesusabdullah/browserify-cdn)

--

* [[GitHub] substack / node-browserify](https://github.com/substack/node-browserify) - browser-side require() the node.js way

* [[GitHub] substack / browserify-handbook](https://github.com/substack/browserify-handbook) - how to build modular applications with browserify

* [[GitHub] basti1302 / angular-browserify](https://github.com/basti1302/angular-browserify) - Example/seed project for AngularJS with Browserify


##### Requireify

* [RequireBin](http://requirebin.com/)

* [[GitHub] johnkpaul / requireify](https://github.com/johnkpaul/requireify) - Browserify plugin to access all modules from browser console

  * [Requirify | Google Chrome Extension](https://chrome.google.com/webstore/detail/requirify/gajpkncnknlljkhblhllcnnfjpbcmebm)

* [[Gist] Require modules in the browser console](https://gist.github.com/mathisonian/c325dbe02ea4d6880c4e)



#### Require.js

> Performance e Organização

* [RequireJS](http://requirejs.org)

* [[YouTube] RequireJS - The Basics](https://www.youtube.com/watch?v=VGlDR1QiV3A)

  * [[GitHub] CaryLandholt / Tutorial RequireJS TheBasics](https://github.com/CaryLandholt/Tutorial-RequireJS-TheBasics)

* [[YouTube] RequireJS - Optimizer](https://www.youtube.com/watch?v=m6VNhqKDM4E) - Cary Landholt

  * [[GitHub] CaryLandholt / Tutorial RequireJS Optimizer](https://github.com/CaryLandholt/Tutorial-RequireJS-Optimizer)

* [Modular JavaScript with RequireJS](http://blog.credera.com/topic/technology-solutions/java/modular-javascript-with-requirejs/)

* [Lazy Loading JavaScript with RequireJS](http://www.joezimjs.com/javascript/lazy-loading-javascript-with-requirejs/)

* [Usando requireJS + jQuery para organizar seu código | Tutsmais](http://tutsmais.com.br/blog/javascript-2/usando-requirejs-jquery-para-organizar-seu-codigo/)

* [Organize Your Code with RequireJS](http://blog.teamtreehouse.com/organize-your-code-with-requirejs)

* [Source Modification With r.js | Merrick Christensen](http://merrickchristensen.com/articles/build-angular-with-requirejs.html) - An overview of source modification with r.js. Using ngmin and Angular.js as an example.

* [Using r.js to Optimize Your RequireJS Project | Tech Pro](http://tech.pro/blog/1639/using-rjs-to-optimize-your-requirejs-project)

* [RequireJS – Optimizing and Building One File](http://orizens.com/wp/topics/requirejs-optimizing-and-building-one-file/)

* [How to load jQuery plugins with RequireJS | Simone Web Design](http://simonewebdesign.it/blog/how-to-load-jquery-plugins-with-requirejs/)

* [Five Helpful Tips When Using RequireJS | Tech Pro](http://tech.pro/blog/1561/five-helpful-tips-when-using-requirejs)

--

* [[GitHub] adriancmiranda / generator-gulp-requirejs](https://github.com/adriancmiranda/generator-gulp-requirejs) - A gulp.js generator for requirejs webapps

* [[GitHub] RobinThrift / gulp-requirejs](https://github.com/robinthrift/gulp-requirejs) - A small, simply, very easy wrapper around the require.js optimizer to work with gulp.js


##### Backbone.js

* [A RequireJS, Backbone, and Bower Starter Template | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/a-requirejs-backbone-and-bower-starter-template/)

* [EndDash](http://www.enddash.com/) - is a two-way binding javascript templating framework built on top of semantic HTML


##### Angular.js

* [[SlideShare] Fast prototyping apps using AngularJS, RequireJS and Twitter Bootstrap](http://www.slideshare.net/ysilvestrov/js-quick-prototyping-kyiv-js)

  * alarm-clock [webapp](http://jayostudio.net/app/#/clock) | [bitbucket: code](https://bitbucket.org/ysilvestrov/alarm-clock)



### Qualidade de Código

* [JSHint](http://www.jshint.com/)

  * [[Gist] When JSLint hurts your feelings, hug it out with Doug](https://gist.github.com/textarcana/1745829)

  * [[GitHub] sindresorhus / jshint-stylish](https://github.com/sindresorhus/jshint-stylish) - Stylish reporter for JSHint

* [JSLint](http://www.jslint.com/)



### Integração Contínua

* [Magnum CI : The Jenkins Chronicles 1 - Intro to JsTestDriver](http://transitioning.to/2012/07/magnum-ci-the-jenkins-chronicles-1-intro-to-jstestdriver/)



### Útil

* [[GitHub] Kickstart](https://github.com/felixlaumon/kickstart) - is a starter template for building your next web app. It allows you  to dive right into writing actual code. Kickstart uses Grunt and Bower  and includes LiveReload, LESS, Jade, RequireJS, and JSHint

* [Automatically download & use FrontEnd JS dependencies with Bower + Grunt boilerplate free](http://www.blogeek.com.ar/2013/04/25/automatically-download-use-frontend-js-dependencies-with-bower-grunt-boilerplate-free/)

* [[GitHub] andrewbredow / Library-Detector-for-Chrome](https://github.com/andrewbredow/Library-Detector-for-Chrome) - Google Chrome Extension that detects which Javascript library is running on a page


### Bibliotecas

* [JSDB.io](http://www.jsdb.io/) is a collection of the best javascript libraries

* [Microjs](http://microjs.com/) - Fantastic Micro-Frameworks and Micro-Libraries for Fun and Profit! | [[GiHub] madrobby / microjs.com](https://github.com/madrobby/microjs.com)

--

* [[GitHub] angular / zone.js](https://github.com/angular/zone.js) - Implements Zones for JavaScript. A Zone is an execution context that persists across async tasks. You can think of it as thread-local storage for JavaScript VMs.

--

* [[GitHub] philschatz / octokat.js](https://github.com/philschatz/octokat.js) - Client for the Github API using callbacks or Promises. Intended for the browser or NodeJS.

--

* [FloraJS - JavaScript framework for simulating natural systems](http://www.florajs.com/)

* [Lena.JS](https://github.com/davidsonfellipe/lena-js/) - biblioteca de filtros para processamento de imagens usando JavaScript.

--

* [Offline.js](http://github.hubspot.com/offline/docs/welcome/) - Handle your users losing their internet connection like a pro

--

* [stacktrace.js](http://stacktracejs.com/) - Framework-agnostic, micro-library for getting stack traces in all web browsers.

--

* [[GitHub] arasatasaygin / is.js](https://github.com/arasatasaygin/is.js) - Micro check library

* [[GitHub] dleitee / strman](https://github.com/dleitee/strman) - A Javascript string manipulation library without npm dependences

* [[GitHub] RadLikeWhoa / helpers.js](https://github.com/RadLikeWhoa/helpers.js) - Small JavaScript functions for common use cases.

* [[GitHub] dankogai / js-combinatorics](https://github.com/dankogai/js-combinatorics) - power set, combination, and permutation in JavaScript

* [[GitHub] caolan / highland](https://github.com/caolan/highland) - The high-level streams library for Node.js and the browser

--

* [[GitHub] wilmoore / selectn](https://github.com/wilmoore/selectn) - Resolves deeply-nested object properties via dot or bracket-notation for Node.js and the browser

--

* [[GitHub] baconjs / bacon.js](https://github.com/baconjs/bacon.js) - FRP (functional reactive programming) library for Javascript

  * [Functional Reactive Programming in JavaScript | Flippin' Awesome](http://flippinawesome.org/2013/09/30/functional-reactive-programming-in-javascript/)

--

* [[GitHub] allouis / minivents](https://github.com/allouis/minivents) - Small event system for javascript

* [[GitHub] philbooth / trier.js](https://github.com/philbooth/trier.js) - Conditional and repeated function invocation for node and browser

--

* [[GitHub] sutoiku / formula.js](https://github.com/sutoiku/formula.js) - JavaScript implementation of most Microsoft Excel formula functions

* [[GitHub] stephen-hardy / xlsx.js](https://github.com/stephen-hardy/xlsx.js) - is a JavaScript library for converting the data in base64 XLSX files into JavaScript objects - and back!

    * [[GitHub] mgcrea / node-xlsx](https://github.com/mgcrea/node-xlsx) - Node.js excel parser & builder

* [[GitHub] Niggler / js-xls](https://github.com/Niggler/js-xls)

  * [NPM](https://npmjs.org/package/xlsjs) | [JS-XLS Live Demo](http://niggler.github.io/js-xls/)

* [[GitHub] jlord / sheetsee.js](https://github.com/jlord/sheetsee.js) - visualize data from a google spreadsheet

--

* [[GitHub] gkindel / CSV-JS](https://github.com/gkindel/CSV-JS) - A Comma-Separated Values parser for JavaScript. Standards-based, stand alone, and no regular expressions

* [[GitHub] knrz / CSV.js](https://github.com/knrz/CSV.js) - A simple, blazing-fast CSV parser and encoder. Full RFC 4180 compliance

* [[GitHub] mholt / PapaParse](https://github.com/mholt/PapaParse) - Papa Parse is a powerful CSV (delimited text) parser that gracefully handles large files and malformed input

--

* [WebODF](http://webodf.org/) - a JavaScript library that makes it easy to add Open Document Format (ODF) support

--

* [Como imprimir com Javascript | nomadev](http://nomadev.com.br/como-imprimir-com-javascript/)

--

* [[GitHub] jDataView / jBinary](https://github.com/jDataView/jBinary) - High-level I/O for binary data. jBinary makes it easy to work with binary files in JavaScript as with native objects via declarative syntax.

* [zip.js](http://gildas-lormeau.github.io/zip.js/) - A JavaScript library to zip and unzip files

* [lz-string](http://pieroxy.net/blog/pages/lz-string/demo.html) - JavaScript compression, fast!

* [[Google Code] jslzjb](https://code.google.com/p/jslzjb/) - Javascript port of the LZJB compression algorithm.

--

* [[GitHub] mikaelbr / SocialFeed.js](https://github.com/mikaelbr/SocialFeed.js) - Easily create a feed with your latest interactions on different social media. Accumulate Github Events, Disqus comments, Delicious links, Tweets, etc.

* [SpeakingURL](http://pid.github.io/speakingurl/) - Generate a SpeakingURL/slug for browser & server

* [[GitHub] medialize / URI.js](https://github.com/medialize/URI.js) - Javascript URL mutation library

* [[GitHub] loadfive / Knwl.js](https://github.com/loadfive/knwl.js) - Scan through text for data that may be of interest

--

* [parseUri - Split URLs in JavaScript](http://blog.stevenlevithan.com/archives/parseuri)

* [[GitHub] QubitProducts / urlite](https://github.com/QubitProducts/urlite) - A very small, fast, dependency free url parser and formatter for nodejs and the web

--

* [[GitHub] flesler / hashmap](https://github.com/flesler/hashmap) - HashMap JavaScript class for NodeJS and the browser. The keys can be anything and won't be stringified

* [[GitHub] montagejs / collections](https://github.com/montagejs/collections) - This package contains JavaScript implementations of common data structures with idiomatic interfaces

--

* [[GitHub] philbooth / check-types.js](https://github.com/philbooth/check-types.js) - A tiny JavaScript library for checking arguments and throwing exceptions.

* [[GitHub] zvictor / ArgueJS](https://github.com/zvictor/ArgueJs) - optional parameters, default values and type-checking for your JavaScript method signatures

* [Leaflet](http://leafletjs.com/) - a JavaScript library for mobile-friendly maps

* [List.js](http://listjs.com/) - Add search, sort and flexibility to plain HTML lists or tables with cross-browser native JavaScript by @javve . “Native” JavaScript, no dependencies on libraries.

--

* [Converse.js](http://conversejs.org/) - An XMPP chat client for your website

* [Strophe.js](http://strophe.im/strophejs/) - An XMPP library for JavaScript

--

* [[GitHub] fdaciuk / ajax](https://github.com/fdaciuk/ajax) - Ajax module in Vanilla JS

* [[GitHub] brandonjpierce / jax](https://github.com/brandonjpierce/jax) - A minimal fully featured client side ajax library inspired by Superagent

* [[GitHub] jas- / comm.js](https://github.com/jas-/comm.js) - Plugin to handle browser communications (i.e. xhr, xdr, ws & wss protocols)

--

* [AmplifyJS](http://amplifyjs.com/) - is a set of components designed to solve common web application problems with a simplistic API (Request | Store | Pub/Sub)

* [[GitHub] moll / js-concert](https://github.com/moll/js-concert) - An event library for JavaScript and Node.js that implements the observer pattern (a.k.a publish/subscribe). Similar to Node's EventEmitter and Backbone.Events, but independent, minimal and light-weight. [ Concert.js doesn't yet have a build ready for the browser, but you might be able to use Browserify to have it run there till then. ]

--

* [HeliosJS](http://entrendipity.github.io/helios.js/) - in-memory graph database for modern browsers

* [[GitHub] keithwhor / UnitGraph](https://github.com/keithwhor/UnitGraph) - Lightweight Graph Library for iojs

  * [Using Graph Theory to Build a Simple Recommendation Engine in JavaScript | Medium by @keithwhor](https://medium.com/@keithwhor/using-graph-theory-to-build-a-simple-recommendation-engine-in-javascript-ec43394b35a3) - Leveraging User Behavior to Drive Recommendations

* [[GitHub] rse / extraction](https://github.com/rse/extraction) - Tree Extraction for JavaScript Object Graphs

--

* [[GitHub] kripken / sql.js](https://github.com/kripken/sql.js) - SQLite compiled to JavaScript through Emscripten

--

* [[GitHub] google / lovefield](https://github.com/google/lovefield) - is a relational database for web apps. Written in JavaScript, works cross-browser. Provides SQL-like APIs that are fast, safe, and easy to use.

* [TaffyDB](http://www.taffydb.com/) - The JavaScript Database

* [SpahQL](http://danski.github.io/spahql/) - Query, manipulate and manage JSON data effortlessly.

* [[GitHub] tuxracer / simple-storage](https://github.com/tuxracer/simple-storage) - Simple localStorage / sessionStorage supporting objects and arrays

* [[GitHub] techfort / LokiJS](https://github.com/techfort/LokiJS) - javascript embedded / in-memory database

  * [LokiJS](http://lokijs.org/) - A lightweight javascript document oriented database

* [PouchDB](http://pouchdb.com/) - the JavaScript Database that Syncs! PouchDB is an Open Source JavaScript Database inspired by Apache CouchDB that is designed to run well within the browser.

--

* [Squel.js](http://hiddentao.github.io/squel/) - lightweight Javascript library for building SQL query strings.

* [[GitHub] goodybag / mongo-sql](https://github.com/goodybag/mongo-sql) - An extensible SQL generation library for JavaScript with a focus on introspectibility

* [Formbuilder.js | dobtco](http://dobtco.github.io/formbuilder/)

--

* [[GitHub] Prinzhorn / skrollr](https://github.com/Prinzhorn/skrollr) - Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery. Just plain JavaScript (and some love).

* [[GitHub] component / infinity](https://github.com/component/infinity) - infinite scrolling with loading and unloading

* [spin.js](http://fgnass.github.io/spin.js/) - An animated CSS activity indicator with VML fallback [sample](http://www.javascriptoo.com/spin-js)

--

* [[GitHub] tildeio / kamino.js](https://github.com/tildeio/kamino.js) - Kamino.js is a library for passing data structures between sandboxed environments in the browser via 'postMessage'

* [[GitHub] jpillora / xhook](https://github.com/jpillora/xhook) - Easily modify XHR requests and responses

* [Dug.js — A JSONP to HTML Script | Rog.ie](http://rog.ie/blog/dugjs-a-jsonp-to-html-script)

--

* [[GitHub] lorenzoongithub / completely](https://github.com/lorenzoongithub/completely/) - A fresh take on autocompletion for a wonderful user experience

--

* [[GitHub] marcoscaceres / jsi18n](https://github.com/marcoscaceres/jsi18n) | [site](http://marcoscaceres.github.io/jsi18n/) - Using the JavaScript Internationalization API

* [[GitHub] jquery / globalize](https://github.com/jquery/globalize) - A JavaScript library for internationalization and localization that leverages the official Unicode CLDR JSON data

  * [Announcing Globalize 1.0 | Official jQuery Blog](http://blog.jquery.com/2015/04/23/announcing-globalize-1-0/)

  * [[GitHub] rxaviers / javascript-globalization](https://github.com/rxaviers/javascript-globalization) - The globalization (internationalization and localization) farm of the JavaScript community.

--

* [[GitHub] rodrigogs / kairos](https://github.com/rodrigogs/kairos) - A non date-based time calculator

* [Moment.js](http://momentjs.com/) - A javascript date library for parsing, validating, manipulating, and formatting dates.

  * [Managing Dates and Times Using Moment.js | SitePoint](http://www.sitepoint.com/managing-dates-times-using-moment-js/) - 2014/04/29

* [[GitHub] d3 / d3-time-format](https://github.com/d3/d3-time-format) - A JavaScript time formatter and parser inspired by strftime and strptime

--

* [[GitHub] Khan / KaTeX](https://github.com/Khan/KaTeX) - is a fast, easy-to-use JavaScript library for TeX math rendering on the web

* [[GitHub] fantasyland / fantasy-land](https://github.com/fantasyland/fantasy-land) - Specification for interoperability of common algebraic structures in JavaScript

* [[GitHub] nicolewhite / algebra.js](https://github.com/nicolewhite/algebra.js) - Build, display, and solve algebraic equations

--

* [[GitHub] sloisel / numeric](https://github.com/sloisel/numeric) -  is a javascript library for doing numerical analysis in the browser - [NumericJS](http://www.numericjs.com/)

* [[GitHub] adamwdraper / Numeral-js](https://github.com/adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers

* [[GitHub] MikeMcl / big.js](https://github.com/MikeMcl/big.js) - A small, fast JavaScript library for arbitrary-precision decimal arithmetic

* [[GitHub] iriscouch / bigdecimal.js](https://github.com/iriscouch/bigdecimal.js) - Arbitrary-precision Javascript BigInteger and BigDecimal real numbers

* [[GitHub] HubSpot / humanize](https://github.com/HubSpot/humanize) - A simple utility library for making the web more humane.

* [[GitHub] rschmukler / human-interval](https://github.com/rschmukler/human-interval) - Human readable time distances for javascript

* [[GitHub] Nijikokun / file-size](https://github.com/Nijikokun/file-size) - Lightweight filesize to human-readable / proportions w/o dependencies for node.js & browsers.

--

* [[GitHub] jstayton / version.js](https://github.com/jstayton/version.js) - Test a different script version with the switch of a query string

--

* [[GitHub] serratus / quaggaJS](https://github.com/serratus/quaggaJS) - An advanced barcode-scanner written in JavaScript | [site](https://serratus.github.io/quaggaJS/)

--

* [[GitHub] benvan / lsys](https://github.com/benvan/lsys) - interactive l-system generator (CoffeeScript) | [wiki: L-system](https://en.wikipedia.org/wiki/L-system)

--

* [[GitHub] zenorocha / clipboard.js](https://github.com/zenorocha/clipboard.js) - Modern copy to clipboard. No Flash. Just 2kb


#### Upload

* [[GitHub] TTLabs / EvaporateJS](https://github.com/TTLabs/EvaporateJS) - Javascript library for browser to S3 multipart resumable uploads


#### Emulator

* [Emulators written in JavaScript | Frederic Cambus](http://www.cambus.net/emulators-written-in-javascript/)

  * [[GitHub] fcambus / jsemu](https://github.com/fcambus/jsemu) - A list of emulators written in the JavaScript programming language

* [PCjs : IBM PC XT (Model 5160) running Windows v1.01](http://jsmachines.net/demos/pc/cga-win101/xt-cga-win101.xml)

* [JsDOSBox - JavaScript PC DOS Emulator](http://sourceforge.net/p/jsdosbox/home/Home/)

* [JsPspEmu - JavaScript PSP emulator](http://jspspemu.com/)


#### Redes Neurais

* [Hacker's guide to Neural Networks | Andrej Karpathy blog](https://karpathy.github.io/neuralnets/)

* [[GitHub] karpathy / convnetjs](https://github.com/karpathy/convnetjs) - Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.


#### Compiladores

* [altJS](http://altjs.org/) - Web coding beyond JavaScript. JavaScript is the only language browsers understand, but JS compilers and converters make it possible to code in a variety of languages and still deploy the result anywhere.

--

* [[GitHub] lkesteloot / turbopascal](lkesteloot / turbopascal) - Web-based Turbo Pascal compiler.

  * [Turbo Pascal Compiler](http://www.teamten.com/lawrence/projects/turbo_pascal_compiler/) | [try it here](http://www.teamten.com/lawrence/projects/turbo_pascal_compiler/demo/)

* [Scala.js](http://www.scala-js.org/) - A Scala to JavaScript compiler

  * [[GitHub] scala-js / scala-js](https://github.com/scala-js/scala-js) - Scala.js, a Scala to JavaScript compiler

  * [Scala.js Fiddle](http://www.scala-js-fiddle.com/)

  * [[GitHub] lihaoyi / workbench-example-app : ScalaJSExample.scala](https://github.com/lihaoyi/workbench-example-app/blob/ray-tracer/src/main/scala/example/ScalaJSExample.scala) - Scala.js Ray Tracer

  * [[GitHub] rockymadden / scala-node](https://github.com/rockymadden/scala-node) - Proof of concept to determine if Scala.js could be leveraged to make a Node.js module. It can.

* [CoffeeScript](http://coffeescript.org/) is a little language that compiles into JavaScript

  * [[GitHub] jashkenas / coffee-script](https://github.com/jashkenas/coffee-script/) - Unfancy JavaScript

  * [Resources for Learning Coffeescript | Jennifer Mann](http://jennifermann.ghost.io/resources-for-learning-coffeescript/)

  * [[CodeSchool] CoffeeScript](http://coffeescript.codeschool.com/)

  * [Hard Rock CoffeeScript](https://alchapone.github.io/hard-rock-coffeescript/)

  * [Functional CoffeeScript for the impatient | Blog of Cedric Ruiz](http://cedricruiz.me/blog/functional-coffeescript-for-the-impatient/)

* [[GitHub] shift-js / shift-js](https://github.com/shift-js/shift-js) - Swift to JavaScript transpiler

* [TypeScript](http://www.typescriptlang.org/) - is a language for application-scale JavaScript development. TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.

  * [[GitHub] Microsoft / TypeScript](https://github.com/Microsoft/TypeScript) - TypeScript is a superset of JavaScript that compiles to clean JavaScript output.

  * [[GitHub] DefinitelyTyped / tsd](https://github.com/DefinitelyTyped/tsd) - TypeScript Definition manager for DefinitelyTyped

  * [[GitHub] DanWahlin / TypeScriptDemos](https://github.com/DanWahlin/TypeScriptDemos) - A set of TypeScript demos showing various features of the language

  * [TypeScript for C# Programmers | InfoQ](http://www.infoq.com/minibooks/typescript-c-sharp-programmers)

  * [The Rise of TypeScript? | Telerik Developer Network](http://developer.telerik.com/featured/the-rise-of-typescript/)

  * [Getting Started with TypeScript | Treehouse Blog](http://blog.teamtreehouse.com/getting-started-typescript)

  * [The Case for TypeScript | InfoQ](http://www.infoq.com/presentations/tpescript-language-tools) - 2016/04/17

  * [[GitHub] Microsoft / TypeScript-Sublime-Plugin](https://github.com/Microsoft/TypeScript-Sublime-Plugin) - IO wrapper around TypeScript language services, allowing for easy consumption by editor plugins

  * [When should I use TypeScript? | Medium by @alexewerlof](https://medium.com/@alexewerlof/when-should-i-use-typescript-311cb5fe801b)

* [Blog | Wolk Software Engineering](http://blog.wolksoftware.com/)

  * Decorators & metadata reflection in TypeScript: From Novice to Expert

    * [PART I: Method decorators](http://blog.wolksoftware.com/decorators-reflection-javascript-typescript)

    * [PART II: Property decorators & Class decorators](http://blog.wolksoftware.com/decorators-metadata-reflection-in-typescript-from-novice-to-expert-part-ii)

--

* [[GitHub] danprince / jsxpr](https://github.com/danprince/jsxpr) - Lisp in your language.


#### Máquinas Virtuais

* [[GitHub] kripken / lua.vm.js](https://github.com/kripken/lua.vm.js)

    * [The Lua VM, on the Web](http://kripken.github.io/lua.vm.js/lua.vm.js.html) - This is an experiment in running [Lua](http://www.lua.org/) on the web, by porting the Lua C implementation to JavaScript using [Emscripten](https://github.com/kripken/emscripten/wiki).

    * [Learning Lua/From JS](http://phrogz.net/lua/LearningLua_FromJS.html)

* [[GitHub] copy / v86](https://github.com/copy/v86) - x86 virtualization in JavaScript, running in your browser and NodeJS

* [[GitHub] maximecb / Higgs](https://github.com/maximecb/Higgs) - Higgs JavaScript Virtual Machine. An interpreter and JIT compiler for JavaScript targetting x86-64 platforms. (D Language)


#### Text Search

* [lunr.js - A bit like Solr, but much smaller and not as bright](http://lunrjs.com/) - Simple full-text search in your browser

  * [Building a Full-Text Index in Javascript | Gary Sieling](http://garysieling.com/blog/building-a-full-text-index-in-javascript)

* [[GitHub] brianreavis / sifter.js](https://github.com/brianreavis/sifter.js) - A library for textually searching arrays and hashes of objects by property (or multiple properties). Designed specifically for autocomplete.

* [[GitHub] krisk / Fuse](https://github.com/krisk/fuse) - Lightweight fuzzy-search, in JavaScript


#### Hash

* [Using JavaScript to create a GUID from a user's browser information](https://andywalpole.me/#!/blog/140739/using-javascript-create-guid-from-users-browser-information)

* [[GitHub] Valve / fingerprintjs](https://github.com/Valve/fingerprintjs) - Fast browser fingerprint library. Written in pure JavaScript, no dependencies. By default uses Murmur hashing and returns a 32bit integer number. Hashing function can be easily replaced. Feather weight: only 843 bytes when gzipped.

* [[GitHub] karanlyons / murmurHash3.js](https://github.com/karanlyons/murmurHash3.js) - All of MurmurHash3, in javascript. | [wiki: MurmurHash](https://en.wikipedia.org/wiki/MurmurHash)

* [[GitHub] ivanakimov / hashids.js](https://github.com/ivanakimov/hashids.js) - A small JavaScript class to generate YouTube-like hashids from one or many numbers. This is a client-side version of Node.js version


#### Crypto

* [Performance of Hashing in Javascript Crypto Libraries](http://dominictarr.github.io/crypto-bench/) - Dominic Tarr (Stackvm Mad Science University) 2014-01-26 (v1.0.4)

* [Stanford Javascript Crypto Library](http://crypto.stanford.edu/sjcl/) - The Stanford Javascript Crypto Library is a project by the Stanford Computer Security Lab to build a secure, powerful, fast, small, easy-to-use, cross-browser library for cryptography in Javascript.

* [OpenPGP.js](http://openpgpjs.org/) - JavaScript implementation

* [[GitHub] kjur / jsrsasign](https://github.com/kjur/jsrsasign) - The 'jsrsasign' (RSA-Sign JavaScript Library) is an opensource free cryptography library supporting RSA/RSAPSS/ECDSA/DSA signing/validation, ASN.1, PKCS#1/5/8 private/public key, X.509 certificate and CRL in pure JavaScript.


#### Steganography

* [steganography.js](http://www.peter-eigenschink.at/projects/steganographyjs/) - Information Hiding done with JavaScript

* [JavaScript Steganography : encoding secret messages in tweets or any text](http://holloway.co.nz/steg/)


#### Gesture

* [[GitHub]  roboleary / LeapTrainer.js](https://github.com/roboleary/LeapTrainer.js) - A gesture learning and recognition framework for the Leap Motion



### Design API & Biblioteca

* [Designing Javascript APIs](http://blog.filepicker.io/post/34767202473/designing-javascript-apis)

* [Designing Better JavaScript APIs | Smashing Coding](http://coding.smashingmagazine.com/2012/10/09/designing-javascript-apis-usability/)

* [Build Your First JavaScript Library | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/build-your-first-javascript-library/)

* [Criando um plugin JavaScript (sem jQuery!) | Tableless](http://tableless.com.br/criando-um-plugin-javascript-sem-jquery/)



### Ferramentas

* [[GitHub] gorhill / uBlock](https://github.com/gorhill/uBlock) - µBlock - An efficient blocker for Chromium, Firefox, and Safari. Fast and lean

--

* [A List of Foundational JavaScript Tools](https://www.codefellows.org/blogs/complete-list-of-javascript-tools)

* [[GitHub] tooling / book-of-modern-frontend-tooling](https://github.com/tooling/book-of-modern-frontend-tooling) - The Little Book Of Modern Front-end Tooling

  * [Book of Modern frontend tooling](http://tooling.github.io/book-of-modern-frontend-tooling/introduction.html) - This is a free, work-in-progress open-source book introducing you to the world of tooling for modern web applications

--

* [[GitHub] ondras / my-mind](https://github.com/ondras/my-mind) - Online Mindmapping Software

* [50 Useful JavaScript Tools](http://coding.smashingmagazine.com/2009/02/08/50-extremely-useful-javascript-tools/)

* [Super useful online tools to make JavaScript development easier](http://www.catswhocode.com/blog/super-useful-online-tools-to-make-javascript-development-easier)

* [Mixture : The perfect front-end development tool](http://mixture.io/)

* [[GitHub] adamschwartz / log](https://github.com/adamschwartz/log) - Console.log with style | [Demo](http://adamschwartz.co/log/) (Google Chrome)

* [[GitHub] caiogondim / logdown](https://github.com/caiogondim/logdown) - Debug utility with markdown support that runs on browser and server

* [[GitHub] paulirish / break-on-access](https://github.com/paulirish/break-on-access) - break on access to a property

--

* [Console e Command Line API | Loop Infinito](http://loopinfinito.com.br/2013/03/13/console-command-line-api/)

* [Ways to Remove Those Pesky console.log Statements | Elijah Manor](http://www.elijahmanor.com/grunt-away-those-pesky-console-log-statements/)

--

* [Getting a Head Start with Front End Generators | Flippin' Awesome](http://flippinawesome.org/2013/09/03/getting-a-head-start-with-front-end-generators/)

--

* [Brunch](http://brunch.io/) - is an ultra-fast HTML5 build tool


#### Slush

* [[GitHub] klei / slush](https://github.com/klei/slush) - The streaming scaffolding system - Gulp as a replacement for Yeoman

* [Slush, o novo Yeoman | Diogo Moretti](http://diogo.nu/slush-o-novo-yeoman/)

* [Slush - A Better Web App Scaffolding Tool | Flippin' Awesome](http://flippinawesome.org/2014/05/05/slush-a-better-web-app-scaffolding-tool/)


#### Yeoman

> **Sobre**
> O Yeoman é um projeto open-source, que tem como objetivo melhorar o fluxo de trabalho em aplicações webs robustas.

> **Dependência**
> Precisa e executa sobre o Node.js

* [Yeoman](http://yeoman.io/) - is a  robust and opinionated set of tools, libraries, and a workflow that can  help developers quickly build beautiful, compelling web apps.

  * [Yeoman 1.0](http://yeoman.io/blog/hello-1.0.html)

  * [Yeoman Codelab](http://yeoman.io/codelab.html) - tutorial

* [Yeoman - Iniciando com Sr. Bigodes](http://www.randalmaia.com/post/49118899296/yeoman-iniciando-com-sr-bigodes)

* [Experimente o Yeoman em seu workflow de projetos front-end | Caelum](http://blog.caelum.com.br/experimente-o-yeoman-em-seu-workflow-de-projetos-front-end/)

* [Building Apps With the Yeoman Workflow | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/building-apps-with-the-yeoman-workflow/)

* [How to Use Yeoman to Scaffold Your Next Web App | Wesley Tate Smith](http://wes.is/2015/01/13/how-to-use-yeoman-to-scaffold-your-next-web-app/)

* [3 steps to fully automatized JavaScript environment with yeoman and require.js for lazy people | webdesignporto](http://www.webdesignporto.com/3-steps-to-fully-automatized-javascript-environment-with-yeoman-and-require-js-for-lazy-people/)

--

* [Build Your Own Yeoman Generator | Tuts+ Code Tutorial](http://code.tutsplus.com/tutorials/build-your-own-yeoman-generator--cms-20040)

* [Static Site Generators for Yeoman | DailyJS](http://dailyjs.com/2013/09/12/yeoman-static-site-generators/)

* [Cordova + Web Best Practices | Gaunt Face - Matthew Gaunt](http://www.gauntface.co.uk/blog/2013/07/18/cordova-web-best-practices/) - Getting PhoneGap / Cordova up and running with Yeoman

* [[GitHub] mrichard / generator-marionette](https://github.com/mrichard/generator-marionette) - Yeoman marionette generator a la AMD

* [[GitHub] yeoman / generator-mobile](https://github.com/yeoman/generator-mobile/) - A Yeoman generator for mobile-first web apps


#### DevTools

* [NiDIUM](http://www.nidium.com/) - A new browser engine


##### Firefox

* [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/) - Built for those who build the Web. Introducing the only browser made for developers like you.

  * [Mozilla Introduces the First Browser Built For Developers: Firefox Developer Edition | Mozilla Hacks](https://hacks.mozilla.org/2014/11/mozilla-introduces-the-first-browser-built-for-developers-firefox-developer-edition/)

--

* [Firefox DevTools](https://developer.mozilla.org/en-US/docs/Tools)

* [How To Use Firefox's Web Developer Tools](http://www.howtogeek.com/105320/how-to-use-firefoxs-web-developer-tools/)

* [Future of Firefox DevTools](http://paulrouget.com/e/devtoolsnext/)

* [Java,Coffee,Live Script terminal for Firefox | more info](https://github.com/paulmillr/firefox-jsterm)

* Reintroducing the Firefox Developer Tools | Mozilla Hacks

    * [part 1: the Web Console and the JavaScript Debugger](https://hacks.mozilla.org/2013/09/reintroducing-the-firefox-developer-tools-part-1-the-web-console-and-the-javascript-debugger/)

* [Firefox Add-on Enables Web Development Across Browsers and Devices | Mozilla Hacks](https://hacks.mozilla.org/2014/09/firefox-tools-adapter/)


##### Google Chrome

* [DevTools Tips](http://devtoolstips.com/)

* [[GitHub] jaredwilli / devtools-cheatsheet](https://github.com/jaredwilli/devtools-cheatsheet) - A cheatsheet for developers using Chrome DevTools

* [[GitHub] andersonweb / DevTools-Learning](https://github.com/andersonweb/DevTools-Learning) - List of resources to learn Chrome DevTools

* [Down and Dirty with Chrome Developer Tools | Bret Little](https://blittle.github.io/chrome-dev-tools/)

--

* [Segredos do Chrome DevTools (Portuguese) | YouTube](https://www.youtube.com/playlist?list=PLOU2XLYxmsILUKyjDYUVYLeq7yyTxM_3d) - Zeno Roch

* [12 Extensions & Apps that Fill the Gaps in Chrome DevTools | Telerik Developer Network](http://developer.telerik.com/featured/12-extensions-apps-fill-gaps-devtools/)

* [Discover DevTools | Code School](http://www.codeschool.com/courses/discover-devtools) - Sharpen your dev process with Chrome DevTools

* [Strict Workflow](https://chrome.google.com/webstore/detail/strict-workflow/cgmnfnmlficgeijcalkgnnkigkefkbhd) - Enforces a 25min/5min workflow: 25 minutes of distraction-free work, followed by 5 minutes of break. Repeat as necessary.

--

* [Chrome Dev Tools](https://developers.google.com/chrome-developer-tools/)

* [Que usamos 10% do cérebro é mito. Mas que usamos 10% do Chrome, é fato! Chrome, a IDE que eu queria! | InfoQ Br](http://www.infoq.com/br/presentations/chrome-ide-que-eu-queria)

* [DevTools Tips For Sublime Text Users | Medium - @addyosmani](https://medium.com/@addyosmani/devtools-tips-for-sublime-text-users-cdd559ee80f8) - 2015/08/24

* [[YouTube Playlist] Segredos do Chrome DevTools](https://www.youtube.com/watch?v=XUgfwYzv-WQ&list=PLiGzvgwA5Gmgnq5vPjJxW52hDiX3ndL53)

* [DevTools Extensions Gallery](https://developers.google.com/chrome-developer-tools/docs/extensions-gallery)

* [Chrome extension source viewer](https://chrome.google.com/webstore/detail/chrome-extension-source-v/jifpbeccnghkjeaalbbjmodiffmgedin)

* [Console | Chrome Dev Tools](https://developers.google.com/chrome-developer-tools/docs/console)

* [Chrome Dev Tools: JavaScript and Performance | Nettuts+](http://net.tutsplus.com/tutorials/tools-and-tips/chrome-dev-tools-javascript-and-performance/)

* [DevTools Extensions For Web App Developers | AddyOsmani.com](http://addyosmani.com/blog/devtools-extensions-for-webapp-developers/)

* [Breakpoint Actions in JavaScript | RandomThink.net](http://www.randomthink.net/blog/2012/11/breakpoint-actions-in-javascript/)

* [CSS Prettifier Bookmarklet](https://github.com/addyosmani/cssprettifier-bookmarklet) - Um bookmarklet para unminify seu CSS no navegador

* [Canvas Inspection using Chrome DevTools - HTML5 Rocks](http://www.html5rocks.com/en/tutorials/canvas/inspection/)

* [Evaluate and validate XPath/CSS selectors in Chrome Developer Tools | Yi Zeng](http://yizeng.me/2014/03/23/evaluate-and-validate-xpath-css-selectors-in-chrome-developer-tools/) - 2014/03/23

--

* [Pesticide](http://pesticide.io/) - Kill Your Css Layout Bugs

--

* [Chrome Dev Tools Theming with Zero Base Themes | Simon Owen](http://simonowendesign.co.uk/blog/2014/03/12/chrome-dev-tools-theming-with-zero-base-themes/)

--

* [DevTools Snippets](http://bgrins.github.io/devtools-snippets/) - A collection of helpful snippets to use inside of browser devtools

* [JSHint for Chrome Dev Tools](http://mrpotes.github.io/jshint-extension/)

--

* [[GitHub] mauricecruz / chrome-devtools-zerodarkmatrix-theme](https://github.com/mauricecruz/chrome-devtools-zerodarkmatrix-theme) - A highly customized dark theme for Chrome DevTools

* [[GitHub] tweekmonster / Developer-Profile](https://github.com/tweekmonster/Developer-Profile) - A Google Chrome extension that deletes browser data when all windows in a profile are closed

* [[GitHub] vladikoff / grunt-devtools](https://github.com/vladikoff/grunt-devtools) - Grunt Task Runner Extension for Chrome Developer Tools

* [[GitHub] github-linker / chrome-extension](https://github.com/github-linker/chrome-extension/) - The GitHub Linker is a Google Chrome Extension which links NPM, bower, Composer & Duo dependencies to their GitHub repository page. It also solve require() statments in a .js, .jsx, .coffee or .md file.


### Gerenciador de Pacotes

* [npm and front-end packaging | The npm Blog](http://blog.npmjs.org/post/101775448305/npm-and-front-end-packaging)

* [Why Version Control isn’t Package Management: A brief history | Medium - @wbinnssmith](https://medium.com/@wbinnssmith/why-version-control-isnt-package-management-a-brief-history-5d40c524ba3e) - Or, why aren’t we using npm for the frontend?

--

* [Jam.js and Bower | Red Badger](http://red-badger.com/blog/2013/03/26/jam-js-and-bower/)

* [jspm.io](http://jspm.io/) - is a browser module loader that will load any module format (ES6 / AMD / CJS) locally or even directly from NPM and Github utilising SPDY push.

--

* [Component.io](http://component.io/)

    * [[GitHub] component / component](https://github.com/component/component) - client package management for building better web applications

    * [Introduction to Component | Samll.js](http://smalljs.org/package-managers/component-part-1/)

    * [Introduction to the Component JavaScript Package Manager | Flippin Awesome](http://flippinawesome.org/2014/02/17/introduction-to-the-component-javascript-package-manager/)


#### Bower

> **Sobre**
> Bower é um gerenciador de pacotes para web. Ele oferece uma solução genérica para o problema de gerenciar os pacores de front-end. O Bower utiliza e executa sobre Git e é agnóstico de pacote.

> **Dependência**
> Precisa e executa sobre o Node.js

--

> 2015 - muitos indicam usar o NPM ao invés do Bower, pois muitos projetos atuais já usam ferramentas que rodam sobre o Node.js que já possui um gerenciador de pacotes (o NPM)

* [Why We Should Stop Using Bower - And How to Do It | Gofore](http://gofore.com/ohjelmistokehitys/stop-using-bower/) - 2015/05/25 - usar o browserify no lugar do bower

--

* [Bower](http://bower.io/) - is a package manager for the web, from Twitter, that lets you easily install assets such as images, CSS and JavaScript, and manages dependencies for you.

* [Search Bower packages | Bower](http://bower.io/search/)

* [[GitHub] bower / bower](https://github.com/bower/bower)

* [Bower components](http://sindresorhus.com/bower-components/) - Sistema de busca dos pacotes/componentes indexados pelo Bower

--

* [Setting up a private Bower registry. | Fumbles' Tech Blog](http://fumblesandfriends.com/blog/setting-up-a-private-bower-registry/)

* [How to host a private bower registry | ParadigmShift](http://toranbillups.com/blog/archive/2013/08/04/How-to-host-a-private-bower-registry/)

* [[GitHub] Hacklone / private-bower](https://github.com/Hacklone/private-bower) - A simple private bower registry

--

* [[YouTube] Conheça o Bower](https://www.youtube.com/watch?v=0XffYRF7-G0)

* [Gerenciando dependências client-side com Bower | Simples Ideias](http://simplesideias.com.br/gerenciando-dependencias-client-side-com-bower)

* [Bower na prática | Tableless](http://tableless.com.br/bower-na-pratica/)

* [Client-Side Dependency Management With Bower | TysonJS](http://tysoncadenhead.com/blog/client-side-dependency-management-with-bower)

* [Meet Bower: A Package Manager For The Web | Nettuts+](http://net.tutsplus.com/tutorials/tools-and-tips/meet-bower-a-package-manager-for-the-web/)

* [Twitter Bower & Grunt: Get started with assets management | Guillaume Piot](http://gpiot.com/twitter-bower-grunt-get-started-with-assets-management/)

* [Package Management for the Browser with Bower | SitePoint](http://www.sitepoint.com/package-management-for-the-browser-with-bower/)

* [Checking in front-end dependencies | Addy Osmani](http://addyosmani.com/blog/checking-in-front-end-dependencies/)

* [Bower all the things | Roughdraft.io](http://anotheruiguy.roughdraft.io/8927018)

* [A quebra do build automático e o Bower no meio do caminho | Igor Costa](http://www.igorcosta.com/quebra-build-automatico-e-o-bower-meio-caminho/)


#### JamJS

* [JamJS](http://jamjs.org/) - For front-end developers who crave maintainable assets, Jam is a package manager for JavaScript. Unlike other repositories, we put the browser first.

* [Frictionless AMD with Jam | Nettuts+](http://net.tutsplus.com/tutorials/javascript-ajax/frictionless-amd-with-jam/)

* [Managed JavaScript with JamJS | zerokspot](http://zerokspot.com/weblog/2012/09/16/managed-js-with-jamjs/)


### Single Page Application

* [[GitHub] imrefazekas / leaper.js](https://github.com/imrefazekas/leaper.js) - is a simple javascript library to aid creation of single-page web-applications. It follows declarative way to define pages making the markings simpler and straightforward.

* [Patterns For Large-Scale JavaScript Application Architecture | Addy Osmani](http://addyosmani.com/largescalejavascript/)

* [reInteractive: Lessons learnt by building Single Page Applications | Sydney, Australia Ruby on Rails Developers](http://www.reinteractive.net/posts/186-lessons-learnt-by-building-single-page-applications)


### Frameworks

* [MVC Architecture](http://developer.chrome.com/trunk/apps/app_frameworks.html)

* [TodoMVC](http://addyosmani.github.com/todomvc/) - Helping you select an MV* framework

  * [How Complex are TodoMVC Implementations | CoderStats Blog](http://blog.coderstats.net/todomvc-complexity/)

* [Journey Through The JavaScript MVC Jungle | Smashing Coding](http://coding.smashingmagazine.com/2012/07/27/journey-through-the-javascript-mvc-jungle/)

* [Modularity in Javascript MVC Frameworks](http://juristr.com/blog/2013/04/modularity-in-javascript-frameworks/)

* [Rich JavaScript Applications – the Seven Frameworks (Throne of JS, 2012)](http://blog.stevensanderson.com/2012/08/01/rich-javascript-applications-the-seven-frameworks-throne-of-js-2012/)

* [The Big Glossary of Open Source JavaScript and Web Frameworks with Cool Names](http://www.hanselman.com/blog/TheBigGlossaryOfOpenSourceJavaScriptAndWebFrameworksWithCoolNames.aspx)

--

* [The Top 10 Javascript MVC Frameworks Reviewed](http://codebrief.com/2012/01/the-top-10-javascript-mvc-frameworks-reviewed/)

* [Top JavaScript MVC Frameworks | InfoQ](http://www.infoq.com/research/top-javascript-mvc-frameworks)

--

* [Contrasting Backbone and Angular | Victor Savkin on Software Architecture & Design](http://victorsavkin.com/post/65519559752/contrasting-backbone-and-angular)

* [Contrasting Backbone and Angular | InfoQ](http://www.infoq.com/articles/backbone-vs-angular)

--

* [[GitHub] Famous / famous](https://github.com/Famous/famous) -  provides a powerful JavaScript framework and developer tools designed to build rich, fast web applications.

--

* [BladeRunnerJS](http://bladerunnerjs.org/) - (BRJS) is an open source development toolkit and framework for modular construction of large single-page HTML5 apps. It consists of a set of conventions, supporting tools and micro-libraries that make it easy to develop, test, deploy and maintain complex JavaScript apps.

--

* [[GitHub] mattbaker / Reactive.js](https://github.com/mattbaker/Reactive.js) - A library for programming reactively in Javascript.

  * [Ractive.js Expressions and the New Wave of Reactive Programming | Flippin' Awesome](http://flippinawesome.org/2013/08/19/ractive-js-expressions-and-the-new-wave-of-reactive-programming/)

--

* [Cycle.js](http://cycle.js.org/) - A fully reactive JavaScript framework for Human-Computer Interaction

  * [[GitHub] cyclejs / cycle-core](https://github.com/cyclejs/cycle-core/)

--

* [[GitHub] moot / riotjs](https://github.com/moot/riotjs/)

  * [Riot.js — The 1kb client-side MVP framework](https://moot.it/blog/technology/riotjs-the-1kb-mvp-framework.html)

--

* [Ember.js](http://emberjs.com/)

  * [Ember Inspector | Google Chrome Developer Tool](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi?hl=en)

  * [An Ember.js beginners tutorial | WilliamHart.info](http://www.williamhart.info/an-emberjs-beginners-tutorial.html)

  * [An In-Depth Introduction To Ember.js | Smashing Coding](http://coding.smashingmagazine.com/2013/11/07/an-in-depth-introduction-to-ember-js/)

  * [Querying for data in a full Javascript stack | 100PercentJS](http://www.100percentjs.com/querying-data-full-javascript-stack-2/)

* [HospitalRun](http://hospitalrun.io/) - Open source software for developing world hospitals. (Uses ember on UI)

--

* [Knockout.js](http://knockoutjs.com/)

  * [KnockoutJS Tips and Tricks | Tech Pro](http://tech.pro/tutorial/1559/knockoutjs-tips-and-tricks)

  * [Knockout.js Lesson 1 - Introduction | Tech Pro](http://tech.pro/tutorial/1562/knockoutjs-lesson-1-introduction)

--

* [Sammy.js](http://sammyjs.org/) - A Small Web Framework with Class / RESTFul Evented JavaScript

  * Store: A Sammy.js Tutorial [Part I](http://sammyjs.org/docs/tutorials/json_store_1) | [Part II](http://sammyjs.org/docs/tutorials/json_store_2) | [[GitHub] quirkey / the_json_store](https://github.com/quirkey/the_json_store)

--

* [jsblocks - Better JavaScript MV-ish Framework](http://jsblocks.com/) - From simple user interfaces to complex single-page applications using faster, server-side rendered and easy to learn framework

  * [[GitHub] astoilkov / jsblocks](https://github.com/astoilkov/jsblocks) - Better MV-ish Framework

--

* [Vue.js](http://vuejs.org/) - is a library for building interactive web interfaces. It provides data-reactive components with a simple and flexible API.

  * [[GitHub] yyx990803 / vue](https://github.com/yyx990803/vue) - Intuitive, fast & composable MVVM for building interactive interfaces.

  * [[GitHub] vuejs / awesome-vue](https://github.com/vuejs/awesome-vue) - A curated list of awesome things related to Vue.js

  * [Vue MDL](http://posva.net/vue-mdl/)

  * [Vue.js: data-binding e components | Fabio Vedovelli](http://www.vedovelli.com.br/web-development/vue-js-data-binding-e-componentes/)


### Babel

* [Babel](http://babeljs.io/) is a JavaScript transpiler. Use next generation JavaScript, today.

  * [Babel REPL](https://babeljs.io/repl/)

  * [[GitHub] babel / babel](https://github.com/babel/babel) - Babel is a transpiler for writing next generation JavaScript. (Previously 6to5)

* [Not Born to Die | Babel](http://babeljs.io/blog/2015/02/15/not-born-to-die/)

* [Learn ES6 | Babel](http://babeljs.io/docs/learn-es6/) - A detailed overview of ECMAScript 6 features.

--

* [From JSXTransformer to Babel | Stoyan's phpied.com](http://www.phpied.com/from-jsxtransformer-to-babel/) - 2015/06/22

--

* [[GitHub] 6to5 / 6to5-sublime](https://github.com/6to5/6to5-sublime) - Syntax definitions for ES6 JavaScript with React JSX extensions

* [[GitHub] voronianski / oceanic-next-theme](https://github.com/voronianski/oceanic-next-theme) - Sublime Text theme ready for ES6, optimized for 6to5-sublime package

* [Frontend lindo usando Babel para rodar ES6 | Underground WebDev](http://udgwebdev.com/frontend-lindo-usando-babel-para-rodar-es6/)

* [Frontend moderno com Browserify e Babel | Underground WebDev](http://udgwebdev.com/frontend-moderno-com-browserify-e-babel/)

* [Getting ES6 modules working thanks to Browserify, Babel, and Gulp | Advantcomp Blog](http://advantcomp.com/blog/ES6Modules/)

  * [[GitHub] acoard / ES6ModulesWithBabel](https://github.com/acoard/ES6ModulesWithBabel)

* [How to Use ES6 for Isomorphic JavaScript Apps | JavaScript Scene — Medium](https://medium.com/javascript-scene/how-to-use-es6-for-isomorphic-javascript-apps-2a9c3abe5ea2)

* [Transpiling ES6 Modules to AMD & CommonJS Using Babel & Gulp | SitePoint](http://www.sitepoint.com/transpiling-es6-modules-to-amd-commonjs-using-babel-gulp/) - 2015/09/21

  * [[GitHub] sitepoint-editors / Angular-ES6-BookShelf-Modules](https://github.com/sitepoint-editors/Angular-ES6-BookShelf-Modules)

* [[GitHub] CentaurWarchief / babel-plugin-global-require](https://github.com/CentaurWarchief/babel-plugin-global-require) - A simple plugin that allows you to require globally


### ECMAScript 6

> ECMAScript 6 -> ECMAScript 2015

* [ECMAScript 6 compatibility table](https://kangax.github.io/compat-table/es6/)

  * [[GitHub] kangax / compat-table](https://github.com/kangax/compat-table) - ECMAScript 5/6/7 compatibility tables

* [Five to Six — Addy Osmani’s list of ECMAScript 6 tools | Super-Script](http://www.super-script.us/2015/es6-tools.html)

--

* [es6 cheatsheet | Duckduckgo](https://duckduckgo.com/?q=es6+cheatsheet&ia=answer&iax=1)

* [[GitHub] DrkSephy / es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet) - ES2015 [ES6] cheatsheet containing tips, tricks, best practices and code snippets

--

* [[GitHub] airbnb / javascript](https://github.com/airbnb/javascript) - JavaScript Style Guide (ES6)

--

* [es6rocks.com](http://es6rocks.com/) : new site dedicated to articles and talks about the next version of JavaScript

  * [ES6: Brincando com o novo Javascript | ES6 Rocks](http://es6rocks.com/pt-br/2014/11/es6-playing-with-the-new-javascript/)

* [Introduction to ECMAScript 6 | Christophe Coenraets](http://coenraets.org/present/es6/)

* [ES6 In Depth Articles | Mozilla Hacks](https://hacks.mozilla.org/category/es6-in-depth/)

* [Read Exploring ES6 | Leanpub](https://leanpub.com/exploring-es6/read)

* [The ES6 Conundrum | SitePoint](http://www.sitepoint.com/the-es6-conundrum/) - 2015/08/10

* [Introduction to ECMAScript 6 Slides | Coenraets](http://coenraets.org/blog/2015/05/introduction-to-ecmascript-6-slides/) - 2015/05/20

  * [[GitHub] ccoenraets / intro-to-es6](https://github.com/ccoenraets/intro-to-es6)

* [O Guia do ES6: TUDO que você precisa saber |  Medium by @matheusml](https://medium.com/@matheusml/o-guia-do-es6-tudo-que-voc%C3%AA-precisa-saber-8c287876325f)

--

* [Replace CoffeeScript with ES6 | thoughtbot](http://robots.thoughtbot.com/replace-coffeescript-with-es6)

* [[Git] Moving to ES6 from CoffeeScript by danielgtaylor](https://gist.github.com/danielgtaylor/0b60c2ed1f069f118562)

* [Easing the Transition to ES6 | ifwe](http://www.ifwe.co/code/posts/easing-the-transition-to-es6/)

* [[Speaker Deck] From ES5 to ES6 (ES2015) and ES2016](https://speakerdeck.com/rauschma/from-es5-to-es6-es2015-and-es2016)

--

* [Expert ES6 | tagtree.io](http://tagtree.io/courses/expert-es6/do) - An ES6 Course in the Browser

* [[GitHub] ericdouglas / ES6-Learning](https://github.com/ericdouglas/ES6-Learning) - List of resources to learn ECMAScript 6

* [[GitHub] nzakas / understandinges6](https://github.com/nzakas/understandinges6) - Content for the ebook "Understanding ECMAScript 6"

  * [Announcing Understanding ECMAScript 6 | NCZOnline](http://www.nczonline.net/blog/2014/03/26/announcing-understanding-ecmascript-6/)

  * [Understanding ECMAScript 6 | Leanpub](https://leanpub.com/understandinges6)

* [ECMAScript 6 | rauchg.com](http://rauchg.com/2015/ecmascript-6/)

* [JavaScript — Just another introduction to ES6 — Sons of JavaScript | Medium - @gerardsans](https://medium.com/sons-of-javascript/javascript-an-introduction-to-es6-1819d0d89a0f)

--

* [Deploying ECMAScript 6 | 2ality](http://www.2ality.com/2015/04/deploying-es6.html)

* [ECMAScript 6 modules: the final syntax | 2ality](http://www.2ality.com/2014/09/es6-modules-final.html)

* [Variables and scoping in ECMAScript 6 | 2ality](http://www.2ality.com/2015/02/es6-scoping.html)

* [Managing the private data of ES6 classes | 2ality](http://www.2ality.com/2016/01/private-data-classes.html)

* [Arrow This | getiblog](http://blog.getify.com/arrow-this/)

* [ES6: arrow functions em 5 minutos | Raphael Fabeni](http://www.raphaelfabeni.com.br/es6-arrow-functions/) - 2016/01/12

* [Mastering ES6 higher-order functions for Arrays | airpair](https://www.airpair.com/javascript/posts/mastering-es6-higher-order-functions-for-arrays)

* [Iterables and iterators in ECMAScript 6 | 2ality](http://www.2ality.com/2015/02/es6-iteration.html)

* [JavaScript iterables and iterators | JS Rocks](http://jsrocks.org/2015/09/javascript-iterables-and-iterators/) - 2015/09/15

* [ES6 generators in depth | 2ality](http://www.2ality.com/2015/03/es6-generators.html)

* [ES6 Modules: The End of Civilization As We Know It?](https://medium.com/@brianleroux/es6-modules-amd-and-commonjs-c1acefbe6fc0)

* [JavaScript Modules the ES6 Way | @24ways](http://24ways.org/2014/javascript-modules-the-es6-way/)

* [ES6 Overview in 350 Bullet Points | ponyfoo](https://ponyfoo.com/articles/es6)

* [ES6 in Depth | ponyfoo](https://ponyfoo.com/articles/tagged/es6-in-depth)

  * [ES6 Modules in Depth | ponyfoo](http://ponyfoo.com/articles/es6-modules-in-depth)

  * [ES6 Promises in Depth | ponyfoo](http://ponyfoo.com/articles/es6-promises-in-depth)

  * [ES6 Array Extensions in Depth | ponyfoo](https://ponyfoo.com/articles/es6-array-extensions-in-depth)

  * [ES6 Symbols in Depth | ponyfoo](https://ponyfoo.com/articles/es6-symbols-in-depth)

* [ES6 for Now: Template Strings | SitePoint](http://www.sitepoint.com/es6-now-template-strings/) - 2015/09/09

* [Constructive destructuring | krasimirtsonev.com](http://krasimirtsonev.com/blog/article/constructive-destructuring-es6-assignment)

--

* [Rewriting A WebApp With ECMAScript 6 | TasteJS](http://blog.tastejs.com/rewriting-a-webapp-with-ecmascript-6/)

* [Get ready for ECMAScript 6 | K33G_ORG's Blog](https://k33g.github.io/2014/06/26/ES6-READY.html)

* [An introduction to ES6 classes | JavaScript Playground](http://javascriptplayground.com/blog/2014/07/introduction-to-es6-classes-tutorial/)

* [ES6 classes and JavaScript prototypes | reinteractive](https://reinteractive.net/posts/235-es6-classes-and-javascript-prototypes)

* [Preparing for ECMAScript 6: let and const | SitePoint](http://www.sitepoint.com/preparing-ecmascript-6-let-const/)

* [For and against `let` | DWB](http://davidwalsh.name/for-and-against-let)

* [JavaScript ES6 Variable Declarations with let and const | StrongLoop](https://strongloop.com/strongblog/es6-variable-declarations/)

* [ES6 Let, Const and the “Temporal Dead Zone” (TDZ) in Depth | ponyfoo](http://ponyfoo.com/articles/es6-let-const-and-temporal-dead-zone-in-depth) - 2015/09/04

--

* [ECMAScript 6 Proxy | Loop Infinito](http://loopinfinito.com.br/2014/09/09/ecmascript-6-proxy/)

--

* [[GitHub] JustinDrake / node-es6-examples](https://github.com/JustinDrake/node-es6-examples) - ECMAScript 6 examples for Node.JS

* [[GitHub] danielstern / generator-es6-webapp](https://github.com/danielstern/generator-es6-webapp) - A Yeoman generator to create an app which automatically transpiles ES6 to ES5 - also includes LESS and Skeleton

* [[GitHub] barbarosa / ECMAScript6_architecture](https://github.com/barbarosa/ECMAScript6_architecture) - Workshop and example of architecture with testable, maintainable, decoupled components written in ES6


### ECMAScript 7

> ECMAScript 7 -> ECMAScript 2016

* [[YouTube] Netflix JavaScript Talks - Version 7: The Evolution of JavaScript](https://www.youtube.com/watch?v=DqMFX91ToLw)

* [[YouTube] Jafar Husain: Async Programming in ES7 | JSConf US 2015](https://www.youtube.com/watch?v=lil4YCCXRYc) - 2015/06/22

* [2016 - the year of web streams | JakeArchibald.com](https://jakearchibald.com/2016/streams-ftw/) - 2016/01/25

* [The final feature set of ECMAScript 2016 (ES7) | 2ality](http://www.2ality.com/2016/01/ecmascript-2016.html) - 2016/01/30
