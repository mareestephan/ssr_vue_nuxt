<template>
    <li> {{link }}</li>
</template>

<script>
export default {
  name: "list-item",
  props: {
    link: {
      type: String,
      default: "Fallback"
    }
  }
};
</script>

<style>
</style>
