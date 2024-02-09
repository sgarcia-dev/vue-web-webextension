<script setup lang="ts">
import SharedComponent from '@shared/components/SharedComponent.vue'
</script>

<template>
  <main
    font-sans
    p="x-4 y-10"
    text="center gray-700 dark:gray-200"
  >
    <RouterView />
    <!-- <TheFooter /> -->
    <SharedComponent />
  </main>
</template>
