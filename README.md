# [www.dark-coder.com](https://www.dark-coder.com/)
# Nanobar
Super lighweight, pure JavaScript page load progress bar


********************************************************************************
## Status
[![GitHub Version](https://img.shields.io/github/release/the-muda-organization/nanobar.svg?style=for-the-badge)](https://github.com/the-muda-organization/nanobar)
[![License](https://img.shields.io/github/license/the-muda-organization/nanobar.svg?style=for-the-badge)](https://github.com/the-muda-organization/nanobar)


[![Github Star](https://img.shields.io/github/stars/the-muda-organization/nanobar.svg?style=for-the-badge)](https://github.com/the-muda-organization/nanobar)
[![Github Fork](https://img.shields.io/github/forks/the-muda-organization/nanobar.svg?style=for-the-badge)](https://github.com/the-muda-organization/nanobar)

[![JS gzip size](https://img.badgesize.io/the-muda-organization/nanobar/master/dist/nanobar.min.js?compression=gzip&label=JS+gzip+size)](https://github.com/the-muda-organization/nanobar/blob/master/dist/nanobar.min.js)


********************************************************************************
## [View Preview](https://rawcdn.githack.com/the-muda-organization/nanobar/bc45c370a045bb0026cce61b937902ac90dc021f/DEMO.html)
********************************************************************************

<img src="https://github.com/the-muda-organization/nanobar/blob/master/PREVIEW.jpg?raw=true" alt="" style="width:100%;display:block;">


********************************************************************************
## Table of contents
- [Status](#status)
- [Quick Start](#quick-start)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Versioning](#versioning)
- [Changelog](#changelog)
- [Team](#team)
- [Code of Conduct](#code-of-conduct)
- [Copyright and License](#copyright-and-license)


********************************************************************************
## Quick Start

Several options are available:
- [Download the latest release.](https://github.com/the-muda-organization/nanobar/archive/master.zip)
- Clone the repo: `git clone https://github.com/the-muda-organization/nanobar.git`
- Install with [Composer](https://getcomposer.org/): `composer require the-muda-organization/nanobar`


********************************************************************************
## What's included
Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

There are no dependencies. See below for [Installation Guide](#installation) and [How to Use](#how-to-use)
```
nanobar/
 │
 └─ dist/
    │
    ├── nanobar.js
    └── nanobar.min.js
```


********************************************************************************
## Bugs and feature requests
Have a bug or a feature request? Before opening a new issue search for existing and closed issues. If your problem or idea is not addressed yet, [open a new issue](https://github.com/the-muda-organization/nanobar/issues/new).


********************************************************************************
## Installation

1. Download and copy files to your project
2. Add JS to your project:
```html
    <script src="https://example.com/nanobar/1.x.x/nanobar.min.js"></script>
```
OR add script inline (recommended):
```html
    <script>Paste script here</script>
```
3. Place nanobar `<script>` right after opening `<body>` tag.
4. Ready to use!


********************************************************************************
## How to Use

Nanobar is designed to be placed in CDN and used on multiple pages. Nanobar has default background color set to red. You may set custom background color you like the most in JavaScript variables (at the beginning of the script).

If you want to change color on a single page add `data-nanobar=""` attribute to `<body>`. You can use any color value that is usually used in CSS `#nanobar{background: something}` - color name, hex value, gradients and more.

```html
    <body data-nanobar="#ff8c00">
    <body data-nanobar="blue">
    <body data-nanobar="linear-gradient(to right,#40e0d0,#ff8c00,#ff0080)">
```

> Do not add this attribute and do not leave blank if you don't want to change background color. JavaScript checks if data-nanobar="#ff8c00" has a new background color value.

Nanobar has assigned ID: `<div id="nanobar"></div>`

********************************************************************************
## Versioning
Nanobar will be maintained under the Semantic Versioning guidelines as much as possible. Releases will be numbered with the following format:
```<major>.<minor>.<patch>```


********************************************************************************
## Changelog
For last releases see detailed [CHANGELOG](https://github.com/the-muda-organization/nanobar/blob/master/CHANGELOG.md).


********************************************************************************
## Team
-  [Jakub Muda](https://github.com/jakubmuda)


********************************************************************************
## Code of conduct
We will behave ourselves if you behave yourselves. For more details see our
[CODE OF CONDUCT](https://github.com/the-muda-organization/nanobar/blob/master/CODE_OF_CONDUCT.md).


********************************************************************************
## Copyright and license
Code and documentation copyright 2017-2020 [The MUDA Organization](https://muda.pl).

Code released under the [MIT License](https://github.com/the-muda-organization/nanobar/blob/master/LICENSE).


********************************************************************************


