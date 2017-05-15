# 做一个类似 vue-loader 一样的文件加载器

能够像下面一样写页面

```vuejs
<template>
  <div>
    hello {{msg}}
  </div>
</template>

<script>
  export default {
    data() {
      return {
        msg: 'hello'
      }
    }
  }
</script>

<style>
  * {
    font-size: 10px;
  }
</style>
```
