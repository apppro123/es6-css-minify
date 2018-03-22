# ES5/ES6/CSS Minifier

[![Downloads](https://img.shields.io/vscode-marketplace/d/olback.es6-css-minify.svg?label=Downloads)](https://marketplace.visualstudio.com/items?itemName=olback.es6-css-minify)
[![Visual Studio Marketplace](https://img.shields.io/vscode-marketplace/v/olback.es6-css-minify.svg?label=VS%20Code%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=olback.es6-css-minify)
[![GitHub package version](https://img.shields.io/github/package-json/v/olback/es6-css-minify.svg?logo=github&label=Github)](https://github.com/olback/es6-css-minify)

A simple ES5/ES6/CSS3 minifier.  
A `Minify` button should appear in the status bar when opening a `.js` or a `.css` file. You can also run `Minify` by clicking `F1`.

### Loading custom configs
By default the extension will look for `.uglifyrc` and `.cleancssrc`.  
You can change the paths in settings. After changing settings in any of the config files, make sure to reload with `Minify: Reload config`. If the reload fails, make sure you don't have syntax errors in your config. If you want to go back to the default config, rename/delete your config file(s).

### Minify on save
Minify on save can be dissabled in settings.  
  

[uglify-es](https://www.npmjs.com/package/uglify-es) [clean-css](https://www.npmjs.com/package/clean-css)
