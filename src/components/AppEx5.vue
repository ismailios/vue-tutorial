<template>
  <div>
    <input v-model="text" placeholder="Type here" />
    <p>{{ text }}</p>
  </div>
</template>

<script setup>
import { ref } from "vue";

const text = ref("");
</script>
