<template>
  <main>
      <BaseRunner/>
      <OneSection/>
      <TwoSection/>
  </main>
</template>

<script>
import BaseRunner from '../sections/BaseRunner.vue'
import OneSection from '../sections/OneSection.vue'
import TwoSection from '../sections/TwoSection.vue'
export default {
    name: 'BaseMain',
    components: {
    BaseRunner,
    OneSection,
    TwoSection,
  }

}
</script>

<style scoped lang="scss">

</style>