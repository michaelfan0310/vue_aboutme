<template>
  <div id="app">
  <NavAbout />
  <TitleAbout />
  <DescriptionAbout />
  <PicturesAbout />
  <FooterAbout />
  </div>
  
</template>

<script>
import NavAbout from './components/NavAbout.vue'
import TitleAbout from './components/TitleAbout.vue'
import DescriptionAbout from './components/DescriptionAbout.vue'
import PicturesAbout from './components/PicturesAbout.vue'
import FooterAbout from './components/FooterAbout.vue'


export default {
  name: 'App',
  components: {
    NavAbout,
    TitleAbout,
    DescriptionAbout,
    PicturesAbout,
    FooterAbout
}
}
</script>

<style >
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: whitesmoke;
 /* background-image: url('./assets/about-bg2.jpg'); */
  /* margin-top: 60px; */
}
 html { cursor:url('data:image/png;base64,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'),pointer;
    
    }
</style>
