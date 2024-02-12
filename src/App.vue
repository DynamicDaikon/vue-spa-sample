<template>
  <h1 :class="titleClass">Make me dynamic</h1>
  <div>{{ message.split(' ').reverse().join(' ') }}</div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello world',
      titleClass: 'title',
    };
  },
};
</script>

<style>
.title {
  color: red;
}
</style>
