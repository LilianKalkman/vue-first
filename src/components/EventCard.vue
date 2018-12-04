<template>
  <div>
    <h1>{{ quote }}</h1>
    <p>This is the Test Component created</p>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  props: {
    message: String
  },
  data() {
    return {
      quote: "hello"
    };
  }
};
</script>

<style scoped>
p {
  color: pink;
}
h1 {
  color: blue;
}
</style>
