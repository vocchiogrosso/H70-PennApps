<template>
  <div class="home">
    <LandingComp></LandingComp>
    <AboutComp></AboutComp>
  </div>
</template>

<script>
// @ is an alias to /src
import LandingComp from '@/components/LandingComp.vue'
import AboutComp from '@/components/AboutComp.vue'

export default {
  name: 'home',
  components: {
    LandingComp,
    AboutComp
  }
}
</script>
