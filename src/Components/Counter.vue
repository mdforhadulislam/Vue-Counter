<template>
  <h1>Count {{ count }}</h1>
  <button @click="count++">+</button>
  <button @click="count--">-</button>
</template>

<script>
export default {
  name: "CounterApp",
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<style>
body {
  font-family: sans-serif;
}
</style>
