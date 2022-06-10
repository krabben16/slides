<script setup lang="ts">
const props = defineProps({
  id: {
    default: '',
  },
})
</script>

<template>
  <a :href="`https://github.com/${id}`" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</template>
