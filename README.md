# vue-material Style Overrides

scss files to replace pixel-based values with `em`.

## Install

```bash
# install package
npm install @lgv/vue-material-style
```

### Use Module

```bash
// declare vue-material themeing like normal from the official vue-material project
import "vue-material/dist/vue-material.min.css";
import "vue-material/dist/theme/default.css";
...
...

// import vue-material-style high enough in the cascading for it to influence your style as you wish
@import "@lgv-vue-material-style/src/index.scss";
```
