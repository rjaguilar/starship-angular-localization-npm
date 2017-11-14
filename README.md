# angular-localization 

*THIS IS AN NPM PACKAGE FOR THE BELOW*

*AngularJS Localization done right.*

[![Build Status](https://travis-ci.org/doshprompt/angular-localization.svg?branch=master)](https://travis-ci.org/doshprompt/angular-localization)
[![Code Climate](https://codeclimate.com/github/doshprompt/angular-localization/badges/gpa.svg)](https://codeclimate.com/github/doshprompt/angular-localization)
[![Test Coverage](https://codeclimate.com/github/doshprompt/angular-localization/badges/coverage.svg)](https://codeclimate.com/github/doshprompt/angular-localization/coverage)
[![Bower version](https://badge.fury.io/bo/angular-localization.svg)](http://badge.fury.io/bo/angular-localization)
[![GitHub license](https://img.shields.io/github/license/doshprompt/angular-localization.svg)](https://github.com/doshprompt/angular-localization/blob/master/LICENSE)

[![Dependency Status](https://david-dm.org/doshprompt/angular-localization.svg?theme=shields.io)](https://david-dm.org/doshpromot/angular-localization)
[![devDependency Status](https://david-dm.org/doshprompt/angular-localization/dev-status.svg?theme=shields.io)](https://david-dm.org/angular-localization#info=devDependencies)
[![Gitter chat](https://badges.gitter.im/doshprompt/angular-localization.png)](https://gitter.im/doshprompt/angular-localization)
[![Stories in Ready](https://badge.waffle.io/doshprompt/angular-localization.png?label=ready&title=Ready)](https://waffle.io/doshprompt/angular-localization)
[![Donate to help support angular-localization development](http://img.shields.io/gittip/doshprompt.svg)](https://www.gittip.com/doshprompt/)

___

## Table of Contents

- [Overview](#overview)
    - [Build Dependencies](#build-dependencies)
    - [Dear Developer](#dear-developer)
- [Getting Started](#getting-started)
    - [Quick Start](#quick-start)
    - [Wiring It Up](#wiring-it-up)
    - [Module Setup](#module-setup)
    - [Localization File Formats](#localization-file-formats)
- [Usage Examples](#usage-examples)
    - [i18n directive](#i18n-directive)
        - [Localize Using the i18n attribute](#localize-using-the-i18n-attribute)
        - [Localize with Dynamic User Data](#localize-with-dynamic-user-data)
    - [i18nAttr directive](#i18nattr-directive)
    - [locale service](#locale-service)
    - [i18n filter](#i18n-filter)
    - [Sample App](#sample-app)
- [License](#license)

## Overview

A localization module for [AngularJS](http://angularjs.org/) complete with core service and accompanying filter, directives etc.

It is based on a number of angularjs localization modules already available out there on the web,
and borrows heavily from the following list including but not limited to:

- http://dailyjs.com/2014/04/08/angular-localize/
- https://github.com/blueimp/angular-localize
- http://alicoding.com/how-to-localized-angularjs-app/

It was inspired by [Jim Lavin's AngularJS Resource Localization Service](https://github.com/lavinjj/angularjs-localizationservice)
who made an excellent first tutorial for his original version at [Coding Smackdown TV](http://codingsmackdown.tv/blog/2012/12/14/localizing-your-angularjs-app/)
which was later updated to include performance improvements [seen here](http://codingsmackdown.tv/blog/2013/04/23/localizing-your-angularjs-apps-update/).

### Sample App

I've created a sample app that uses this plugin to provide the text for the entire application.
I registered 'ngLocalize' in my app's dependency list and I then use a combination of
`ng-bind="'home.title' | i18n"`,
`{{ 'home.title' | i18n }}`,
`data-i18n="home.title"` and
`data-i18n-attr="{placeholder: 'home.title'}`
to insert the text into the page at run time along with their variously supported use-cases.

## License

The MIT License (MIT)

Copyright (c) 2014 Rahul Doshi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

[![Analytics](https://ga-beacon.appspot.com/UA-51468215-1/angular-localization/README.md)](https://github.com/igrigorik/ga-beacon)
[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/doshprompt/angular-localization/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
