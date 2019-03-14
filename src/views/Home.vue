<template>
  <div>
    <b-row>
      <b-col class="px-0">
        <Jumbotron />
      </b-col>
    </b-row>
    <b-row>
      <b-col md="3" sm="6" class="border"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore,
        iure ad, exercitationem deserunt dolores facilis eos sed adipisci at
        sequi quis reiciendis laboriosam odit illo voluptatum aspernatur aliquam
        quisquam assumenda!</b-col
      >
      <b-col md="3" sm="6" class="border"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore,
        iure ad, exercitationem deserunt dolores facilis eos sed adipisci at
        sequi quis reiciendis laboriosam odit illo voluptatum aspernatur aliquam
        quisquam assumenda!</b-col
      >
      <b-col md="3" sm="6" class="border"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore,
        iure ad, exercitationem deserunt dolores facilis eos sed adipisci at
        sequi quis reiciendis laboriosam odit illo voluptatum aspernatur aliquam
        quisquam assumenda!</b-col
      >
      <b-col md="3" sm="6" class="border"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore,
        iure ad, exercitationem deserunt dolores facilis eos sed adipisci at
        sequi quis reiciendis laboriosam odit illo voluptatum aspernatur aliquam
        quisquam assumenda!</b-col
      >
    </b-row>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import Jumbotron from "@/components/Jumbotron.vue";

export default {
  name: "home",
  components: {
    Jumbotron
  }
};
</script>

<style scoped>
border {
  border: 1px solid gray;
}
</style>
