<template>
  <li class="nav-item">
    <router-link class="nav-link custom-link" :to="{ name: item.link }">{{
      item.name
    }}</router-link>
  </li>
</template>

<script>
export default {
  props: {
    item: {
      type: Object,
      required: true
    }
  }
};
</script>

<style scoped>
.custom-link:hover {
  background-color: blue;
  color: red;
}
</style>
