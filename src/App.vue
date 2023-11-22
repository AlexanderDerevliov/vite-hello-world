<script>
import Title from "./components/title.vue";add
export default {
  components: {
    Title
  },
  data() {
    return {
      text: "ciao mondo"
    }
  }
}
</script>

<template>
<h1>{{ text }}</h1>
<Title />
</template>

<style scoped>
</style>
