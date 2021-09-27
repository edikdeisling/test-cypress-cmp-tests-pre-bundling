<template>
  <div data-test="app">{{ hello }}</div>
</template>

<script lang="ts" setup>
  import { computed } from 'vue';

  const hello = computed(() => 'Hello world')
</script>
