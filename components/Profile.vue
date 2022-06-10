<script setup lang="ts">
const {
  VITE_COMPANY_NAME,
  VITE_SECTION_NAME,
  VITE_PERSONAL_NAME,
} = import.meta.env
</script>

<template>
  <div>
    {{ VITE_COMPANY_NAME }} {{ VITE_SECTION_NAME }} {{ VITE_PERSONAL_NAME }}
  </div>
</template>
