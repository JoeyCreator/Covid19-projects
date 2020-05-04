<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/profile">Profile</router-link>
    <router-link to="/covid19">Covid19</router-link>
    <router-link to="/livestream">LiveStream</router-link>
  </nav>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style scoped>
nav a {
  font-weight: 700;
  margin: 10px 20px;
}
</style>
