<template>
  <div class="home">
    <header>
      <Nav />
      <HeroSection />
    </header>
  </div>
</template>

<script>
import Nav from "@/components/Nav.vue";
import HeroSection from '@/components/HeroSection.vue'
import MainSection from '@/components/MainSection.vue'
import Card from '@/components/Card.vue'

export default {
  name: "HomeView",
  components: {
    Nav,
    HeroSection,
    MainSection,
    Card
  },
};
</script>
