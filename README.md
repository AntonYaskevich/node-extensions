# node-extensions

## Initial steps  
All modules are built with [node-gyp](https://www.npmjs.com/package/node-gyp) npm module.  
First u need some preinstalled features, there are [all steps](https://github.com/nodejs/node-gyp#installation).

## Installation  
```
$ npm install -g node-gyp
```
## Configuration and build  
Generate config for native module:  
```
$ node-gyp configure
```
Build native modules:  
```
$ node-gyp build
```

