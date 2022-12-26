<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <div><p>teste</p></div> -->
    <HeaderPage />
    <div><p>teste</p></div>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderPage from "@/components/HeaderPage.vue";

export default {
  name: "HomeView",
  components: {
    HeaderPage,
  },
};
</script>
