### `#30xHelloworlds` `#codevember`
# 30 days of hello, world's
30 new things in 30 days to inspire a lasting curiosity & desire to experiment.

I believe the best way to improve, become well rounded, form better opinions, and enhance one's ability to choose the right tool for the occasion is through experience. 30 days of "Hello, world!" challenges one's self to dive into unfamiliar territory with an open mind and zero bias.

In 30 days, I'm challenging myself to experiment with different frameworks, language, libraries, patterns, API's and technology that are unfamiliar or new to me. The goal is simply to gain a better understanding of the tools of the web and tech landscape by getting hands on experience and having fun doing so.

Contents:
- [Day 1: Go lang](#day1)
- [Day 2: Hapi.js](#day2)
- [Day 3: Koa.js](#day3)
- [Day 4: Hug API framework](#day4)
- [Day 5: Django: scratching the surface](#day5)
- [Day 6: Architect: Dependency injection](#day6)
- [Day 7: Vue.js](#day7)
- [Day 8: TypeScript](#day8)
- [Day 9: Angular 2 + TypeScript fun](#day9)
- [Day 10: React Native!](#day10)
- [Day 11: Touching on Ember.js](#day11)
- [Day 12: Next.js](#day12)
- [Day 13: R Programming](#day13)
- [Day 14: Attempt at understanding Haskell](#day14)
- [Day 15: Socket.io](#day15)
- [Day 16: Matter.js](#day16)
- [Day 17: Brunch.io](#day17)
- [Day 18: The basics of Phaser](#day18)
- [Day 19: Rust Lang](#day19)
- [Day 20: Elm Lang](#day20)
- [Day 21: ErLang](#day21)
- [Day 22: Ionic](#day22)
- [Day 23: Meteor](#day23)
- [Day 24: Messenger bot](#day24)
- [Day 25: Polymer](#day25)
- [Day 26: Service Workers: offline first](#day26)
- [Day 27: Swift3](#day27)
- [Day 28: Total JS](#day28)
- [Day 29: Mo.js Animation](#day29)
- [Day 30: MicroPython, Feather, Si7021](#day30)

___

# <a name="day1"></a> Day 1: ready, set, GO lang.
To get `go`-ing, I chose to start with Go because I figured, if things go well, I could use it throughout the next 30 days as a platform on hosts like Heroku or Google App Engine.

## What I like after 1 day
The syntax seemed quickly familiar with the added difference/bonus of Type Declarations. However, the type interpolation is pretty nice in Go.

Importing dependencies is straight forward and clean.

## Learning curves:
Getting setup with the `$GOPATH` with ZSH for me took a bit of Googling and diving into Stack Overflow. After adding it to my `.zshrc` everything was fine.

The `struct` way of handling objects, and the lack of traditional classes, is a bit of a mind bend and takes time to understand, after only one day of Go, I haven't quite grasped it, yet.


Resources:
- [golang.org](https://golang.org/)
- [play.golang.org](play.golang.org)
- [Pluralsight Go fundamentals](https://app.pluralsight.com/library/courses/go-fundamentals)
- [Pluralsight Gin Go](https://app.pluralsight.com/library/courses/gin-go-web-app-framework/table-of-contents)


# <a name="day2"></a>Day 2: Hapi.js
In the spirit of setting up a web server with Go, I'm continuing the exploration around web servers with Hapi.js. Up until now, when I've needed to spin up a web server, I've almost exclusively reached for Express. Coming from Express, Getting started with Hapi was quite simple.

The setup and syntax are similar enough, and even without any familiarity with a web server platform, Hapi is quite straight forward and easy to use. I enjoy the speed and simplicity of Hapi and will likely use it in the future projects.

## Learning curves:
Some of the documentation and tutorials I was reading (unofficial) were for old versions of Hapi that had some plugins included in the "core" Hapi package, e.g., vision. Sorting that out was as quick as reading the official documentation. As with most things, reading the documentation is paramount to understanding exactly how each method should be configured; which in Hapi, can be exhaustive and will take some memorization.

Resources:
- [Hapijs.com official Tutorials](http://hapijs.com/tutorials)
- [Post example](https://github.com/paullang/hapi-post-example)
- [Pluralsight Building web applications w/ Hapi](https://app.pluralsight.com/library/courses/hapi-building-web-applications/table-of-contents)

# <a name="day3"></a>Day 3: Koa
Koa was designed by those who brought us Express and feels like Express 2.0, or how Express would have been built today. Koa is a light-weight, callback-less framework. Koa uses ES6 (ES2015) Generators for everything. There is no pre-bundled middle wear in Kia, which means everything is a plug-in—I’m noticing more and more people are adopting this bare-minimum platform pattern with plugins/modules/extensions, these days.

Koa vs. Hapi vs. Express? Numerous blogs do in-depth analysis on this topic ([Such as this one on AirPair](https://www.airpair.com/node.js/posts/nodejs-framework-comparison-express-koa-hapi)). In my opinion,  I don't think you can go wrong with any of the platforms; it depends on personal preference. Koa seems to be the "lightest" and being Generator based has advantages. Plus, Koa "Makes writing servers fast and enjoyable."

## Learning curves
Everything in Koa uses Generator functions, which, before this I hadn't  spent much time with in practical, real-world use. Koa is the first thing I’ve seen using Generators (and they utilized them way back before Node fully supported them) in a non-academic way. The whole architecture uses generators instead of callback functions to be light and clean; which Koa is. Once you understand how to work with Generators, and how to `yield`, building a project is straightforward and efficient.

Resources:
[Koa homepage](http://koajs.com/)
[Pluralsight Intro to Koa Js](https://app.pluralsight.com/library/courses/javascript-koa-introduction/table-of-contents)
[Koa Examples](https://github.com/koajs/examples)


# <a name="day4"></a>Day 4 - Hug API framework

Hug + Python. It took some time to figure out what to design that was API only, but once I decided to build a simple random message app, things were easy. I didn’t get in too deep into all the features I would have liked to use in Hug, but I did see some parts that I would like to explore more of, mainly custom directives.

Hug makes writing API’s simple—as promised—once you know the syntax and how to use the decorators. The automatic documentation and error handling is very nice. I had planned to integrate swagger as part of day for documentation but found it wasn’t necessary (plus I was short on time)

## Learning curves
I struggled the most with creativity in trying to design an app “API first” Technically, the setup and installation process of Python 3.3, virtualenv, and hug took time and patience.

Resources:
Hug is not an easy framework to Google. Resources were a bit scarce compared to the larger frameworks I’m used to.
- [Hug.rest quickstart](http://www.hug.rest/website/quickstart)
- [Hug.rest Learn](http://www.hug.rest/website/learn/)
- [Hug examples code, Github](https://github.com/timothycrosley/hug/tree/develop/examples)

# <a name="day5"></a>Day 5 Django: The non-templating parts
Over the last year, I’ve used Jinja2 almost daily but never got around to checking out Django. Since I’m already familiar with the tempting _style_, the goal for today was to see all the other features Django has to offer.

The Django environment—at least from my minimal experience–is a fully considered development environment with all kinds of conveniences built in for developers; like a web server and simplified interactions and queries with databases.

Django aims to make developers more productive, and I think it does that well. I would say its similar to having a well-considered development environment built on Gulp, Grunt or similar tooling stack. The difference being that it has everything you need to get started writing your app without the overhead of installing and setting up your own tooling.

## Learning curves
Not a big deal, but in Django, the term “app” doesn’t refer to the entire application, but is more similar to “module.” The nature of the Django MVT(Model View Template, a variation of MVC–Model View Controller) architecture is to have a lot of files spread out, which is a bit cumbersome in the beginning. Fully comprehending which file needs which dependency takes practice and time.

Django has many proprietary commands that are required to work with Django, such as `python manage.py sqlmigrate` which are challenging to memorize right away. A cheatsheet or more time is needed (as is with most everything) to become fluent.

Resources
- [Official Django docs](https://docs.djangoproject.com/en/1.10/intro/overview/)
- [Pluralsight Django fundamentals](https://app.pluralsight.com/library/courses/django-fundamentals/table-of-contents)

#<a name="day6"></a> Day 6: Node Architect [Dependency injection]
I’ve been looking forward to trying Architect for Node for the last month. What I’ve read sounded promising, a lightweight, node-style framework for dependency injection. In other words, a simple framework for using plug-ins within an app. This type of application architecture would be perfect for allowing third-party plug-ins to be installed to different instances of an application—think Wordpress or Slack for example. Architect does make it easy to setup dependencies and create API's from one plug-in to another; called "consumes" and "provides" within the application.

Project support for Architect is a bit lacking. While it’s still a viable framework, is not maintained in the official repository, but instead in the Coud9 core; as explained in this issue https://github.com/c9/architect/issues/48. Because of minimal support documentation is lacking. As easy and quick as Architect can be, without proper documentation, it’s hard to recommend it to someone who is looking for a speedy resolution. It takes time digging through the source code and an understanding of Node.js to figure out how to make it work.

Given an abundance of free time, I would love to write documentation for Architect and solve some of the issues around getting started. I have to wonder if it would be a worthwhile project to write my own Architect inspired, modern, dependency injection/inversion of control type framework to solve my “plug-in store” application problem.

## Learning curves.
As mentions, Documentation is pretty scarce and limited to two examples in the official GitHub repo and a handful of blogs around the internet. There should be more support and better documentation!

Resources:
- [c9/architect on Github](https://github.com/c9/architect)
- [Architecture Using Architect](https://medium.com/@ohbytheway/architecture-using-architect-8c8bb7d0277a#.lfbmvvax1)
- [Dependency injection in node js](https://mario.fyi/dependency-injection-in-node-js-and-other-architectural-patterns/)
- [Dependency injection in JS using architect](http://zedapp.org/2014/04/dependency-injection-in-javascript-using-architect/)

#<a name="day7"></a> Day 7: Vue.js!
Before jumping in to check out Vue.js, I had heard a lot of good things about the framework. After watching Evan You ([@youyuxi](https://twitter.com/youyuxi))’s talk on Vue.js, it seems that it is in line with my current thinking around how frameworks should work. In a nutshell, that is being less prescriptive, but extensible. The idea of a “progressive framework” sounds good–and in Vue.js’s case, works well. I haven’t formed a solid opinion on whether or not I like the idea of keeping all of the HTML, CSS, and JS of a component smushed in one file (in the past I’ve been against it), but so far in Vue, it works OK.

For my dip into Vue, I spent more time playing with the well-documented examples on the official site, watching the talk, and reading through the documentation and source code of Vue. I didn’t get too much hands on time with this, but it is something I look forward to re-visiting in the future.

## Learning curves
As with every framework, there is a prescribed way to do things. Setting up a new Vue project is pretty painless. The biggest hurdle is probably learning what Vue can do, how it handles it and learning to write the code to execute it.

Resources:
- [Vue.js Official guide](https://vuejs.org/v2/guide/)
- [Vue.js Talk by Evan You](https://www.youtube.com/watch?v=pBBSp_iIiVM&feature=youtu.be)

#<a name="day8"></a> Day 8: Typescript
Typescript is/can be used with Angular 2, so I wanted to spend some time working with TypeScript separate from A2.

TypeScript is essentially syntactic sugar for writing clean Javascript. An example is `namespace` and `export` which simply compile down to an immediately invoked function to keep namespaced items block scoped. This is the big take away, since TypeScript compiles to regular Javascript, the rules in TS are not held true at run time but are at compile time. TypeScript is largely (almost 100%) a developer tool for writing more descriptive code. It makes sense to reach for Typescript to keep code organized and "strict".

As a bonus, TypeScript development in VSCode is very nice.

## Learning curves
Most of what typescript offers is very straightforward. There are only a few new things to learn as far as syntax and definition go, to get started. A couple things still have me a bit confused (after only a couple of hours) and that is type declaration for Arrays and Generics–since I don’t come from a static typed language like C+ or Java.

Resources:
- [Lynda.com TypeScript essential training](https://www.lynda.com/Typescript-tutorials/TypeScript-Essential-Training/421807-2.html)
- [TypeScript in VSCode](https://code.visualstudio.com/Docs/languages/typescript)
- [TypeScript Playground](https://www.typescriptlang.org/play/index.html)

#<a name="day9"></a> Day 9: Angular 2
A couple of years ago I had small projects that ran on Angular 1.4 (I think it was 1.4). Since then, I haven’t spent any time following Angular other than simply being aware that Angular 2 came out. Today I wanted to give A2 a try coupled with my newly acquired familiarity with TypeScript.

The largest difference I noticed (from 1.4) was the setup and tooling is now much more complicated than just adding a single Angular source file. The `Package.json` and `tsconfig.json` are quite large on their own and understand what the functionality of each setting and dependency is a lot of overhead. Not to mention the tooling to build ES6 modules with System.js, Webpack, Browserify, or similar. The quick start guide is helpful, and there is a CLI tool that can help with the boilerplate code.

Frameworks as large as Angular inspire me to spend more time with them. A few hours in a single day is not enough time to experience even just the basics.

## Learning Curves
The setup and configuration overhead is a bit cumbersome. As with all comprehensive frameworks, there is going to be an investment that one needs to make in learning all of the proprietary syntax and keywords (e.g., Angular core components, decorators, “ng” keywords). Knowing Javascript well is probably a good prerequisite to Angular since some of the patterns seem complicated for a beginner—not to mention the added layer of TypeScript.

Resources:
[Official Angular 2 Quickstart](https://angular.io/docs/ts/latest/quickstart.html)
[Frontend Masters Building Angular2 Apps](https://frontendmasters.com/courses/angular-2/)
[Angular2 tutorial for beginners](https://www.youtube.com/watch?v=_-CD_5YhJTA)

#<a name="day10"></a> Day 10: React Native

React Native is more of a _platform_ than a framework and it's  powerful platform. I have little React experience, only a couple applications I’ve helped build. One of the benefits of React Native is that any knowledge you have from React web transfers over (it’s the same) and can be used to build native applications.

Writing the application code should be [is] easy to pick up for anyone used to ES6 or have a pretty strong understanding of Javascript. The ‘base’ application code or the minimum amount of setup you need to start a project isn’t overwhelming. The command line tool takes care of many tasks, including starting a new project and building the app in iOS/Android simulators (unless you break things like me)

Since I haven’t done any Android development, ever, the setup process to use [Genymotion](https://www.genymotion.com/fun-zone/) and Android SDK along with React Native ate up all the time I had devoted to the project today. On the plus side, now I have it all set-up for future projects.

## Learning curves
React Native is a solid platform and the products built on it out in the wild are proof that it's a stable platform for your project. A reoccurring them, at the risk of being too repetitive, is that large frameworks require time and experience to learn all of the proprietary commands, architecture, and nuances. Because React native is javascript with some different syntax and a less-traditional way of handling project organization (separation of HTML, CSS, JS, directory structure, etc.) it can be challenging to adopt.

Once dependencies are installed, getting the hot reloading working and the app to build and refresh in the native device simulators was troublesome.

Along those same lines, the initial setup and build process took a long time to get dependencies working properly, etc. It took me over an hour for everything.
Setup on a new machine will take time. However, if you're working with React on a regular basis, it shouldn't be a problem.

Bonus: somehow I broke `npm`, so that took more time to repair.

Resources:
- [React Native official docs](https://facebook.github.io/react-native/releases/0.24/docs/getting-started.html)
- [Android setup](https://facebook.github.io/react-native/releases/0.24/docs/android-setup.html)
- [FE Masters React](https://frontendmasters.com/courses/react-native/)

#<a name="day11"></a> Day 11: Touching on Ember.js

Ember is one of those frameworks that I’ve heard of for a long time and never took the time to explore. Ember’s “Convention over Configuration” philosophy means that with the help of the Ember CLI (command line interface), project directory structure, file name conventions, etc. are all predefined, and developers are expected to work within this convention. The strict convention could be considered an advantage, or disadvantage depending on one's personal style.

Compared to other Javascript Frameworks, I find that the Ember CLI and tooling are excellent. There are many developer conveniences included, like live a live reloading server and testing; which makes getting started developing an app, quick.

## Learning curves
The standard amount of getting used to the pre-configured, pre-architected structure of a framework is required, but the effort level is relatively low with Ember.

Mastering all of what Ember has to over will take time. I’m especially interested in spending more time with Ember Data and the way it interacts with _any_ backend and normalizes data queries

Resources:
- [FE Masters Ember](https://frontendmasters.com/courses/ember-2/)
- [Lynda Ember.js Essential Training](https://www.lynda.com/Ember-js-tutorials/Ember-js-Essential-Training/480960-2.html)
- [Official Ember starter guide](https://guides.emberjs.com/v2.9.0/tutorial/routes-and-templates/)

#<a name="day12"></a> Day 12: Next.js
Next.js is a “universal Javascript application” framework built on top of React, Webpack, and Babel. Next.js does a lot of cool things under the hood to solve a lot of performance problems often seen in other applications. One major thing Next does is automatic code splitting; this is managed through explicit dependency management with ES6 module imports—I like this a lot.

With tucking most of the framework engine under the hood, Next keeps the directory structure clean and minimal. I always appreciate clean folders and this is perfect for developers who don’t like folder cruft.

Next is brand new as of last month (Oct 2016) and under current development. It’s production ready now (Nov 2016) and while it is powerful as is, there is a promising roadmap outlined in the [official repository](https://github.com/zeit/next.js). With tooling included and only one node module to install, getting a project running with Next is extremely fast and convenient.

## Learning curves
Next is an opinionated framework. It strictly enforces patterns on how to manage pages and components–as do many frameworks. The development process is quite simple since currently, developers only need to be concerned with pages and components; which each contain explicit dependencies and markup. Getting used to this _simplified_ application architecture might take some time.

Coming from React will help a lot since Next is built on top of it. Next.js's decision to use Glamor for CSS in JavaScript can be a slight learning curve (or perceived downside) if you're not familiar or in favor of Styles in JavaScript.

Resources:
- [Official next blog](https://zeit.co/blog/next)
- [Github readme](https://github.com/zeit/next.js)
- [Glamor Repository](https://github.com/threepointone/glamor)

#<a name="day13"></a> Day 13: Taking a break from JS with R programming
R programming has a reputation for being the best language for statistical analysis. After spending a bit of time with R, I can see how easy it is to work with and how powerful it can be when used with large datasets. R can crunch numbers and show correlations as well as distributions. Additionally, R is used for Machine Learning and other things like image processing and facial recognition.

R syntax is straightforward and similar in ways to Python; which makes jumping in easy. I started with R in the terminal, tried out RStudio and VSCode with R ([Tutorial on how to setup the R process in VSCode](http://jdav.is/2015/07/28/r-with-visual-studio-code/)). As much as I currently enjoy using VSCode, for something like R, a dedicated IDE is better. RStudio has great visualizations built in (one of R’s main features!), project management, plug-in management, git, and more!

## Learning curves
If you’re not a stats person or used to working with vectors; this can take a bit of a dive plus experience to understand fully. Finding the right project or use case to become thoroughly acquainted with R programming is tricky. Since the power of R comes from processing data, getting a real dataset to practice with is key.

Resources:
- [R Tutorial](https://statsguys.wordpress.com/2014/01/03/first-post/)
- [Lynda.com Up and running with R](https://www.lynda.com/R-tutorials/Up-Running-R/120612-2.html)


#<a name="day14"></a> Day 14: Attempt at understanding Haskell!
Haskell is an interesting programming language. For a front-end web focused developer who spends most of the time in dynamically typed languages like Javascript and Python, Haskell is full of fun, new concepts.

Among some of the more interesting of features in Haskell are the function definition syntax and emphasis on recursion. There are no `For` loops in Haskell and all _loops_ are called through recursive function calls.

## Learning Curves

The, "no loops, use recursion” philosophy is tricky. I struggled to grasp the execution of recursion in Haskell entirely. Something in which I  may come back to expand. Additionally, while not super complicated, the syntax in Haskell will take a moment to get become accustomed.

There are a handful of concepts that may be brand new, including pattern matching, cases, lambdas, pure functions, Monads, and non-overwriting function declarations.

Resources:
- [Learn You A Haskell](http://learnyouahaskell.com/chapters)
- [Syntax in Haskell](http://rigaux.org/language-study/syntax-across-languages-per-language/Haskell.html)
- [Sudoku Solver in Haskell](http://paarsgames.nl/2013/07/29/sudoku-solver-in-haskell/)

#<a name="day15"></a> Day 15: Socket.io
I’ve always come across Socket.io, but never had a project or reason to build anything with it. As a popular interface for Web Sockets, I had high hopes. I was pleased to work with the Socket.io API on both the client and server sides. Setup is easy, and using it is intuitive.

The number of products/projects that you can build with Socket.io are vast and open-ended—anything that can benefit from instant data. Getting started is very quick and easy.

Looking forward to building something with Socket.io!

## Learning curves
The Getting Started tutorial is good enough to get going, but the example implementations are a limited to the single chat app. Making sure that the server-side and client-side `socket` is running is important.

Bridging the client/server relationship with the different `emit` and `on` methods could take a while to grab.

Resources:
- [Socket.io official getting started](http://socket.io/get-started/chat/)
- [David Walsh web sockets blog](https://davidwalsh.name/websocket)
- [Nodesource understanding socket-io](https://nodesource.com/blog/understanding-socketio/)

#<a name="day16"></a> Day 16: Matter.js Physics Engine
I’ve wanted to get my hands on a Canvas based physics engine for quite a while. Matter.js provides a lot of functionality and as far as I know, a complete javascript physics engine—it’s also extensible with plugins if needed.

Implementation of the getting started guide was easy enough and building off of it wasn’t too difficult. The game idea I had in my head to get done today was a bit over reaching for the amount of time I had to work on it. I spent the majority of the allocated time searching on how to do certain things.

Given the ease of use, I wouldn’t hesitate to come back to Matter.js for any future game development. It’s lightweight and doesn’t feel like it needs excessive setup and configuration. The default physics just work out of the box.


##Learning curves
Learning all of a physics engine the size of Matter.js is not something that can be accomplished in a few hours. However, the API is easy to use and pick up quickly.

I found that the while the API documentation is solid and the GitHub Wiki is good; it would be nice to have a bit more of the “getting started” style walkthrough guides. I found myself having to browse the API documentation and read every property/method to try and figure out how to do what I wanted to.

Resources
- [Matter.js Official Docs](http://brm.io/matter-js/docs/index.html)
- [Matter.js Github Wiki](https://github.com/liabru/matter-js/wiki)

#<a name="day17"></a> Day 17: Brunch

Another build tool? I thought, but of course, with an open mind, I gave Brunch.io a try. Brunch simplifies tooling setup config compared other popular build tools and has a number pre-configured “skeleton” projects. In addition to the base functions, Brunch is extensible with a number of plug-ins—as you would expect.

Plug-ins “Just Work,” (as advertised). I was a bit perplexed when I installed the Sass plug-in. After installation a was left with a bit of “what do I configure next” when I was surprised to see that running `brunch build` just compiled my sass. Nice.

Convenient! Most of what I’d consider standard environment tools that I’m always adding to my `gulpfile.js` when in Gulp (or Grunt) is built into Brunch–like a basic server, file watching, and auto browser reload.

## Learning Curves
Configuration is simple. However, there was some discrepancy in the way the documentation is written. Some config examples are written as .js modules, some as JSON, and some as Coffee Script or YAML depending on the author.

While great, the “just works” nature of plugins isn’t well explained and can be a bit confusing. With a lot of the conveniences tucked under the hood, it can be hard to understand everything; though the documentation helps a lot.

Resources:
- [Getting Started with Brunch](http://brunch.io/docs/getting-started)
- [Brunch Guide, Readme](https://github.com/brunch/brunch-guide#readme)
- [Brunch Sass](https://github.com/brunch/sass-brunch)

#<a name="day18"></a> Day 18: The basics of Phaser

Phaser is more than just a physics engine; it’s an entire HTML game platform. It has _all_ the things you need to build a game, including a robust physics engine, audio, 2D & 3D, Camera controls, text, animation input handlers, and a lot more.

Method and property names of the Phaser API are named in plain English; which makes working with Phaser easy to pick up. There is a lot to explore within Phaser, and the game possibilities seem endless. The example gallery of games built on Phaser is quite impressive. I feel that it truly is a gaming platform that can build production-ready HTML based games.

## Learning Curves
Getting started is easy enough, and the learning resources seem quite vast. There wasn’t any trouble in getting going to build my first game. The only learning curve is time to understand the capabilities and best practices. Making a fully considered game will take time learning the extent of what Phaser has to offer.

Resources:
- [Phaser Sandbox](https://phaser.io/sandbox/edit/3)
- [OpenGameArt, open source assets](http://opengameart.org/)
- [Phaser Readme](https://github.com/photonstorm/phaser/tree/v2.6.2)

#<a name"day18"></a> Day 19: Rust lang

Rust is another programming language that is competitive with C/C++; neither of which I've used before. However, I felt comfortable working with it even though I was very new. The syntax is slightly different from the languages I'm used to (JS, Python), and the architecture of a Rust application (as far as I know after a few hours) is very similar to a Node.js application. Similar to Node, Rust has Cargo; which makes development easy and friendly.

Cargo is a package/dependency manager for Rust. Very quickly, in the Rust guide, you will switch over to using Cargo to manage the project and have to become familiar with the `Cargo.toml`  file. This file is very similar to the `package.json` file of Node NPM projects.

Working with Rust is pretty friendly. There is a lot to learn, but the compiler is pretty good about reporting issues.

## Learning curves
As stated in the docs, coming from a Dynamic language (like I am) you’ll have to get used to compiling to an executable, and then running the executable—they’re two different steps. While this isn’t a big issue, it’s something to keep in mind.

Rust is less forgiving with semi-colons than Javascript, so making sure all statements end in a `;` is important. Missing semi-colons will throw errors at compile time.

Many concepts seem unique to Rust, or at least may be an introduction to them. Some examples are immutable variables by default, associated functions, patterns, macros, and references. You can find all the interesting things in the [Syntax and Semantics Chapter of the rust book](https://doc.rust-lang.org/book/syntax-and-semantics.html).

The getting started docs are well written and multi-platform friendly–something that is often neglected.

Resources:
- [Getting Started, “The Book"](https://doc.rust-lang.org/book/getting-started.html)
- [Pluralsight Rust Fundamentals](https://app.pluralsight.com/library/courses/rust-fundamentals/table-of-contents)
- [Rust Playground](http://play.integer32.com/)

#<a name="day20"></a> Day 20: Elm Lang

🤔 Elm compiles down to Javascript, but it's much more than just a different way of writing JS. Unlike Coffee Script orTypescript which are both just javascript, Elm is a functional programming language of its own.

Elm is pretty enjoyable to work with after you get through all of the learning curves. All the benchmarks show the benefits of performance and the other benefits Elm provides like "no runtime exceptions" are other reasons to choose Elm. It seems that some are having good luck using Elm with Elixer or Pheonix to build apps. [More info here](http://blog.carbonfive.com/2016/04/19/elixir-and-phoenix-the-future-of-web-apis-and-apps/)

## Learning Curves

When building web apps, Elm brings HTML and CSS into the Elm script. The HTML syntax in Elm is essentially swapping `<>` to `[]` brackets with extra confusion—I’m still not used to writing this way, it's different than anything else I've ever seen thus far.

I don’t know how much it’s used, but my experience with the `elm—repl` was that it is moderately slow. It also seems to rely on an internet connection which resulted in some issues when on poor (train) internet.

Some concepts are quite removed from my front-end dev expertise. Things like `foldp` folds, and Elm's Subs and commands structure are over my head; it may be the same for other front-end focused developers.

Resources:
- [Elm guide](https://guide.elm-lang.org/)
- [Elm Tutorial: SPA](https://www.elm-tutorial.org/en/)
- [Brandon Richey’s Elm Tutorial. Pt -1 (slightly outdated)](https://medium.com/p/11d7a53b1a78)
- [Brandon Richey’s Elm Tutorial. Pt -2](https://medium.com/p/7932781396ef)
- [Brandon Richey’s Elm Tutorial. Pt -3](https://medium.com/p/e1c649bd0d96)

#<a name="day21"></a> Day 21: Er…Lang
Erlang is (another) functional programming language. It advertises speed and scalability, especially where multi-cpu computing is concerned. Apparently, Erlang is used mostly in telecom (companies like T-mobile, Motorola, and Ericsson use it) but is also used in other instances where scalability and concurrency need to be top tier.

Working on a small, hello world application with Erlang has been challenging. Mostly because the resources out there are aimed at truly learning the language and not just building something with minimal understanding. That being said, going through the “Learn you some Erlang” tutorial, I’ve found writing Erlang to be very friendly. Friendly like Python (kinda). Some of the syntax is weird and I could do without, but it’s easy. I’ve noticed a number of concepts That were new to me when studying R-lang to be much better explained in different Erlang docs—like Guards!

## Learning Curves
Being that I built the least out of all of the previous 20 different frameworks and languages; I’d say the largest factor for learning Erlang is time. Everything that was presented to me in both starter guides, The official one and the one on _Learn You Some Erlang_ was clear and understandable. Time is a factor only because the syntax is unique and there are a lot of “new” things to learn before you can get started building “projects"

Some of the unique characteristics to Erlang are the `.` full stops. Don’t forget to use the full stop `.` after expressions, or they will continue indefinitely (more or less) until they’re stopped—this one that I continue to forget. Additionally,
there is no native String type so working with and manipulating string can be cumbersome and apparently is one of the biggest critiques of Erlang. Finally, the different comparison operators. What you may be used to as `== !=` is `=:= =/=` in Erlang

Resources:
- [Erlang official site](http://erlang.org/doc/getting_started/intro.html)
- [Learn You Some Erlang](http://learnyousomeerlang.com/introduction#what-is-erlang)

#<a name="day22"></a> Day 22: Ionic (featuring A2 & TS)
Ionic is a framework for building native applications with HTML, CSS, and Javascript. Ionic uses the power of Cordova to help build the native apps. Native does not just mean iOS and Android. Ionic has many other platforms you can compile to, including OSX, Windows, web, and more.

Ionic pairs with Angular. You can choose Angular 1.5 or 2. Ionic itself is a  library of pre-styled components for native environments—it reminds me of components in Xcode. Ionic Components are essentially HTML-components that work across multiple platforms.

## The Ionic Creator.
You don’t need to use the creator to use Ionic. If you do, you will get some very quick shortcuts to design and export a base application UI. Creator feels very similar to using a simplified version of Xcode combined with Sketch—it’s not an IDE. Which is to say, it is convenient and comfortable. It also means that you’re only setting up the basic view and app page flow. Any dynamic content or functions will eventually be written outside of the Ionic Creator. I didn't test Creator PRO which looks to give more options as far as code editing within Creator.

Unfortunately, Ionic Creator (at this time) doesn’t support exporting for Ionic2 which uses Angular 2. Ionic 1.* with Angular 1.5 is stable and is what the Pluralsight tutorial is based around, so there isn’t an issue there. Just preference.

## Learning Curves
You will need to know or be familiar with Angular (for Ionic 2, you need Angular 2 and TypeScript) to get started working with Ionic. Aside from that, there isn't much that is too difficult to pick up. The Ionic CLI has a lot of commands that you may or may not need to know, but they are well documented and easy to figure out.

Ionic components are HTML web components and have some special parameters that control layout that you will need to become familiar with. Again, this is documented well in the official docs.

Resources:
- [Official Getting started](https://ionicframework.com/getting-started/)
- [Pluralsight Ionic Framework (slightly dated, still good)](https://app.pluralsight.com/library/courses/ionic-framework-tools-patterns/table-of-contents)
- [Building A2, Ionic2 app tutorial](http://gonehybrid.com/build-your-first-mobile-app-with-ionic-2-angular-2-part-5/)

#<a name="day23"></a> Day 23: Meteor

Meteor is an excellent platform for building the web and native apps. Like Ionic, it leverages the power of Cordova to compile native apps. There are some similarities to Ionic, but Meteor is unique in that it is a fully considered application developing platform. Meteor ships with all the packages you need to work with a database (Mongo) and add user authentication, test your app; both of which are essentially for most apps.

I spent a little time with Meteor in the past, but since there have been major updates in the last couple of years, I thought I’d give it another try. I remember Meteor to be developer friendly and set up in a flexible way, and both of those still hold true. Meteor is flexible on many levels and can be used in conjunction with other frameworks—typically seen with Angular or React.

## Learning curves
Meteor keeps a lot under the hood and developers will have to determine which modules should be imported when–much like any platform. Based on one's preference, developers will have to either pick up a tempting framework like Angular or learn Meteor’s templating structure, Blaze. Learning Blaze is easy, and its syntax is much like handlebars.

Overall, the official guides and tutorials on Meteor.com are sufficient in teaching how to work with and get started with all of the technologies within Meteor. Time to get up and running with a functioning app or prototype is very quick–especially if you have a Javascript background.

Resources
- [Official guides](https://www.meteor.com/)


#<a name="day24"></a> Day 24: Messenger App [Bot]

When I was working with API.AI last month, I discovered how simple it was to integrate with Messenger through the API.AI interface and connect it to a Natural Language Processing bot. Since then, I’ve wanted to work with messenger and discover what it’s like to develop for.

Once everything is setup, working with the Messenger API seems straightforward. I did spend most of my time getting the app functioning and deployed to Heroku; which meant I only had a chance to read through the API documentation. All features/methods in the API are well covered and include helpful examples.

## Learning curves
Facebook applications to me have always seemed to have a significant overhead of “app configuration” on the Facebook Developer side. Setting up tokens and pages, etc. If you’re not familiar with this, it can be a bit of a hassle. Additionally, I went the route of setting up a Heroku Node application for the Messenger webhooks; which took an additional amount of setup and overhead when developing.

The toughest part is setting up the application in Facebook and deploying (or figuring out how to work locally, which I didn’t bother with) a functioning app. The official guide that I used as my single resource did cover everything well, but it does gloss over some minor details that expect the reader to be familiar with Facebook applications and having a functioning server somewhere.

Resources:
- [Messenger app quick start](https://developers.facebook.com/docs/messenger-platform/guides/quick-start)


#<a name="day25"></a> Day 25: Polymer Element

Web components have been making a steady climb in popularity lately, and with the continued development and push of Polymer, it’s growing even quicker. I was excited to make custom web components with Polymer finally, and in doing so, I worked with the CLI’s boilerplates for Elements and Starter App’s.

The Polymer CLI makes it quick to get started in an environment for writing and testing custom web components (and applications). I found that once I was familiar with the folder structure, I could work quickly. The CLI generates a bit of code for tests, documentation, and demos which are all helpful. For the most part, though, you can ignore all of them and focus on writing your component in a single file—for simple components at least.

Working with Polymer was mostly pleasant and seems to be the standard these days for creating custom web components. I haven’t tried any of the other frameworks or even the bare minimum polyfills, but I probably just use Polymer on future projects.

## Learning curves
Polymer leverages HTML imports, which requires at least a basic understanding of how they work (easy). The Polymer CLI has some fancy routing with the `bower_components` that changes the path for importing dependencies which can be a bit confusing but is mostly a “set it and forget it” kind of thing.

While I found the API friendly and mostly vanilla Javascript, some Polymer methods are tricky to understand in a short time. The documentation covers everything but can be a bit tough to comprehend in my opinion.

Lastly, since Polymer has gone through some significant changes throughout its version and has had a big following, I found a lot of resources around the web to be out of date, or at least slightly out of date; this has been particularly true on StackOverflow.

Resources:
- [Webcomponents.org intro](http://webcomponents.org/articles/a-quick-polymer-introduction/)
- [Polymer Docs](https://www.polymer-project.org/1.0/docs/tools/polymer-cli)
- [Pluralsight Working with Polymer.js Elements](https://app.pluralsight.com/library/courses/polymer-js-elements-working/table-of-contents)
- [Polycast video series](https://www.youtube.com/watch?v=SkhCs-IDgS4&list=PLNYkxOF6rcIDdS7HWIC_BYRunV6MHs5xo)
- [Polymer CLI readme](https://github.com/Polymer/polymer-cli)


#<a name="day26"></a> Day 26: Service Workers, offline first.

I’ve followed service workers since what feels like the first Google talk about them by Jake Archibald. Over the last year service worker support has been growing and so has my interest as well as interest in the industry.

I Started with the bare minimum set up to get content to work offline and load under “lie-fi” using the new Cache API. Using the service worker’s so far has been easy and fun. Having content load while offline is nice! Especially when that is dynamic data from a third-party API like Google Maps. I Can’t wait to have support for both ServiceWorker and Cache on iOS.

## Learning Curves
If you’re already familiar with `fetch` and `localStorage`, you should have an easy time understanding `serviceWorker` and how to implement it. If not, then there will be a bit of overhead understanding how those work before diving into service workers.

The API is easy to understand, and the documentation around the web is extensive.

Resources:
- [Google, Intro to service workers](https://developers.google.com/web/fundamentals/getting-started/primers/service-workers)
- [Google, getting started with PWA](https://developers.google.com/web/updates/2015/12/getting-started-pwa)
- [Offline Cookbook](https://jakearchibald.com/2014/offline-cookbook/)
- [Using ServiceWorkers, MDN](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API/Using_Service_Workers)
- [Cache API, MDN](https://developer.mozilla.org/en-US/docs/Web/API/Cache)

#<a name="day27"></a> Day 27: Swift 3

Back when Swift was first announced, I jumped on it to build iOS and WatchOS apps no longer needing Objective C. Since then, I haven’t touched Swift and it has transformed into what is now version 3, so I thought it was time to pick it up again. 

Having a REPL built into OS X is very handy. Unfortunately, I don’t know what the setup process for running Swift on Windows is (maybe using the Linux versions?). Even though the playground and the REPL are perfect for writing and testing code snippets, most of the development is done in Xcode for apps and a lot of this can be a little “drag and drop-y”. This takes a bit away from learning Swift.  I ended up brushing up on Swift syntax in Playgrounds the most.

## Learning curves
Getting Xcode up and running with the necessary profiles can be a headache if you don’t already have it set up, especially when it comes to building and running apps. Luckily, once it’s working, you can begin testing Swift code in Playgrounds within Xcode. 

As for actually writing Swift (not dealing with the Xcode interface), if you come from Javascript or Python I think you’ll find the syntax to be familiar and friendly. Swift is a very heavily supported language. The resources for learning are vast including videos, courses, tutorials, examples,  official documentation; it's all widely available from many sources. Because of the support and resources, it's probably one of the easiest modern languages to learn.

Resources:
- [Swift REPL](https://swift.org/getting-started/#using-the-repl)
- [Swift Guided Tour](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/GuidedTour.html)
- [Mapbox iOS SKD first steps](https://www.mapbox.com/help/first-steps-ios-sdk/)
- [Jared Davidson: Custom Table View Cells](https://www.youtube.com/watch?v=zAWO9rldyUE)


#<a name="day28"></a> Day 28: Total.js Node Framework

Total.js is a Node platform “similar to Python’s Django” or other app/website platforms that bundle up all the dependencies you *may* need–like a server, a database, routing, etc.

After poking around a bit with the file structure and documentation, I was able to make sense of how things operated. I’m not sure if this project is being actively developed, but I feel like it’s “almost there”. The CLI is useful, like with other platforms, but again it’s “almost there.”

From what I’ve seen in the examples and on the Total.js marketing site, it looks like Total.js can ship production ready products and is extensible—I just wasn’t quick able to get there in the short time I spent with it.

## Learning Curves
Total.js has its way of doing just about everything, which isn’t necessarily a bad thing. I did find the official documentation to be challenging to understand and unclear at times. Along the same lines, there is a lot of code tucked under the hood, which makes things a little difficult see how they work. For instance, I didn’t really know it supported Sass until I poked around the generated code and noticed a single `$color: #67B13D;` definition.

For people used to Handlerbars/Jinja style templating, you’ll find the Total.js View-Engine to to be different, but not challenging.

Resources:
- [official get-started page](https://www.totaljs.com/get-started/)
- [Examples on GitHub](https://github.com/totaljs/examples)

#<a name="day29"></a> Day 29: Mo.js

Mo.js is a new animation/motion framework for motion on the web. It works especially well with SVG animations as well as regular DOM animations and tweens. As someone who is a big Greensock (GSAP) fan, I found Mo.js to be just as awesome. 

I haven’t done all the performance benchmarks or even really compared the two frameworks—I did get the CPU fans whirring on my 15" Macbook Pro. So far (after a few hours) Mo.js seems to provide a few different interfaces for animating things. 

 Mo.js feels like its focus is more on shapes, and the API for creating custom shapes in Mo is very simple. By default, Mo.js ships with a few shape primitives like `circle`, `zigzag`, `polygon` and more. Adding custom SVG shapes is as simple as extending the `mojs.CustomShape` class.

There are native tweens, as well as unique animation “primitives” like `burst` and `swirl`. Similar to Greensock, there is also the concept of Timelines to chain/group animations in sequence. I love Timelines in Greensock and am glad to see them here.

Mo.js seems to provide more customizable easing curves by allowing developers to import an SVG Path to use as easing curves. There is even a great tool to build them. Also, while still young, the Mo.js Tool suite is well designed—I like it a lot. It currently consists of the Player and curve tool

## Learning Curves
If you’ve ever worked with animation frameworks, whether that’s Action Script in Flash, native CSS animations, Greensock, or even Framer, you will quickly adapt to Mo.js. If this is your first time, there is a little work to do to understand the concepts, but I’d rate them as beginner friendly.

SVG knowledge is not required but is extremely helpful. At the minimum, developers will need to be familiar with how inline SVG’s are laid out in the DOM and how to select different parts, etc. to work with them in JS.

Overall, Mo.js is easy to use and with only one dependency, getting started in CodePen is highly recommended.

Resources:
- [Sarah Drasner article no CSS Tricks](https://css-tricks.com/introduction-mo-js/)
- [GitHub Repo](https://github.com/legomushroom/mojs)
- [API docs](https://github.com/legomushroom/mojs/blob/master/api/readme.md)
- [Official Tutorials](http://mojs.io/tutorials/shape/)
- [Mo-js player tool](https://github.com/legomushroom/mojs-player)

#<a name="day30"></a> Day 30: MicroPython, Feather, Si7021.

Since day 1 of this challenge, I’ve been excited to get back to working with microcontrollers, electronics, and sensors, specifically with Python—I’ve used Arduino in the past.

It’s been a couple of years since I wrote my last Arduino code. I didn’t even have the IDE installed on my machine anymore. I was starting from scratch at developing for the Adafruit Feather; which wasn’t a bad thing at all. I had ordered myself the board, and a breakout board for the temperature and humidity sensor and got put everything together on the breadboard.

I started with the basic setup tutorials (had to go through a lot), followed by getting LED lights to blink, then finally working with I2C sensors. It was a long process before getting to the “main project, ” but after only 4 hours, I had a working product.

## Learning Curves
Setting up the development environment on the board and your machine takes some time and a bit of reading. I found the best documentation split between the official MicroPython docs and the guides on Adafruit; both were paramount in my understanding and setup.

The actual coding and writing of MicroPython is __just python!__ The only learning curve is the `machine` library; which is for setting up interaction with the board, pins, and I2C protocol, etc. I didn't explore any other libraries besides, `machine`, but learning them is very similar to becoming familiar with any third-party Python package.

*Finding the command for finding the USB port was hard. it’s `ls /dev/tty.*` and so far I only found this command through watching a video.

Resources:
- [Adafruit Feather HUZZAH ESP8266](https://www.adafruit.com/product/2821)
- [Adafruit Si7021 Temperature & Humidity Sensor Breakout Board](https://www.adafruit.com/product/3251)
- [How to load Micropython on a board](https://learn.adafruit.com/micropython-basics-how-to-load-micropython-on-a-board/esp8266)
- [How to load files: AMPY](https://learn.adafruit.com/micropython-basics-load-files-and-run-code)
- [MicroPython I2C Devices Tutorial](https://learn.adafruit.com/micropython-hardware-i2c-devices/overview)
- [Micropy Si7021 module](https://gist.github.com/minyk/7c3070bc1c2766633b8ff1d4d51089cf)
- [Hexidecimal -> Decimal converter](http://www.binaryhexconverter.com/hex-to-decimal-converter)
- [Micropython file system documentation](http://docs.micropython.org/en/v1.8.2/esp8266/esp8266/tutorial/filesystem.html)
