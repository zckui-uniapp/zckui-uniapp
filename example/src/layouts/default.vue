<script lang="ts" setup>
// const { darkMode } = storeToRefs(useAppStore())

// const curPage = getCurrentPages().at(-1) as any

// #ifdef H5
// if (window.parent !== window.self) {
//   window.parent.postMessage({
//     type: 'route',
//     data: curPage.route.slice(0, -6),
//   }, '*')
// }
// #endif
</script>

<template>
  <div
    id="index"
    max="w-100dvmin"
    mx="auto"
    h="100dvh"
    overflow="auto"
    bg="#f6f7f9"
    p="1em"
  >

    <slot />
  </div>
</template>

<style lang="scss">

</style>
