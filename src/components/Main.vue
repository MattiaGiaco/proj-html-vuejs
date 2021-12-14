<template>
  <main>
   <Junbotron />
   <SectionInfo />
   <SectionYT />
  </main>
</template>

<script>

import Junbotron from './Junbotron.vue'
import SectionInfo from './SectionInfo.vue'
import SectionYT from './SectionYT.vue'

export default {
  name: 'Main',
  components: {
    Junbotron,
    SectionInfo,
    SectionYT
  }
}
</script>

<style lang="scss">

</style>