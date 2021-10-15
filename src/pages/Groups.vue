<template>
  <p>1</p>
  <p>{{ count }}</p>
</template>

<script setup lang="ts">
import { ref } from 'vue';
const count = ref(4);
</script>
