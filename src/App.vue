<template>
  <header-section/>
  <news-section/>
  <most-read/>
  <economy-section/>
</template>

<script>
import NewsSection from './components/News.vue'
import MostRead from './components/MostRead.vue'
import EconomySection from './components/EconomySection.vue'
import HeaderSection from './components/HeaderSection.vue'
import 'bootstrap/dist/css/bootstrap.min.css'
import 'bootstrap/dist/js/bootstrap.bundle.js'
import './assets/styling/App.scss'

export default {
  name: 'App',
  components: {
    NewsSection,
    MostRead,
    EconomySection,
    HeaderSection
  }
}
</script>

