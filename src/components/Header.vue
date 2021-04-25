<template>
  <header>
    <img src="../assets/logo.png" />
    <h1>Todo</h1>
  </header>
</template>

<script lang="ts">
import { ref, defineComponent } from "vue";
export default defineComponent({
  name: "Header",
});
</script>

<style scoped>
header {
  background-color: white;
  height: 60px;
  border-radius: 10px;
  box-shadow: 5px 8px 24px #ababab50;
  width: 100%;
  display: flex;
  align-items: center;
}

header img {
  width: 20px;
  height: 20px;
  margin-left: 20px;
}

header h1 {
  font-size: 20px;
  margin-left: 20px;
}
</style>
