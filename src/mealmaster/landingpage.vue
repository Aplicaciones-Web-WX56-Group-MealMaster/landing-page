<script setup>
import Toolbar from './components/toolbar.component.vue'
import HeroImage from './components/heroimage.component.vue'
import AboutUs from './components/aboutus.component.vue'
import Testimonials from './components/testimonials.component.vue'
import Plans from './components/plans.component.vue'
import Footer from './components/footer.component.vue'
</script>

<template>
  <section class="landing-page">
    <div><Toolbar></Toolbar></div>
    <div><HeroImage></HeroImage></div>
    <div><AboutUs></AboutUs></div>
    <div><Testimonials></Testimonials></div>
    <div><Plans></Plans></div>
    <div><Footer></Footer></div>
  </section>
</template>

<style scoped>

</style>