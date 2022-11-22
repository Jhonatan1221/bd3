<template>
  <div id="nav">
    <nav-bar />
    <navbar />
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
