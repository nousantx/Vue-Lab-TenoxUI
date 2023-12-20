<script setup>
import TenoxUI, { Color } from "../TenoxUI";

defineProps({
  whatTenox: String,
});
</script>

<script>
export default {
  mounted() {
    Color();
    TenoxUI();
  },
};
</script>

<template>
  <div
    class="display-flex flex-parent-center gap-1rem bg-0d0d0d p-1rem tc-white"
  >
    <h1 class="fs-1rem">{{ whatTenox }}<span class="tc-[primary]">UI</span></h1>
    <h1 class="fs-1rem">x</h1>
    <h1 class="fs-1rem tc-[vue]">Vue</h1>
  </div>
</template>

<style>
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
