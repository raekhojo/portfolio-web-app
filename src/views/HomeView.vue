<template>
  <app-hero/>
  <app-featured-work/>
  <app-about/>
  <portfolio-pic/>
  <app-experience/>
  <app-services/>
  <app-cta/>
</template>

<script>
// @ is an alias to /src
import AppHero from '@/components/AppHero.vue'
import AppFeaturedWork from '@/components/AppFeaturedWork.vue'
import AppAbout from '@/components/AppAbout.vue'
import PortfolioPic from '@/components/PortfolioPic.vue'
import AppExperience from '@/components/AppExperience.vue'
import AppServices from '@/components/AppServices.vue'
import AppCta from '@/components/AppCta.vue'

export default {
  name: 'HomeView',
  components: {
    AppHero,
    AppFeaturedWork,
    AppAbout,
    PortfolioPic,
    AppExperience,
    AppServices,
    AppCta
  }
}
</script>
