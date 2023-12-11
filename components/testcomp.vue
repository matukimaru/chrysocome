<template>
  <div>
    Hello
  </div>
</template>

<script setup lang="ts">
import { ref } from "vue";

const count = ref(1);
console.log(count.value)
</script>

<style scoped></style>