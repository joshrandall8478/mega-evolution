<script setup>
// import HelloWorld from './components/HelloWorld.vue'
import TopBar from './components/TopBar.vue';
import megaEvolutions from './assets/data.json';
</script>

<template>
  <TopBar />
  <div>
    <ul class="pokemon__list">
      <div v-for="data in megaEvolutions">{{ data }}</div>
    </ul>
  </div>
</template>

<style scoped>
.pokemon__list{
  list-style: none;
}
</style>
