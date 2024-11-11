<script setup lang="ts">
import { appName } from '~/constants'

useHead({
  title: appName,
  bodyAttrs: {
    class: 'bg-stone-50 dark:bg-stone-950 text-blue-600 dark:text-blue-300',
  },
})
</script>

<template>
  <VitePwaManifest />
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<style>
#__nuxt {
  margin: 0;
  padding: 0;
}

html,
body {
  min-height: 100dvh;
}
</style>
