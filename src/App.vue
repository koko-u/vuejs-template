<template>
  <div class="app">
    <section class="hero is-light">
      <div class="hero-body">
        <h1 class="title">{{ message }}</h1>
        <h2 class="subtitle">powered by Vue.js + parcel + sass</h2>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      message: "This is Vue.js 2 project Template."
    };
  },
  components: {}
};
</script>

<style>
</style>
