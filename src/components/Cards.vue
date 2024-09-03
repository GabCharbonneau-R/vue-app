<template>
    <div class="card">
      <img :src="image" :alt="title" v-if="image">
      <h3>{{ title }}</h3>
      <p>{{ content }}</p>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      title: String,
      content: String,
      image: String
    }
  };
  </script>