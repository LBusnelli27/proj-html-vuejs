<template>
  <div>
    <section class="d-flex justify-content-between">
      <div class="position-relative">
        <img class="my-beige-shape-1 position-absolute" :src="require('../assets/images/artist-shape-02.png')" alt="">
        <img class="my-hero-image-1 position-absolute" :src="require('../assets/images/artist-hero-image-01.jpg')" alt="">
        <img class="my-orange-person-hero position-absolute" :src="require('../assets/images/artist-hero-image-03.png')" alt="">
        <img class="my-hero-image-1 position-absolute" :src="require('../assets/images/artist-hero-image-01.jpg')" alt="">
        <img class="my-hero-image-2 position-absolute" :src="require('../assets/images/artist-hero-image-02.jpg')" alt="">
      </div>
      <div></div>
    </section>
  </div>
</template>

<script>
export default {
  name : 'MainComponent'
}
</script>

<style>
  .my-beige-shape-1 {
    width: 75rem;
  }
  .my-blu-points-hero {
    top: 10rem;
    left: 3rem;
    width: 30rem;
  }
  .my-orange-person-hero {
    top: 30rem;
    left: 43rem;
    width: 17rem;
  }
  .my-hero-image-1 {
    z-index: 2;
    left: 13rem;
    top: 35rem;
    width: 18rem;
  }
  .my-hero-image-2 {
    z-index: 1;
    left: 30rem;
    top: 8rem;
    width: 23rem;
  }
</style>