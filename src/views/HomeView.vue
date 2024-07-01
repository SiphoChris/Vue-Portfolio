<template>
  <div class="home">
    <header>
      <Nav />
      <HeroSection />
    </header>
    <MainSection />
    <Footer />
  </div>
</template>

<script>
import Nav from "@/components/Nav.vue";
import HeroSection from "@/components/HeroSection.vue";
import MainSection from '@/components/MainSection.vue'
import Footer from "@/components/Footer.vue";

export default {
  name: "HomeView",
  components: {
    Nav,
    HeroSection,
    MainSection,
    Footer,
  },
};
</script>
