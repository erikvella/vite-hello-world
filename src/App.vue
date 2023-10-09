<script>
import FooterVue from './components/Footer.vue';
import HeaderVue from './components/Header.vue';

export default {
name: 'App',

components:{
  HeaderVue,
  FooterVue
},

data(){
  return{
    titolo: 'Ciao Vue',
  
  }
}
}
</script>


<template>
<HeaderVue />
  <h1>{{ titolo }}</h1>

  <FooterVue />
</template>


<style>
body{
  background-color: blue;
  color: whitesmoke;
}
</style>