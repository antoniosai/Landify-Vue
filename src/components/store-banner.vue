<template>
  <div class="store-banner-store-banner">
    <img :alt="image_alt1" :src="image_src1" class="store-banner-image" />
    <img :alt="image_alt" :src="image_src" class="store-banner-image1" />
  </div>
</template>

<script>
export default {
  name: 'StoreBanner',
  props: {
    image_src: {
      type: String,
      default: '/playground_assets/app-store-badge-1200h.png',
    },
    image_alt1: {
      type: String,
      default: 'image',
    },
    image_src1: {
      type: String,
      default: '/playground_assets/google-play-badge-1200h.png',
    },
    image_alt: {
      type: String,
      default: 'image',
    },
  },
}
</script>

<style scoped>
.store-banner-store-banner {
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.store-banner-image {
  width: 135px;
  object-fit: cover;
}
.store-banner-image1 {
  width: 135px;
  object-fit: cover;
  margin-left: var(--dl-space-space-halfunit);
}
</style>
