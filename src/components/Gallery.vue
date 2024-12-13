<script setup>
const galleryItems = [
  { img: '../assets/image/juuzou.jpg', text: 'A delicadeza das cerejeiras', reverse: false },
  { img: '../assets/image/juuzou.jpg', text: 'Lycoris radiata: a flor mágica', reverse: true },
  { img: '../assets/image/juuzou.jpg', text: 'A harmonia das flores de lótus', reverse: false },
];
</script>

<template>
  <section class="gallery">
    <div v-for="(item, index) in galleryItems" :key="index" :class="['gallery-item', { reverse: item.reverse }]">
      <img :src="item.img" :alt="item.text" class="gallery-image" />
      <p class="gallery-text">{{ item.text }}</p>
    </div>
  </section>
</template>

<style scoped>
.gallery {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.gallery-item {
  display: flex;
  align-items: center;
  gap: 1rem;
}

.gallery-item.reverse {
  flex-direction: row-reverse;
}

.gallery-image {
  width: 50%;
  border-radius: 8px;
}

.gallery-text {
  font-size: 1.25rem;
  color: #333;
  flex: 1;
}
</style>
