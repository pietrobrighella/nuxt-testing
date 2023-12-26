<template>
    <UButton size="xl" to="/about" target="_self" block>About</UButton>
    <NuxtLink to="/about">About with NuxtLink</NuxtLink>
    <div>
        <br/>
        <UButton size="sm" target="_self" to="/photo">Guarda le foto</UButton>
        <br/>
    </div>
</template>

<script setup>
    definePageMeta({
        colorMode: ''
    })

    useHead({
      title: 'My app Pietro',
      htmlAttrs: {lang: 'it'},
    })
</script>

<style scoped>
</style>