<template>
  <h1 :class="titleClass">Make me red</h1>
  <!-- add dynamic class binding here -->
</template>

<script setup>
import { ref } from "vue";
const titleClass = ref("title");
</script>

<style scoped>
.title {
  color: blue;
}
</style>
