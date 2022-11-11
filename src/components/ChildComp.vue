<template>
  <div>
    <h1>this is a child component</h1>
    <!-- Both work fine using props or directy the name of the props -->
    <h2>{{ props.message }}</h2>
  </div>
  <!--  a slot with a fallback content-->
  <slot>Fallback content</slot>
</template>

<script setup>
// eslint-disable-next-line no-undef
const props = defineProps({
  message: String,
});
// eslint-disable-next-line no-undef
const emit = defineEmits(["response"]);

emit("response", "hello from child Ex13");
</script>

<style lang="scss" scoped></style>
