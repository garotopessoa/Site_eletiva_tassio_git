<script lang="ts">
  export default {
    props: ['title', 'items']
  }
</script>

<template>
  <UCard variant="soft" class="hover:shadow-lg hover:cursor-pointer hover:bg-primary/20  transition-shadow transition-colors p-2 ">
    <template #header class="border-none! outline-none!">
      {{ title }}
    </template>

    <List :items="items" />
  </UCard>
</template>
