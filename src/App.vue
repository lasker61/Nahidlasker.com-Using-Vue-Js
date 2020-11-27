<template>
  <HelloWorld></HelloWorld>
  <Main></Main>
  <Skills></Skills>
  <Resume></Resume>
  <Portfolio></Portfolio>
  <Service></Service>
  <Contact></Contact>
  <Footer></Footer>
  <Icon></Icon>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Main from './components/Main.vue'
import Skills from './components/Skills.vue'
import Resume from './components/Resume.vue'
import Portfolio from './components/Portfolio.vue'
import Service from './components/Service.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
import Icon from './components/Icon.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Main,
    Skills,
    Resume,
    Portfolio,
    Service,
    Contact,
    Footer,
    Icon
  }
}
</script>

<style>
#app {
  
}
</style>
