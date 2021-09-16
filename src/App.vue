<template>
  <div id="app">
    <header>
      <Navbar/>
      <Jumbo/>
    </header>
    <main>
      <BannerPlain/>
      <CirclesSection/>
      <SliderSection/>
      <SectionTitle/>
      <Text2cols/>
    </main>
    <Footer/>

  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Jumbo from './components/Jumbo.vue'
import BannerPlain from './components/BannerPlain.vue'
import CirclesSection from './components/CirclesSection.vue'
import SliderSection from './components/SliderSection.vue'
import SectionTitle from './components/SectionTitle.vue'
import Text2cols from './components/Text2cols.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Jumbo,
    Footer,
    BannerPlain,
    CirclesSection,
    SliderSection,
    SectionTitle,
    Text2cols,
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
