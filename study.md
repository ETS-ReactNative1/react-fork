## How to debug

> [add-source-map](https://github.com/facebook/react/pull/21946)

* build by rollup
* try run rollup in watch mode with sourcemap

add dev npm scripts and run example

```json
{
  "scripts": {
    "dev": "nr build react/index,react-dom/index --type=UMD --watch",
    "build": "node ./scripts/rollup/build.js"
  }
}
```


