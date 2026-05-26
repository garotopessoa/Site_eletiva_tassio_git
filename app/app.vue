<script setup lang="ts">
  import type { NavigationMenuItem } from '@nuxt/ui';

  const route = useRoute();

  const items = computed<NavigationMenuItem[]>(() => [
    {
      label: 'Projeto',
      to: '#presentation',
      active: route.path.startsWith('#presentation')
    },
    {
      label: 'Quem somos',
      to: '#team',
      active: route.path.startsWith('#team')
    },
    {
      label: 'Podcast',
      to: '#podcast',
      active: route.path.startsWith('#podcast')
    }
  ]);

</script>

<template>
  <UApp>
    <UHeader class="bg-primary text-neutral border-none" mode="drawer">
      <template #left>
        <span class="font-important">LIS</span>
      </template>

      <template #right>
        <UNavigationMenu :items="items" class="text-neutral justify-between hidden md:block" />
      </template>

      <template #body class="bg-white!">
        <UNavigationMenu :items="items" class="text-neutral justify-between bg-white" orientation="vertical" />
      </template>
    </UHeader>

    <UMain>
      <NuxtPage />
    </UMain>
  </Uapp>


</template>