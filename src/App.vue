<template>
  <div id="app">
    <HeaderComponent />
    <JumboComponent />
    <InfoComponent />
    
  </div>
</template>

<script>
import HeaderComponent from '@/components/HeaderComponent.vue';
import JumboComponent from '@/components/JumbotronComponent.vue';
import InfoComponent from '@/components/InfoComponent.vue'


export default {
  name: 'App',
  components: {
    HeaderComponent,
    JumboComponent,
    InfoComponent
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: #2c3e50;
  margin-top: 60px;
}
</style>
