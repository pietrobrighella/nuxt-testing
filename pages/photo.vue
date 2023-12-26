<template>
  <div v-if="pending" class=" text-white flex flex-wrap">
    Loading...
  </div>
  <div v-else class="flex flex-wrap">
    <UCard v-for="photo in photos">
      <a :href=photo.url><img :src=photo.download_url :alt=photo.author class=" w-96"></a>
    </UCard>
  </div>
</template>

<script setup>
  const { pending, data: photos } = useFetch('https://picsum.photos/v2/list?page=2&limit=10', {
    lazy: true
  })
</script>

<style>

</style>