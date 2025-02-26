Open Browsers
===

[![Buy me a coffee](https://img.shields.io/badge/Buy%20me%20a%20coffee-048754?logo=buymeacoffee)](https://jaywcjlove.github.io/#/sponsor)
[![CI](https://github.com/react-doc/open-browsers/actions/workflows/ci.yml/badge.svg)](https://github.com/react-doc/open-browsers/actions/workflows/ci.yml)
[![npm version](https://img.shields.io/npm/v/open-browsers.svg)](https://www.npmjs.com/package/open-browsers)
[![NPM Downloads](https://img.shields.io/npm/dm/open-browsers.svg?style=flat&label=)](https://www.npmjs.com/package/open-browsers)

Attempts to open the browser with a given URL.
On Mac OS X, attempts to reuse an existing Chrome tab via AppleScript.
Otherwise, falls back to [open](https://github.com/sindresorhus/open) behavior. `open-browsers` form [react-dev-utils](https://github.com/facebook/create-react-app/blob/b8ff97be72c02128c0917437d98e1b672a25ceb4/packages/react-dev-utils/openBrowser.js).

### Install

```bash
npm install open-browsers --save-dev
```

### Usage

> openBrowsers(url: string): boolean 

```js
var openBrowsers = require('open-browsers');
if (openBrowsers('http://localhost:3000')) {
  console.log('The browser tab has been opened!');
}
```

## Contributors

As always, thanks to our amazing contributors!

<!--GAMFC--><!--\n-->

<a href="https://github.com/jaywcjlove" title="小弟调调"><img src="https://avatars.githubusercontent.com/u/1680273?v=4" width="42;" alt="小弟调调"/></a><!--GAMFC-END-->

Made with [contributors](https://github.com/jaywcjlove/github-action-contributors).

### License

`open-browsers` is open source software licensed as MIT.