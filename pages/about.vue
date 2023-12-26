<template>
  <div>
    <h1>Sono about</h1>
    <u><a href="/">Return to home</a></u>
  </div>
</template>

<script setup>
  const route = useRoute();

  console.log(route.name);
</script>

<style>

</style>