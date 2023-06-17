A template for writting packages for WLJS Frontend.
See meta-data in `package.json` file

```js
  "wljs-meta": {
    "css": "dist/styles.css", //styles written in CSS
    "jsmodule": "dist/kernel.js", //a compiled JS module from src/kernel.js using build procedure
    "wlkernel": "src/kernel.wl", //a file loaded into secondary Wolfram Kernel
    "wl": "src/frontend.wl", //a file loaded into the primary (frontend) Wolfram Kernel
    "autocomplete": "src/autocomplete.js" //a data file for autocomplete
  }
```

## Building
```bash
npm i
npm run build
```