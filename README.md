> some style is usually to used
## Start
``` shell
npm install --save rest-css
```
## Use
#### you can use it in javascript(maybe vue, react, angluar, etc) directly;
- in javascript (maybe vue, react, angluar, etc)
``` javascript
//index.js, ng.js, react.js
import 'rest-css'
```
- in vue
``` vue
<template>
    <div id="app"></div>
</template>
<script>
    //引入css, 会自动打包，与在style标签中引入最后打包结果无区别
    //import css，package autoly
    import 'rest-css'
    export default { }
</script>
<style>
</style>
```
- also in css
``` css
@import url('../node_modules/rest-css/rest.css')
```
## Reference
- [-webkit-text-size-adjust属性说明](http://blog.csdn.net/mxy2013/article/details/49813331)