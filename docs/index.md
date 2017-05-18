<h1 id="logo">
  <img src="/img/avatar.png" alt="Ractive.js" />
  <div class="name">Ractive.js</div>
  <div class="slogan">The diamond age of web development</div>
</h1>

<div id="cdn">
  <span class="fluff">&lt;script src="</span><a href="https://cdn.jsdelivr.net/npm/ractive" class="url">https://cdn.jsdelivr.net/npm/ractive</a><span class="fluff">"&gt;&lt;/script&gt;</span>
</div>

<div class="container" id="info-blocks">
  <div class="col-md-4">
    <h3>Live, reactive templating</h3>
    Ractive.js is a template-driven UI library, but unlike other tools that generate inert HTML, it transforms your templates into blueprints for apps that are interactive by default.
  </div>
  <div class="col-md-4">
    <h3>Powerful and extensible</h3>
    Two-way binding, animations, SVG support and much more are provided out-of-the-box - but you can add whatever functionality you need by downloading and creating plugins.
  </div>
  <div class="col-md-4">
    <h3>Optimised for your sanity</h3>
    Some tools force you to learn a new vocabulary and structure your app in a particular way. Ractive works for you, not the other way around - and it plays well with other libraries.
  </div>
</div>

## Usage

Using Ractive is very simple. Create a new instance using `new Ractive({...})` with the desired options. Code blocks with a ⇲ or ▶ button in the top-right corner will open the code in the interactive playground, so feel free to try them out and play around with them.

<div data-playground="N4IgFiBcoE5SBTAJgcwSANCAzlA2gLoC+WALvJjvDAAQC8NAdggO40BKAhgMakCWANwQAKYAB1GY0qU4w0pSDQDkAIwD2SAJ5KMEqaQQBbAA4AbTgcVKAPMYB8wYChgIE-RiiIkajl9z7GfAiMpF7WAPT2OnqkSBaciuKSpFLOru4oVgASCKamatHJUn4BQSFWAOpqMKZIAIRKMUQSRACUANyU3BREQA"></div>

```js
var ractive = Ractive({
    target: 'body',
    template: '<p>{{greeting}}, {{recipient}}</p>',
    data: {
        greeting: 'Hello',
        recipient: 'World!'
    }
});
```

While there are _no required options_, `target`, `template` and `data` are the most common. They specify _what element_ to attach an instance with _this markup_ having _this data_. Check out [Initialization Options](api/initialization-options.md) to learn more about the available options.

If you get stuck at any point, visit the [Get Support](get-started/support.md) page for places to find help.

## Other Downloads

Ractive is available via the following channels:

```sh
# jsDelivr
https://cdn.jsdelivr.net/npm/ractive

# CDNjs
https://cdnjs.com/libraries/ractive

# unpkg
https://unpkg.com/ractive

# npm
npm install --save-dev ractive

# Bower
bower install --save ractive
```

<div id="badges"></div>
[![Gitter chat](https://img.shields.io/gitter/room/ractivejs/ractive.svg?style=flat-square)](https://gitter.im/ractivejs/ractive)
[![npm version](https://img.shields.io/npm/v/ractive.svg?style=flat-square)](https://www.npmjs.com/package/ractive)
[![devDependency Status](https://img.shields.io/david/dev/ractivejs/ractive.svg?style=flat-square)](https://david-dm.org/RactiveJS/Ractive#info=devDependencies)
[![Build Status](https://img.shields.io/travis/ractivejs/ractive/dev.svg?style=flat-square)](https://travis-ci.org/ractivejs/ractive)
[![Coverage Status](https://img.shields.io/coveralls/ractivejs/ractive/dev.svg?style=flat-square)](https://coveralls.io/github/ractivejs/ractive?branch=dev)
[![npm downloads](https://img.shields.io/npm/dm/ractive.svg?style=flat-square)](https://www.npmjs.com/package/ractive)
[![Twitter Follow](https://img.shields.io/twitter/follow/ractivejs.svg?style=flat-square)](https://twitter.com/ractivejs)

## About Ractive.js

Ractive was originally created at [The Guardian (theguardian.com)](https://www.theguardian.com/) to produce news applications. A typical news app is heavily interactive, combines HTML and SVG, and is developed under extreme deadline pressure. It has to work reliably across browsers, and perform well even on mobile devices.

Unlike other frameworks, *Ractive works for you*, not the other way around. It doesn't have an opinion about the other tools you want to use with it. It also adapts to the approach you want to take. This means you're not locked-in to a framework-specific way of thinking. Should you hate one of your tools for some reason, you can easily swap it out for another and move on with life.

This project is the brainchild of an Englishman and has contributors from all over the world. There is an ecclectic mix of primarily the Queen's English, a fair amount of 'Murican English, and a bit of others here and there. Things like `adaptor`, `behaviour`, and `dependant` may have more than one spelling but we try to stick to the Queen's English to the extent that we are able.

<small>Fun fact: Fun fact: The name is a reference to Neal Stephenson's [The Diamond Age: Or, A Young Lady's Illustrated Primer](http://en.wikipedia.org/wiki/The_Diamond_Age) – a book about (among other things) the future of storytelling.</small>