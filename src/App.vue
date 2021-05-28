<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Navbar/>
  <TopBanner/>
  <AboutMe/>
  <Recommendations/>
  <Skills/>
  <Promo/>
  <Products/>
  <Testimonials/>
  <Contact/>
  <Footer/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AboutMe from './components/AboutMe.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
import Navbar from './components/Navbar.vue'
import Products from './components/Products.vue'
import Promo from './components/Promo.vue'
import Recommendations from './components/Recommendations.vue'
import Skills from './components/Skills.vue'
import Testimonials from './components/Testimonials.vue'
import TopBanner from './components/TopBanner.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    AboutMe,
    Contact,
    Footer,
    Navbar,
    Products,
    Promo,
    Recommendations,
    Skills,
    Testimonials,
    TopBanner
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
  margin-top: 60px;
}
</style>
