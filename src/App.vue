<script setup>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import Main from "@/components/Main.vue";

</script>

<template>
  <div id="app-card">
    <Header/>
    <Main/>
    <Footer/>
  </div>

</template>

<style scoped>

#app-card{
  margin: 3rem;
  padding: 2rem;
  border-radius: 1rem;
  box-shadow: 0 3px 3px 0 rgba(0, 0, 0, 0.2);
  display: grid;
  gap: 1rem;
  background-color: #cacaca55;
}

@media (min-width: 1024px) {
}
</style>
