<template>

<Header/>

<MainContent/>

<Footer/>

</template>

<script>
import Header from './components/Header.vue'
import MainContent from './components/MainContent.vue';
import Footer from './components/Footer.vue';

  export default {
    components:{
    Header,
    MainContent,
    Footer,
   
},
    data(){
      return{
       
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>