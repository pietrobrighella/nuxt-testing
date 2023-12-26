<script setup>
  const links = [{
    label: 'Home',
    icon: 'i-heroicons-home',
    to: '/'
  }, {
    label: 'About',
    icon: 'i-heroicons-square-3-stack-3d',
    to: '/about'
  }, {
    label: 'Breadcrumb',
    icon: 'i-heroicons-link'
  }]
</script>

<template>
  <UBreadcrumb :links="links" />
</template>

