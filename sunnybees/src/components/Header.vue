<script setup lang="ts">
defineProps<{
  logo: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ logo }}</h1>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}
</style>
