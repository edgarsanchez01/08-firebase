<template>
  <div id="nav">
    <nav-bar />

    <navbar />
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>

    <router-view />
  </div>

</template>

<script>
import Navbar from './components/NavBar.vue';
export default {
  components: {
    Navbar,
  },
};
</script>
