<script setup>
import { ref } from 'vue';
import GreetingMessage from '@/components/GreetingMessage.vue';
const greet = ref('Hello');
</script>
<template>
  <GreetingMessage>{{ greet }}</GreetingMessage>
  <input v-model="greet" />
</template>

<style></style>
