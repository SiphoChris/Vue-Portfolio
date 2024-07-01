<template>
  <main>
    <Card v-for="(card, index) in cards" :key="index">{{ card }}</Card>
  </main>
</template>

<script>
import Card from "@/components/Card.vue";
export default {
  components: {
    Card,
  },
  data() {
    return {
      cards: ["About", "Education", "Skills", "Tools", "Resume"],
    };
  },
};
</script>

<style src="../assets/css/style.css"></style>
