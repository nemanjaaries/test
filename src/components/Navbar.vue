<template>
  <div>
    <b-container class="px-0">
      <b-navbar toggleable="lg" type="dark" variant="info" class="nav-bar">
        <router-link class="navbar-brand" :to="{ name: 'home' }"
          >Brand</router-link
        >

        <b-navbar-toggle target="nav_collapse" />

        <b-collapse is-nav id="nav_collapse">
          <b-navbar-nav>
            <NavbarItem
              v-for="(itemLink, index) in itemLinks"
              :key="index"
              :item="itemLink"
            ></NavbarItem>
          </b-navbar-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto"> </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </b-container>
  </div>
</template>

<script>
import NavbarItem from "@/components/NavbarItem.vue";
export default {
  name: "Navbar",
  data() {
    return {
      itemLinks: [
        { name: "Home", link: "home" },
        { name: "Contact", link: "contact" },
        { name: "AboutUs", link: "about" }
      ]
    };
  },
  components: {
    NavbarItem
  }
};
</script>

<style scoped>
.nav-bar {
  padding: 0 15px;
}
</style>
