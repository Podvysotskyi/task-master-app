<template>
  <div>
    <h1>
      Welcome to the Admin Page
    </h1>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'admin',
  middleware: ['sanctum:auth'],
})

useHead({
  title: 'Task Master - Admin',
})
</script>
