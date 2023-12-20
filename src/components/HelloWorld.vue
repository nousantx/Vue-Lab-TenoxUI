<script setup>
import { ref } from "vue";
import TenoxUI from "../TenoxUI";

defineProps({
  msg: String,
});
console.log(TenoxUI);
</script>

<script>
export default {
  mounted() {
    TenoxUI();
  },
};
</script>

<template>
  <h1 class="fs-1rem">{{ msg }}</h1>
</template>
