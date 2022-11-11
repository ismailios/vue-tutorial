<template>
  <ChildComp :message="greeting" />
</template>
<script setup>
import { ref } from "vue";
import ChildComp from "./ChildComp.vue";

const greeting = ref("Hello from parent");
</script>
