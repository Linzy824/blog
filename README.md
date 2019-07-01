# Linzy's Blog

## vue
- [] This is a complete item
### deployment in non-root path
```javascript
  module.exports = {
    publicPath:'your website path', //eg. /vue-app/  
    ...
  }
  new Router({  //if use router
    mode:"history", //Only needs in this mode.Another condition is Multi-page.
    base:'your website path', //eg. /vue-app/  
    ...
  })
```
> **publicPath in vue.config.js & base in router config**
>vue-cli >=3.3 the key `publicPath` is baseUrl in old version
