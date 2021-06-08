# Linzy's Blog

## vue
- [] this is an incomplete item
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
>vue-cli >=3.3 the key `publicPath` is `baseUrl` in old version

## css 
- [] this is an incomplete item
### text overflow 
```css
  {
    white-space:nowrap;
    display:inline-block;
    overflow:hidden;
    text-overflow:ellipse;
    overflow:ellipsis;
    width:200px;
  }
```
