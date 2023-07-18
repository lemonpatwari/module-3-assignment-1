<script setup>
import Header from './components/common/Header.vue'
import MyFooter from './components/common/Footer.vue'
import Hero from "./components/Hero.vue";
import Client from "./components/Client.vue";
import About from "./components/About.vue";
import Stats from "./components/Stats.vue";
import Services from "./components/Services.vue";
import Features from "./components/Features.vue";
import Portfolio from "./components/Portfolio.vue";
import Pricing from "./components/Pricing.vue";
import Faq from "./components/Faq.vue";
import Team from "./components/Team.vue";
import CallToAction from "./components/CallToAction.vue";
import Testimonials from "./components/Testimonials.vue";
import RecentPosts from "./components/RecentPosts.vue";
import Contact from "./components/Contact.vue";
</script>

<template>
  <Header/>
  <main id="main">

    <Hero/>

    <Client/>

    <About/>

    <Stats/>

    <Services/>

    <Features/>

    <Portfolio/>

    <Pricing/>

    <Faq/>

    <Team/>

    <CallToAction/>

    <Testimonials/>

    <RecentPosts/>

    <Contact/>

  </main>


  <MyFooter/>

  <!-- Scroll Top Button -->
  <a href="#" id="scroll-top" class="scroll-top d-flex align-items-center justify-content-center"><i
      class="bi bi-arrow-up-short"></i></a>

  <!-- Preloader -->
  <div id="preloader">
    <div></div>
    <div></div>
    <div></div>
    <div></div>
  </div>
</template>

<style scoped>

</style>
