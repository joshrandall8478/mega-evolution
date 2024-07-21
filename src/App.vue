<script setup>
// import HelloWorld from './components/HelloWorld.vue'
import TopBar from './components/TopBar.vue';



</script>
<script>
import data from './assets/data.json';
export default {
  data() {
    return {
      pokemons: data
    };
  }
}
</script>


<template>
  <TopBar />
  <div v-for="pokemon in pokemons">
    <!-- <img :src="pokemon.originalImage" alt=""> -->
     {{  }}
   </div>
</template>

<style scoped>
.pokemon__list{
  list-style: none;
}
</style>
