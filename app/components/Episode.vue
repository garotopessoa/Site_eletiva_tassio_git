<script langt="ts">
  export default {
    props: ['url']
  }
</script>
<template>
  <iframe data-testid="embed-iframe" 
    style="border-radius:12px; max-width: 100%; "
    :src="url"
    width="352"
    height="352"
    frameBorder="0"
    allowfullscreen="false"
    allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
    loading="lazy"
  ></iframe>
</template>