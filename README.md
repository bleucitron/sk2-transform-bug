# SK2 transform bug

- Run
```
npm i
npm run build
npm run preview
```

- Open built app in a browser that does not support [logical assignment syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_OR_assignment#browser_compatibility) (Firefox 78.15 in my tests, you can find sources [here](https://ftp.mozilla.org/pub/firefox/releases/78.15.0esr/))

- Open the console, and witness the error
