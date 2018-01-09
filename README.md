# vue-ui

> A Vuejs based UI for Revisit

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


https://proto.io/freebies/onoff/
https://cbuelter.wordpress.com/2017/05/08/force-reset-a-vue-component/


Dropzone:
- add an additional model
- replace current model

Validate JSON:
- required settings
- correct number of frames

Convert objects to arrays and change key to a number

Longer animation period (for multiple animations)
- option to leave shorter animation at final value or just remove it

TODO:
- Need to refactor everything
- Rollup? Tree-shaking? Remove unused CSS/JS/...

Export animation file
Export URL query

Resize event listener

```
ready: function () {
  window.addEventListener('resize', this.handleResize)
},
beforeDestroy: function () {
  window.removeEventListener('resize', this.handleResize)
}
```

Buttons across the top? Reset camera, etc.?


https://gltf-rs.github.io/gltf-validator-web/?https://raw.githubusercontent.com/gltf-rs/gltf/master/gltf-json/tests/minimal_accessor_invalid.gltf


Point and click on objects
