<template>
    <div id="app">
       <cell></cell>
       <a href="test2.html">跳转test2</a>
       <a href="test3.html">跳转test3</a>
    </div>
</template>

<script>
import cell from '@/components/cell.vue'
export default {
  name: 'app',
  components: { cell }
}
</script>

<style>
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
