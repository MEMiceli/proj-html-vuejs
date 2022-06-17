<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <BaseFoother/>

  </div>
</template>

<script>
import BaseHeader from './components/blocks/BaseHeader.vue'
import BaseMain from './components/blocks/BaseMain.vue'
import BaseFoother from './components/blocks/BaseFoother.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    BaseFoother,
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss';
</style>
