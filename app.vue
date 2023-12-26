<script setup>
  const color = ref("white");
</script>

<template>
  <div class="container">
    <div>
      <div>
      <Nav />
      </div>
      <NuxtPage />
      <div>
        <strong><h2>Sono footer</h2></strong>
        <img src="/favicon.ico" alt="" />
      </div>
    </div>
  </div> 
</template>

<style scoped>
@import url(./assets/css/main.css);
h2 {
  color: v-bind(color);
}

</style>