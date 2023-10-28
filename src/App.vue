<template>
  <HeaderSection/>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <AboutSection/> -->
  <!-- <TestimonialsSection/> -->
  <!-- <FooterSection/> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
import HeaderSection from './components/HeaderSection.vue'
// import HelloWorld from './components/HelloWorld.vue'
// import AboutSection from './components/AboutSection.vue'
// import TestimonialsSection from './components/TestimonialsSection.vue'
// import FooterSection from './components/FooterSection.vue'

export default {
  name: 'App',
  components: {
    HeaderSection,
    // HelloWorld,
    // AboutSection,
    // TestimonialsSection,
    // FooterSection
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
