<script setup lang="ts">
import { ref, onMounted } from "vue";
import TheWelcome from '../components/TheWelcome.vue'
const welRef = ref(null);
onMounted(() => {
  console.log(welRef);
})
</script>

<template>
  <main>
    <TheWelcome ref="welRef" />
  </main>
</template>
