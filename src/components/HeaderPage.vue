<template>
  <header :style="{ 'background-image': 'url(' + headerImage + ')' }">
    <div class="logo">
      <router-link to="/">My Business</router-link>
    </div>
    <nav>
      <ul>
        <li><router-link to="/products">Products</router-link></li>
        <li><router-link to="/about">About</router-link></li>
        <li><router-link to="/contact">Contact</router-link></li>
      </ul>
    </nav>
  </header>
</template>

<script>
import headerImage from "@/assets/metallurgy-2932946_960_720.jpg";

export default {
  name: "HeaderPage",
  data() {
    return {
      headerImage,
    };
  },
};
</script>

<style>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  height: 100%;
  background-position: center;
  background-size: cover;
}
.logo {
  font-size: 1.5em;
}
nav ul {
  display: flex;
}
nav li {
  list-style: none;
  margin-left: 20px;
}
</style>
