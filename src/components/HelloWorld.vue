<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const name = ref('Tim')
</script>

<template>
  <h1 class="font-bold">{{ msg }} {{ name }}</h1>  
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
