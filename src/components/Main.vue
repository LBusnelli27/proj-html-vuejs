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
        <h1 class="my-blue-write">Hello, I'm Martin</h1>
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

    <section class="p-5">
      <div class="row">
        <div class="col-12 text-center mb-5">
          <h2 class="my-blue-write">Artist coaching</h2>
          <h2>I understand what it takes to create</h2>
          <h2>I can help you with</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-2 offset-2">
          <img class="mb-3" :src="require('../assets/images/artist-box-image-01.png')" alt="Online Courses image">
          <h4 class="fw-light">Online Courses</h4>
          <p class="my-fw-light">Online art coaching now offers you a very powerful way to redesign your artist mind</p>
        </div>
        <div class="col-2">
          <img class="mb-3" :src="require('../assets/images/artist-box-image-02.png')" alt="One to One image">
          <h4 class="fw-light">One to One</h4>
          <p class="my-fw-light">Getting the necessary clarity about the current state to help you improve your ability</p>
        </div>
        <div class="col-2">
          <img class="mb-3" :src="require('../assets/images/artist-box-image-03.png')" alt="Anywhere image">
          <h4 class="fw-light">Anywhere</h4>
          <p class="my-fw-light">Access to valuable and portable program which alow you to setup and live anywhere you want</p>
        </div>
        <div class="col-2">
          <img class="mb-3" :src="require('../assets/images/artist-box-image-04.png')" alt="On Time image">
          <h4 class="fw-light">On Time</h4>
          <p class="my-fw-light">Online art coaching now offers you a very powerful way to redesign your artist mind</p>
        </div>
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
    height: 70vh;
    background-color: #fbf9f6;
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