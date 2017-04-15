## Installation

The command-line version of `coffee` is available as a [Node.js](https://nodejs.org/) utility. The [core compiler](/v<%= majorVersion %>/browser-compiler/coffee-script.js) however, does not depend on Node, and can be run in any JavaScript environment, or in the browser (see [Try CoffeeScript](#try)).

To install, first make sure you have a working copy of the latest stable version of [Node.js](https://nodejs.org/). You can then install CoffeeScript globally with [npm](https://www.npmjs.com/):

```bash
npm install --global coffee-script
```

When you need CoffeeScript as a dependency of a project, within that project’s folder you can install it locally:

```bash
npm install --save coffee-script
```
