<template>
  <div class="red-b">テストです<br />{{ testData }}</div>
</template>

<script>
export default {
  name: "TestComponent",
  data() {
    return {
      testData: "テストデータです",
    };
  },
};
</script>

<style scoped>
.red-b {
  border: 1px solid red;
}
</style>