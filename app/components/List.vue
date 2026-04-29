<script lang="ts">
  export default {
    props: ['items']
  }
</script>

<template>
  <div class="flex-column">
    <div v-for="item of items" class="flex items-center mb-3">
      <UIcon name="i-heroicons-star" class="w-3 h-3 mr-3" /> <div>{{ item }}</div>
    </div>
  </div>
</template>