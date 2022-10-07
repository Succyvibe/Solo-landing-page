<template>
  <div class="home">
    <Header />
    <Products />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "../components/Header.vue";

export default {
  name: "HomeView",
  components: {
    Header,
  },
};
</script>

<style scoped></style>
