<template>
  <input type="text" :placeholder="placeholder" ref="input" autocomplete="none"
    :value="value"/>
</template>

<script>
export default (function (x) { return x.default || x })(require('./autocompleteImpl.js'))
</script>
