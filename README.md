
# Example of Node.js Server with babel 7 (latest version)

### Getting Start

```
npm install
```

### Babel Package
1. @babel/cli
2. @babel/core
3. @babel/preset-env


### How it's work?
**`npm run build`** compile **index.js** file and output the result into **dist folder**, then start a web server.

### Alternative - Another way without **.babelrc**
you could use `babel script.js --out-file [you-file].js --presets=@babel/preset-env` with the **presets** params which is same as what .babelrc doing.

Check out https://babeljs.io/docs/en/ for more information.
