<template>
  <HeaderSection/>
  <ContentSection/>
  <AboutSection/>
  <TestimonialsSection/>
  <FooterSection/>
</template>

<script>
import HeaderSection from './components/HeaderSection.vue'
import ContentSection from './components/ContentSection.vue'
import AboutSection from './components/AboutSection.vue'
import TestimonialsSection from './components/TestimonialsSection.vue'
import FooterSection from './components/FooterSection.vue'

export default {
  name: 'App',
  components: {
    HeaderSection,
    ContentSection,
    AboutSection,
    TestimonialsSection,
    FooterSection
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
