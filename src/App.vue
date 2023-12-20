<script setup>
import TenoxUI from "./components/TenoxUI.vue";
</script>

<template>
  <TenoxUI what-tenox="Tenox" />
</template>

<style scoped>
:root {
  --primary: #d2e603;
  --vue: #42b883;
  font-family: inter, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>
