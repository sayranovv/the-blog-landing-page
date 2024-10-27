<script>
export default {
  props: ['cards']
}
</script>

<template>
  <div class="card-container">
    <div v-for="card in cards" :key="card.id" class="card">
      <img :src="card.image" alt="card" class="card-img">
      <p class="card-title">{{ card.title }}</p>
      <p class="card-category">{{ card.category }}</p>
    </div>
  </div>
</template>

<style scoped>

</style>