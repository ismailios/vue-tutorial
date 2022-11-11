<template>
  <h1>{{ counter.count }}</h1>
</template>

<script setup>
import { reactive } from "vue";

const counter = reactive({
  count: 0,
});
</script>

<style lang="scss" scoped></style>
