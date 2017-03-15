<template>
<div id="app">

</div>
</template>

<script>
import Hello from '../../components/Hello'

export default {
  data() {
    return {

    }
  },
  name: 'app',
  components: {
    Hello
  },
  methods: {

  }
}
</script>

<style lang='scss'>
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    // 让字体更加清晰，css3属性 兼容性：ie全挂，其他浏览器可以正常使用
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
</style>
