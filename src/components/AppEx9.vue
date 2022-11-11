<script setup>
import { onMounted, ref } from "vue";

const p = ref(null);

onMounted(() => {
  p.value.textContent = "Hello SQLI";
  p.value.style.backgroundColor = "red";
  p.value.style.color = "white";
});
</script>

<template>
  <p ref="p">hello</p>
</template>
