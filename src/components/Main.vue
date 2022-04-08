<template>
  <div>
    <section class="my-hero d-flex justify-content-between position-relative">
      <div class="position-relative">
        <img class="my-beige-shape-1 position-absolute" :src="require('../assets/images/artist-shape-02.png')" alt="">
        <img class="my-blu-points-hero position-absolute" :src="require('../assets/images/artist-shape-03.png')" alt="">
        <img class="my-orange-person-hero position-absolute" :src="require('../assets/images/artist-hero-image-03.png')" alt="">
        <img class="my-hero-image-1 position-absolute" :src="require('../assets/images/artist-hero-image-01.jpg')" alt="">
        <img class="my-hero-image-2 position-absolute" :src="require('../assets/images/artist-hero-image-02.jpg')" alt="">
      </div>
      <div class="my-center-a-div text-center">
        <h1 class="my-hello-martin">Hello, I'm Martin</h1>
        <h1>Artist Coaching And Mentoring</h1>
        <h1 class="mb-5">Might Be for You</h1>
        <button class="my-btn-orange btn">Get started today</button>
      </div>
      <div class="position-relative">
        <img class="my-beige-shape-2 position-absolute" :src="require('../assets/images/artist-shape-01.png')" alt="">
        <img class="my-feader-shape-1 position-absolute" :src="require('../assets/images/artist-shape-04.png')" alt="">
        <img class="my-color-shape-1 position-absolute" :src="require('../assets/images/artist-shape-05.png')" alt="">
        <img class="my-circle-points-1 position-absolute" :src="require('../assets/images/maxcoach-shape-12.png')" alt="">
        <img class="my-hero-image-4 position-absolute" :src="require('../assets/images/artist-hero-image-04.jpg')" alt="">
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name : 'MainComponent'
}
</script>

<style lang="scss">
@import "../assets/scss/style.scss";

  .my-hero {
    height: 60vh;
  }
  .my-beige-shape-1 {
    width: 57rem;
  }
  .my-blu-points-hero {
    top: 10rem;
    left: 1rem;
    width: 23rem;
  }
  .my-orange-person-hero {
    top: 26rem;
    left: 32rem;
    width: 13rem;
  }
  .my-hero-image-1 {
    z-index: 2;
    left: 7rem;
    top: 27rem;
    width: 15rem;
  }
  .my-hero-image-2 {
    z-index: 1;
    left: 20rem;
    top: 5rem;
    width: 20rem;
  }
  .my-center-a-div {
    .my-hello-martin{
      font-family: 'Nothing You Could Do', cursive;
      color: #029fcc;
    }
  }

  div {
    .my-beige-shape-2 {
      top: 0;
      right: 9rem;
      width: 50rem;
    }
    .my-feader-shape-1 {
      top: 5rem;
      right: 9rem;
    }
    .my-color-shape-1 {
      top: 35rem;
      right: 6rem;
      width: 25rem;
    }
    .my-circle-points-1 {
      top: 39rem;
      right: 27rem;
    }
    .my-hero-image-4 {
      top: 20rem;
      right: 20rem;
      width: 23rem;
    }
  }
</style>