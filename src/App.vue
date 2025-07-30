<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import {
    CustomerReviews,
    Footer,
    Hero,
    PopularProducts,
    Services,
    SpecialOffers,
    Subscribe,
    SuperQuality
} from './sections'
</script>

<template>
  <main class="relative">
    <!-- <Nav/> -->
    <section class="sm:px-16 px-8 sm:py-24 py-12">
      <Hero/>
    </section>
 
    <section class="sm:px-16 px-8 sm:py-24 py-12">
      <PopularProducts/>
    </section>
    <section class="sm:px-16 px-8 sm:py-24 py-12">
      <SuperQuality/>
    </section>
    <section class="sm:px-16 px-8 py-10">
      <Services/>
    </section>
    <section class="sm:px-16 px-8 sm:py-24 py-12">
      <SpecialOffer/>
    </section> 
    <section  class="bg-blue-100 sm:px-16 px-8 sm:py-24 py-12">
      <CustomerReviews/>
    </section> 
    <section class="sm:px-16 px-8 sm:py-32 py-16 w-full">
      <Subscribe/>
    </section> 
    <section class="bg-black sm:px-16 px-8 sm:pt-24 pt-12 pb-8">
      <Footer/>
    </section> 
  </main>
</template>

<style scoped></style>
