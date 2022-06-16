<template>
  <main>
      <BaseRunner/>
      <OneSection/>
      <TwoSection/>
      <ThreeSection/>
  </main>
</template>

<script>
import BaseRunner from '../sections/BaseRunner.vue'
import OneSection from '../sections/OneSection.vue'
import TwoSection from '../sections/TwoSection.vue'
import ThreeSection from '../sections/ThreeSection.vue'
export default {
    name: 'BaseMain',
    components: {
    BaseRunner,
    OneSection,
    TwoSection,
    ThreeSection,
    
  }

}
</script>

<style scoped lang="scss">

</style>