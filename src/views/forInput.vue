<template>
  <input v-model="text" placeholder="Type here" />
  <p>{{ text }}</p>
</template>

<script>
export default {
  data() {
    return {
      text: '',
    };
  },
};
</script>

<style></style>
