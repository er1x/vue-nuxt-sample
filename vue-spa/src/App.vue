<template>
  <div id="app">
    <sample-component></sample-component>
  </div>
</template>

<script>
import { SampleComponent } from 'shared-components'

export default {
  name: 'app',
  components: { SampleComponent }
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
