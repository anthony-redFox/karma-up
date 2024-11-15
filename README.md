# Karma
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/Second-Live/karma-up) [![npm version](https://img.shields.io/npm/v/karma-up.svg?style=flat-square)](https://www.npmjs.com/package/karma-up) [![npm downloads](https://img.shields.io/npm/dm/karma-up.svg?style=flat-square)](https://npmcharts.com/compare/karma-up?minimal=true)

 [![Code Climate](https://img.shields.io/codeclimate/maintainability/karma-runner/karma)](https://codeclimate.com/github/karma-runner/karma) [![PRs Welcome](https://img.shields.io/badge/prs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com/) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

A simple tool that allows you to execute JavaScript code in multiple
_real_ browsers.

> The main purpose of Karma is to make your test-driven development easy,
>  fast, and fun.


## Help and Support

> For questions and support please use the mailing list or Gitter.
> The issue tracker is for bug reports and feature discussions only.

* Obligatory [documentation]
* Quick questions:
[![Gitter Chat](https://img.shields.io/badge/GITTER-join%20chat-green.svg?style=flat-square)](https://gitter.im/karma-runner/karma)
* Longer questions: [Mailing List]
* Bug reports [Issue Tracker]
* Everything less than 140 characters: [@JsKarma] on Twitter



## When should I use Karma?

* You want to test code in *real* browsers.
* You want to test code in multiple browsers (desktop, mobile,
  tablets, etc.).
* You want to execute your tests locally during development.
* You want to execute your tests on a continuous integration server.
* You want to execute your tests on every save.
* You love your terminal.
* You don't want your (testing) life to suck.
* You want to use [Istanbul] to automagically generate coverage
  reports.
* You want to use [RequireJS] for your source files.


## But I still want to use \_insert testing library\_

Karma is not a testing framework, nor an assertion library.
Karma just launches an HTTP server, and generates the test runner HTML file you probably already know from your favourite testing framework.
So for testing purposes you can use pretty much anything you like. There are already plugins for most of the common testing frameworks:

* [Jasmine]
* [Mocha]
* [QUnit]
* and [many others](https://www.npmjs.com/search?q=keywords:karma-adapter)

If you can't find an adapter for your favourite framework, don't worry and write your own.
It's not that hard and we are here to help.


## Which Browsers can I use?

All the major browsers are supported, if you want to know more see the
[browsers] page.


## Troubleshooting
See [FAQ](https://karma-runner.github.io/latest/intro/faq.html).


## I want to use it. Where do I sign?

You don't need to sign anything but here are some resources to help
you to get started...


### Obligatory Screencast.

Every serious project has a screencast, so here is ours.  Just click
[here] and let the show begin.


### Installation.

See [installation](https://karma-runner.github.io/latest/intro/installation.html).


### Using it.

See [configuration](https://karma-runner.github.io/latest/intro/configuration.html).


## This is so great. I want to help.

Please, see
[contributing](https://karma-runner.github.io/latest/dev/contributing.html).


## Why did you create this?

Throughout the development of [AngularJS], we've been using [JSTD] for
testing. I really think that JSTD is a great idea. Unfortunately, we
had many problems with JSTD, so we decided to write our own test
runner based on the same idea. We wanted a simple tool just for
executing JavaScript tests that is both stable and fast. That's why we
use the awesome [Socket.io] library and [Node.js].


## My boss wants a license. So where is it?
[MIT License](./LICENSE)


[AngularJS]: https://angularjs.org/
[JSTD]: https://code.google.com/p/js-test-driver/
[Socket.io]: https://socket.io/
[Node.js]: https://nodejs.org/
[Jasmine]: https://github.com/karma-runner/karma-jasmine
[QUnit]: https://github.com/karma-runner/karma-qunit
[here]: https://www.youtube.com/watch?v=MVw8N3hTfCI
[Mailing List]: https://groups.google.com/forum/#!forum/karma-users
[Issue Tracker]: https://github.com/karma-runner/karma/issues
[@JsKarma]: https://twitter.com/JsKarma
[RequireJS]: https://requirejs.org/
[Istanbul]: https://github.com/gotwarlost/istanbul

[browsers]: https://karma-runner.github.io/latest/config/browsers.html
[documentation]: https://karma-runner.github.io
