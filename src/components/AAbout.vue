<script lang="ts" setup>
defineProps<{
  text: string
}>()
</script>

<template>
  <div>This is a compiled component. With prop text: {{ text }}</div>
</template>
