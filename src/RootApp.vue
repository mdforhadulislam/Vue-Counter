<template>
  <Counter />
  <Counter />
</template>
<script>
import Counter from "./Components/Counter.vue";
export default {
  name: "RootApp",
  components: {
    Counter,
  },
};
</script>

<style>
body {
  font-family: sans-serif;
}
</style>
