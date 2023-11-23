<script>
import Title from "./components/title.vue";
export default {
  components: {
    Title
  },
  data() {
    return {
      text: "Hello World"
    }
  }
}
</script>

<template>
  <h1>{{ text }}</h1>
  <Title />
</template>

<style scoped>
h2 {
  color: red;
}
h1 {
  color: green;
}
h1:hover {
  color: blue;
}
</style>
