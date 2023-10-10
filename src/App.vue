<script>
import FooterVue from './components/Footer.vue';
import Header from './components/Header.vue';

export default {
name: 'App',

components:{
  Header,
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
<Header />
<main>
  <h1>{{ titolo }}</h1>

</main>

  

  <FooterVue />
</template>


<style>
body{
  background-color: blue;
  color: whitesmoke;
}

main{
  min-height: 400px;
}
</style>