# electron-vue-sample

This code demonstrates how to set up Vue.js 2.0 single-file components with electron-forge.

### Getting started

```
npm install -g electron-forge
npm install
npm start
```

### Creating an installable package

```
npm install -g electron-forge
electron-forge make
```

### Where's Webpack? Gulp? All that stuff I had to set up!

Nowhere :)  electron-vue-sample uses [electron-compile](https://github.com/electron/electron-compile), which is a remarkably pain-free way to use all of your favorite web languages with Electron.
