<script>
import { RouterLink, RouterView } from 'vue-router'
import AppHeader from '@/components/AppHeader.vue'
import GetStarted from '@/components/GetStarted.vue'
import Features from '@/components/Features.vue'
import StayProductive from '@/components/StayProductive.vue'
import Reviews from '@/components/Reviews.vue'
import AppFooter from '@/components/AppFooter.vue'
export default{
  components:{
    AppHeader,
    GetStarted,
    Features,
    StayProductive,
    Reviews,
    AppFooter
  }
}
</script>

<template>
  <main class="main-layout">
    <AppHeader/>
    <!-- <RouterView /> -->
    <GetStarted/>
    <Features/>
    <StayProductive/>
    <Reviews/>
    <AppFooter/>
  </main>
</template>

