<template>
  <button @click="increment">count is: {{ count }}</button>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    increment() {
      // コンポーネントの状態を更新する
      this.count++;
    },
  },
};
</script>

<style></style>
