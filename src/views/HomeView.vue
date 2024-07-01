<template>
  <div class="home">
    <header>
      <Nav />
      <HeroSection />
    </header>
    <Footer />
  </div>
</template>

<script>
import Nav from "@/components/Nav.vue";
import HeroSection from '@/components/HeroSection.vue'
// import Card from '@/components/Card.vue'
import Footer from "@/components/Footer.vue";


export default {
  name: "HomeView",
  components: {
    Nav,
    HeroSection,
    // MainSection,
    // Card,
    Footer
  },
};
</script>
