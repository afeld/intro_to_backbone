!SLIDE

# Intro to Backbone.js

Aidan Feldman

[github.com/afeld/intro\_to\_backbone](https://github.com/afeld/intro_to_backbone)

[![ZIP download](zip.png)](https://github.com/afeld/intro_to_backbone/archive/master.zip)

!SLIDE

# moi

* Senõr Web Developer, [Jux](https://jux.com)
* Instructor, [General Assembly](https://generalassemb.ly/) and [NYU](http://scps.nyu.edu/content/scps/faculty/faculty-profile.html?id=14293)
* [Sometime Backbone.js contributor](https://github.com/documentcloud/backbone/contributors)
* Author, *[Developing a Backbone.js Edge](http://bleedingedgepress.com/our-books/)* (more on that later)

!SLIDE

# Why Backbone vs. jQuery?

!SLIDE incremental

# Why Backbone vs. jQuery?

## code organization

* useful abstractions
    * Models & Collections
    * perisistence over REST
* encourage modularity
    * Views
* client-side routing

!SLIDE incremental

# Structure of a Backbone app

(over-generalized)

* initialize base "class"
    * think Java's `public static void main()`
    * usually a View
* load data (`<script>` or AJAX) into Models/Collections
* initialize sub-Views
    * bind to events on Models/Collections
    * bind between Views

!SLIDE

# Backbone Pieces

* [View](http://backbonejs.org/#View)
* [Model](http://backbonejs.org/#Model)
* [Collection](http://backbonejs.org/#Collection)

!SLIDE

# [Todos](https://github.com/afeld/intro_to_backbone/tree/master/todos) Walkthrough

!SLIDE incremental

# What is [Underscore.js](http://underscorejs.org/)?

* Backbone's only dependency, besides jQuery\*
* the "Standard Library" JS never had

!SLIDE

# Play time!

* tasks:
    * "mark all as complete" (solution [here](https://github.com/documentcloud/backbone/tree/0.9.10/examples/todos))
    * priority selector
    * order/filter by priority
* docs: [backbonejs.org](http://backbonejs.org/) and [underscorejs.org](http://underscorejs.org/)

!SLIDE incremental

# Why Backbone vs. [[TodoMVC](http://addyosmani.github.com/todomvc/) option]?

* easy to get set up
* easy to use pieces (both ways)
* [easy to understand](http://backbonejs.org/docs/backbone.html)

!SLIDE incremental

# Also

!SLIDE

## y'all get a free copy of *Developing a Backbone.js Edge*

!SLIDE

# Questions?

!SLIDE

# Fin.

Aidan Feldman

[@aidanfeldman](https://twitter.com/aidanfeldman)

[api.afeld.me](http://api.afeld.me)
