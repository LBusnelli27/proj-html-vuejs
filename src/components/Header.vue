<template>
  <div>
    <section class="my-top-nav d-flex gap-4 align-items-center justify-content-center p-2">
        <p class="my-fw-light m-0">Starts <span class="text-uppercase">tomorrow</span>! Our biggest event of the year...</p>
        <div class="my-clock-header d-flex gap-2 align-items-center">
          <img :src="require('../assets/images/clock-icon.png')" alt="">
          <p class="m-0">00 : 00 : 00</p>
        </div>
        
        <button class="my-btn-orange btn">Get ticket</button>
    </section>

    <section>
      <nav class="d-flex justify-content-around p-4">
        <div>
          <img :src="require('../assets/images/dark-logo.png')" alt="MacCoach Logo">
        </div>
        <div>
          <ul class="d-flex gap-5 list-unstyled">
            <li v-for="(element, index) in navElements" :key="index">{{ element.name }} <i class="fa-solid fa-angle-down"></i></li>
          </ul>
        </div>
        <div class="my-social-container d-flex">
          <img :src="require('../assets/images/twitter-logo.png')" alt="Twitter Nav Logo">
          <img :src="require('../assets/images/black-facebook-logo.png')" alt="Facebook Nav Logo">
          <img :src="require('../assets/images/instagram-logo.png')" alt="Instagram Nav Logo">
          <img :src="require('../assets/images/linkedin-logo.png')" alt="Twitter Nav Logo">
        </div>
      </nav>
    </section>
  </div>
</template>

<script>
export default {
  name : 'HeaderComponent',

  data() {
    return {
      navElements : [
        {
          name : 'Home',
          link : '#'
        },
        {
          name : 'Pages',
          link : '#'
        },
        {
          name : 'Courses',
          link : '#'
        },
        {
          name : 'Features',
          link : '#'
        },
        {
          name : 'Blog',
          link : '#'
        },
        {
          name : 'Shop',
          link : '#'
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";

  .my-top-nav{
    background-color: #f5f5f5;
    p {
      opacity: .7;
    }
    .my-clock-header {
      color:#22437d;
      img{
        height: 20px;
        width: 20px;
      }
      p{
        opacity: 1;
        font-weight: 500;
      }
    }
  }

  nav {
    div{
      img {
        width: 150px;
      }
    }
    div {
      ul {
        li {
          font-size: 1.2rem;
          font-weight: 300;
        }
      }
    }
    .my-social-container {
      gap: 1rem;
      img {
        height: 28px;
        width: 28px;
        opacity: .5;
      }
    }
  }
</style>