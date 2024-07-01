<template>
  <div class="custom-card">
    <div class="cardImage">
      <slot name="cardImage">
        <img class="card-image"
          src="https://siphochris.github.io/images/images/portfolio_images/profile.jpg"
        />
      </slot>
    </div>
    <div class="cardBody">
      <div class="cardText">
        <slot name="cardText">
          <h4>About</h4>
        </slot>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'CardComp'
};
</script>

<style src="../assets/css/style.css"></style>
