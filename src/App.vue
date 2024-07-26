<script setup>
// import HelloWorld from './components/HelloWorld.vue'
import TopBar from './components/TopBar.vue';



</script>
<script>
import { data } from './assets/data.json';
</script>


<template>
  <TopBar />
  <main>
    <div class="container">
      <a class="pokemon__container" v-for="pokemon in data">
        <div class="pokemon__image">
          <img :src="pokemon.originalImage" alt="">
        </div>
        <div class="pokemon__data">
          <h1>{{ pokemon.name }}</h1>
          <h3>Type{{ pokemon.originalType.length == 1 ? '' : 's' }}: <a v-for="(type, index) in pokemon.originalType">{{ type }}{{ index !== pokemon.originalType.length - 1 ? ', ' : '' }}</a></h3>
        </div>
      </a>
     </div>
  </main>
</template>

<style scoped>
.pokemon__list{
  list-style: none;
}
</style>
