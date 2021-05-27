<template>
  <div class="about">
    <Karte Wert="7" Farbe="Karo" />
  </div>
</template>

<script>
  import Karte from "@/components/Karte.vue"
  export default {
    name: "About",
    components: {
      Karte,
    }
  }
</script>

<style scoped>
  .about {
    position: relative;
    height: 200px;
    width: 100px;
    margin: auto;
  }
</style>