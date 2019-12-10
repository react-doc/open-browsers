open-browsers
---

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

### License

`open-browsers` is open source software licensed as MIT.