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
      <Cards/>
      <Checklist/>
      <Banner-images/>
      <Jumbo2/>
      <SectionTitle2/>
      <News/>
      <Map/>
      <SectionTitle3/>
      <Contacts/>
      <Form/>
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
import Cards from './components/Cards.vue'
import Checklist from './components/Checklist.vue'
import BannerImages from './components/BannerImages.vue'
import Jumbo2 from './components/Jumbo2.vue'
import SectionTitle2 from './components/SectionTitle2.vue'
import News from './components/News.vue'
import Map from './components/Map.vue'
import SectionTitle3 from './components/SectionTitle3.vue'
import Contacts from './components/Contacts.vue'
import Form from './components/Form.vue'
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
    Cards,
    Checklist,
    BannerImages,
    Jumbo2,
    SectionTitle2,
    News,
    Map,
    SectionTitle3,
    Contacts,
    Form,
  }
}
</script>

<style lang="scss">
@import "@/assets/scss/_vars.scss";

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
