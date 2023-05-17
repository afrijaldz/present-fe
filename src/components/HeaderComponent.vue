<script setup lang="ts">
import { ref } from 'vue'

const oke = ref('')
</script>

<template>
  <header class="bg-blue-500 w-full h-full py-4">
    <nav class="container m-auto">
      <RouterLink class="text-green-100" to="/">Home</RouterLink>
      <RouterLink to="/submit">Submit</RouterLink>
    </nav>
  </header>
</template>
