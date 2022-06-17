<template>
  <main>
      <BaseRunner/>
      <OneSection/>
      <TwoSection/>
      <ThreeSection/>
      <FourthSection/>
  </main>
</template>

<script>
import BaseRunner from '../sections/BaseRunner.vue'
import OneSection from '../sections/OneSection.vue'
import TwoSection from '../sections/TwoSection.vue'
import ThreeSection from '../sections/ThreeSection.vue'
import FourthSection from '../sections/FourthSection.vue'
export default {
    name: 'BaseMain',
    components: {
    BaseRunner,
    OneSection,
    TwoSection,
    ThreeSection,
    FourthSection,
    
  }

}
</script>

<style scoped lang="scss">

</style>