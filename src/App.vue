<template>
  <div id="app">
    <TypeEffect />
  </div>
</template>

<script>
import TypeEffect from './components/TypeEffect.vue'

export default {
  name: 'app',
  components: {
    TypeEffect
  }
}
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css?family=Righteous');

  body {
    margin: 0;
    padding: 0;
  }

  #app {
    font-family: 'Righteous', arial;
    font-weight: normal;
    font-size: 4rem;
    color: #fff;
    background-color: #241E17;
    width: 100%;
    min-height: 100vh;
  }
</style>
