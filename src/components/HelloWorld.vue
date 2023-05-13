<script setup lang="ts">
defineProps<{ msg: string }>()
</script>

<template>
  <a-button type="primary">
    {{ msg }}
  </a-button>
</template>
