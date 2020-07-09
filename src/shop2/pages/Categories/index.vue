<template>
  <div>
   <!-- <nuxt-link v-for="todo in todos" :key="todo.category_id" to="">{{todo.link}}</nuxt-link>
    <nuxt-link to="/about">{{link}}</nuxt-link> -->
   <nuxt-link class="nuxtLink" v-for="todo in todos" :key="todo.category_id"  v-bind:to="todo.link">Nuxt-Link example</nuxt-link>
      <a class="nuxtLink" v-for="todo in todos" :key="todo.category_id"  v-bind:href="todo.link">Anchor link example</a>

  </div>
</template>

<script>
// const axios = require("axios");

import axios from "axios";

// import ListItem from "../../components/ListItem";

export default {
  data() {
    return {
      todos: []
    };
  },
  async fetch() {
    const { data } = await axios.get(
      `https://my-json-server.typicode.com/mareestephan/jsonProducts/pages_to_create`
    );
    // `todos` has to be declared in data()
    // const appels = data.map;
    this.todos = data;
    // console.log(this.todos);
  },

  head() {
    return {
      title: "Test Nuxt SSR",
      meta: [
        {
          hid: "descriptionHID",
          name: "nameNAME",
          content: "content in die meta array"
        }
      ]
    };
  }
};
</script>

<style>
.nuxtLink {
  display: block;
  text-decoration: underline;
  color: #bd7c91;
}
</style>
