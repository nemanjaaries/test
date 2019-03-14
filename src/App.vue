<template>
  <div id="app">
    <Navbar />
    <b-container class="bg-light">
      <router-view />
    </b-container>
  </div>
</template>
<script>
import Navbar from "@/components/Navbar.vue";
export default {
  components: {
    Navbar
  }
};
</script>
<style></style>
