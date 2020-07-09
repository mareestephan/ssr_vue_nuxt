<template>
    <div class="joke">
      <h3> Nuxt-link Example </h3>
   <nuxt-link v-bind:to="link">{{link}}</nuxt-link>


         <h3> HTML Anchor Example </h3>
    <a v-bind:href="link">{{link}}</a>


    </div>
</template>

<script>
export default {
  name: "Joke",
  props: ["slug", "category_id", "link"]
};
</script>

<style>
.joke {
  padding: 1rem;
  border: 1px dotted #ccc;
  margin: 1rem 0;
}
</style>
