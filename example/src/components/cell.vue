<script lang="ts" setup>
defineProps<{
  title: string
  description?: string
  url?: string
}>()
</script>

<template>
  <navigator
    :url="url"
    open-type="navigate"
    hover-class="navigator-hover"
    bg="white"
    rounded="1"
    p="4"
  >
    <view
      grid="~ cols-[1fr_max-content] rows-[max-content_max-content] flow-col"
      items="center"
      gap=".5em"
    >
      <text font="bold" text="1.25em">{{ title }}</text>
      <text>{{ description }}</text>

      <text grid="row-span-full">
        👉
      </text>
    </view>

  </navigator>
</template>

<style lang="scss"></style>
