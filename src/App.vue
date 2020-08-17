<template>
  <div id="app">
    <div id="nav">
      <navbar />
    </div>
    <router-view />
  </div>
</template>
<script>
import navbar from "@/components/NavBar.vue";
export default {
  components: {
    navbar
  }
};
</script>
<style src="./assets/css/style.css"></style>
