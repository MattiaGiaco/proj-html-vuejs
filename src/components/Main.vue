<template>
  <main>
   <Junbotron />
   <SectionInfo />
   <SectionYT />
   <Newsletter />
   <Workouts />
   <ShopItems />
   <Junbotron2 />
   <Sponsor />
   <OfTheDay />
  </main>
</template>

<script>

import Junbotron from './Junbotron.vue'
import SectionInfo from './SectionInfo.vue'
import SectionYT from './SectionYT.vue'
import Newsletter from './Newsletter.vue'
import Workouts from './Workouts.vue'
import ShopItems from './ShopItems.vue'
import Junbotron2 from './Junbotron2.vue'
import Sponsor from './Sponsor.vue'
import OfTheDay from './OfTheDay.vue'

export default {
  name: 'Main',
  components: {
    Junbotron,
    SectionInfo,
    SectionYT,
    Newsletter,
    Workouts,
    ShopItems,
    Junbotron2,
    Sponsor,
    OfTheDay
  }
}
</script>

<style lang="scss">

</style>