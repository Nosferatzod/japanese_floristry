<script setup>
const bannerText = "Explore a beleza das flores japonesas, como a encantadora Lycoris radiata.";
</script>

<template>
  <section class="banner">
    <img src="../assets/image/juuzou_banner.jpg" alt="Flores Lycoris radiata" class="banner-image" />
    <div class="banner-text">
      <h2>{{ bannerText }}</h2>
    </div>
  </section>
</template>

<style scoped>
.banner {
  position: relative;
  text-align: center;
  margin-bottom: 2rem;
}

.banner-image {
  width: 100%;
  height: auto;
  border-radius: 8px;
}

.banner-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: rgba(0, 0, 0, 0.5);
  color: #fff;
  padding: 1rem 2rem;
  border-radius: 8px;
  font-size: 1.5rem;
}
</style>
