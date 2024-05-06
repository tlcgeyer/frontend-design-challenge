<template>
  <NavBar/>
  <router-view/>
  <main></main>
  <FooterComp/>
</template>


<script>
import NavBar from './components/NavBar';
import FooterComp from './components/FooterComp';

export default {
  components: {
    NavBar,
    FooterComp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}


</style>

