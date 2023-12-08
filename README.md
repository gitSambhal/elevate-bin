# elevate

Precompiled binaries.

This tool allows you to start a program with elevated privileges from the command line. See [1],[2] for details.

[1] http://jpassing.com/2007/12/08/launch-elevated-processes-from-the-command-line/
[2] https://github.com/jpassing/elevate

# Installation

```shell
npm i --save @suhailakhtar/elevate-bin
```

# Get path to binaries

```javascript
const { pathElevate, pathElevate64 } = require("@suhailakhtar/elevate-bin");

console.log({ pathElevate, pathElevate64 });
```
