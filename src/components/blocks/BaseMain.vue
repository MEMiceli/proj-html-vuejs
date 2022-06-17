<template>
  <main>
      <BaseRunner/>
      <OneSection/>
      <TwoSection/>
      <ThreeSection/>
      <FourthSection/>
      <FiftySection/>
      <SixthSection/>
      <ContactSection/>
  </main>
</template>

<script>
import BaseRunner from '../sections/BaseRunner.vue'
import OneSection from '../sections/OneSection.vue'
import TwoSection from '../sections/TwoSection.vue'
import ThreeSection from '../sections/ThreeSection.vue'
import FourthSection from '../sections/FourthSection.vue'
import FiftySection from '../sections/FiftySection.vue'
import SixthSection from '../sections/SixthSection.vue'
import ContactSection from '../sections/ContactSection.vue'
export default {
    name: 'BaseMain',
    components: {
    BaseRunner,
    OneSection,
    TwoSection,
    ThreeSection,
    FourthSection,
    FiftySection,
    SixthSection,
    ContactSection,
    
    
  }

}
</script>

<style scoped lang="scss">

</style>