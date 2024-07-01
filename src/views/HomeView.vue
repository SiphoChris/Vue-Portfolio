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

export default {
  name: "HomeView",
  components: {
    Nav,
    HeroSection
  },
};
</script>
