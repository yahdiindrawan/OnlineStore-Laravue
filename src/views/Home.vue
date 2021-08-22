<template>
  <div class="home">
    <Header />
    <Hero />
    <Products />
    <Insta />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue

import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import Products from "@/components/Products.vue";
import Insta from "@/components/Insta.vue";

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    Products,
    Insta,
  },
};
</script>
