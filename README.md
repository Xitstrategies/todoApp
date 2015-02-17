# CanJS TodoMVC Example

> CanJS is a MIT-licensed, client-side, JavaScript framework that makes building rich web applications easy.

> _[CanJS - canjs.com](http://canjs.com)_


## Use by Morgan Heimbeck

I am using this pulled from todomvc.com to demonstrate my knowledge of the tools provided. I am extending this basic front end todo app with a RESTFUL API that will provide the services and store the data. This will also be hooked up to sockets so that the data will be live bound to the server and any other users out there. 


## Implementation

The CanJS TodoMVC example uses [can.Component](http://canjs.com/guides/Components.html) introduced in CanJS 2.0.
can.Component supports declarative view bindings using Mustache/Handlebars as the template syntax.

Version 2 is mostly backwards compatible with previous 1.1.x version. For alternative architecture examples have a look at
the [TodoMVC 1.2.0 CanJS example](https://github.com/tastejs/todomvc/tree/1.2.0/architecture-examples/canjs).

### CanJS and JavaScriptMVC

CanJS is the extracted, more modern and more library-like MVC parts of [JavaScriptMVC](http://javascriptmvc.com), formerly known as jQueryMX.

JavaScriptMVC 3.3 uses CanJS for the MVC structure so this TodoMVC example applies to JavaScriptMVC as well.

Additionally, JavaScriptMVC contains:

- [CanJS](http://canjs.com) - For the MVC parts
- [jQuery++](http://jquerypp.com) - jQuery's missing utils and special events
- [StealJS](http://javascriptmvc.com/docs.html#!stealjs) - A JavaScript package manager
- [DocumentJS](http://javascriptmvc.com/docs.html#!DocumentJS) - A documentation engine
- [FuncUnit](http://funcunit.com) - jQuery style functional unit testing
