<template>
  <nav>
    <h2 class="logo">{{ `${myFirstName} ${myLastName}` }}</h2>
    <button class="cta" @click.prevent>{{ cta }}</button>
  </nav>
</template>

<script>
export default {
    name: 'NavComp',
    data(){
        return {
            "myFirstName": "Sipho",
            "myLastName": "Nkebe",
            "cta": "Reach Me"
        }
    }
};
</script>

<style src="../assets/css/style.css">
</style>
