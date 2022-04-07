<template>
  <div>
    <section></section>


    <section>
      <nav class="d-flex justify-content-around p-4">
        <div>
          <img :src="require('../assets/images/dark-logo.png')" alt="MacCoach Logo">
        </div>
        <div>
          <ul class="d-flex gap-5 list-unstyled">
            <li v-for="(element, index) in navElements" :key="index">{{ element.name }}</li>
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
          font-weight: 200;
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