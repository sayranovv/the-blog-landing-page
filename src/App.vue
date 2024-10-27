<template>
  <TheNavbar :urls="urlsData" />
  <ThePage />
  <TheFooter />
</template>

<script>
import TheNavbar from "@/components/TheNavbar.vue";
import ThePage from "@/components/ThePage.vue";
import TheFooter from "@/components/TheFooter.vue";

export default {
  name: 'App',
  components: {
    TheNavbar, ThePage, TheFooter
  },
  setup() {
    return {
      urlsData: ['#blog', '#press', '#join'],

    }
  }
}
</script>

<style>
</style>
