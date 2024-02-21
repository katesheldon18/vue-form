<script setup>
import Button from "./components/Button.vue";
import { ref } from 'vue';
const greeting = ref('Hello World!');
</script>

<template>
    <h1>HELLO WORLDasdasd</h1>
    <p class="greeting">{{ greeting }}</p>
    <Button></Button>
    <Button></Button>
    <Button></Button>
</template>

<style scoped>
.greeting {
  color: red;
  font-weight: bold;
}
</style>