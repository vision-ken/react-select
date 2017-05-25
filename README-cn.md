[![NPM](https://img.shields.io/npm/v/react-select.svg)](https://www.npmjs.com/package/react-select)
[![Build Status](https://travis-ci.org/JedWatson/react-select.svg?branch=master)](https://travis-ci.org/JedWatson/react-select)
[![Coverage Status](https://coveralls.io/repos/JedWatson/react-select/badge.svg?branch=master&service=github)](https://coveralls.io/github/JedWatson/react-select?branch=master)
[![Supported by Thinkmill](https://thinkmill.github.io/badge/heart.svg)](http://thinkmill.com.au/?utm_source=github&utm_medium=badge&utm_campaign=react-select)
[![CDNJS](https://img.shields.io/cdnjs/v/react-select.svg)](https://cdnjs.com/libraries/react-select)

React-Select
============

一个 Select 组件的 [React](http://facebook.github.io/react/index.html) 实现. Initially built for use in [KeystoneJS](http://www.keystonejs.com).


## New version 1.0.0-rc

I've nearly completed a major rewrite of this component (see issue [#568](https://github.com/JedWatson/react-select/issues/568) for details and progress). The new code has been merged into `master`, and `react-select@1.0.0-rc` has been published to npm and bower.

1.0.0 has some breaking changes. The documentation is still being updated for the new API; notes on the changes can be found in [CHANGES.md](https://github.com/JedWatson/react-select/blob/master/CHANGES.md) and will be finalised into [HISTORY.md](https://github.com/JedWatson/react-select/blob/master/HISTORY.md) soon.

Testing, feedback and PRs for the new version are appreciated.


## Demo & Examples

Live demo: [jedwatson.github.io/react-select](http://jedwatson.github.io/react-select/)

The live demo is still running `v0.9.1`.

To build the **new 1.0.0** examples locally, clone this repo then run:

```javascript
nvm use v5.8.0
npm install
npm start
```

Then open [`localhost:8000`](http://localhost:8000) in a browser.


## 构建组件准备发布
```javascript
npm run build
```