<template lang="pug">
TopImageVue
#middle
  #left
    LeftMenuVue
    LeftUpdate
  #right
    RightMarquee
    #page
      router-view
FooterText
</template>
<script setup>
import TopImageVue from '@/components/TopImage.vue'
import LeftMenuVue from './components/LeftMenu.vue'
import LeftUpdate from './components/LeftUpdate.vue'
import RightMarquee from './components/RightMarquee.vue'
import FooterText from './components/FooterText.vue'
</script>
