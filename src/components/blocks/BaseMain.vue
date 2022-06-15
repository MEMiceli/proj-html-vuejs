<template>
  <main>
      <BaseRunner/>
      <OneSection/>
  </main>
</template>

<script>
import BaseRunner from '../sections/BaseRunner.vue'
import OneSection from '../sections/OneSection.vue'
export default {
    name: 'BaseMain',
    components: {
    BaseRunner,
    OneSection,
  }

}
</script>

<style scoped lang="scss">

</style>