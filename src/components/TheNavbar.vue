<script>
export default {
  props: ['urls'],
  setup() {
    return {

    }
  }
}
</script>

<template>
  <nav class="navbar">
    <ul class="ul">
      <li class="nav-item"><a :href="this.urls[0]">Blog</a></li>
      <li class="nav-item"><a :href="this.urls[1]">Press</a></li>
      <li class="nav-item"><a :href="this.urls[2]">Join Us</a></li>
    </ul>
  </nav>
</template>

<style scoped>
</style>