<template>
  <div id="app">
   <HeaderComponents />
    <Jumbotron/>
    <MainComponent/>
    <FooterInfoCard />
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponents from '@/components/HeaderComponents.vue'
import Jumbotron from '@/components/JumbotronComponent.vue'
import MainComponent from '@/components/HeroMainComponent.vue'
import FooterInfoCard from '@/components/FooterInfoCardComponent.vue'
import FooterComponent from '@/components/footerComponent.vue'


export default {
  name: 'App',
  components: {
    HeaderComponents,
    Jumbotron,
    MainComponent,
    FooterInfoCard,
    FooterComponent
  }
}
</script>

<style lang="scss">
@import '@/assets/sass/partial/style.scss';

*{
  margin:0;
  padding:0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
  

</style>
