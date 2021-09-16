<template>
  <div id="app">
    <header>
      <Navbar/>
      <Jumbo/>
    </header>
    <main>
      <BannerPlain/>
      <CirclesSection/>
    </main>
    <Footer/>

  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Jumbo from './components/Jumbo.vue'
import BannerPlain from './components/BannerPlain.vue'
import CirclesSection from './components/CirclesSection.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Jumbo,
    Footer,
    BannerPlain,
    CirclesSection,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box; 
}
#app {

}

ul{
  list-style: none;
}
</style>
