<template>
  <div>
    <section class="my-padding-footer my-top-part-footer">
      <div class="row">
        <div class="col-4">
          <h1 class="text-white text-end">Newsletter to get in touch</h1>
        </div>
        <div class="col-8">
          <input class="my-input-email form-control" placeholder="Your e-mail" type="email">
        </div>
      </div>
    </section>


    <section class="my-padding-footer">
      <div class="row">
        <div class="col-4">
          <h5 class="mb-4">Address</h5>
          <p class="fw-lighter">382 NE 191st St # 87394 Miami, FL 33179-3899</p>
          <p class="fw-lighter">+1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)</p>
          <p class="fw-lighter">support@maxcoach.com</p>
        </div>
        <div class="col-2">
          <h5 class="mb-4">Explore</h5>
          <ul class="list-unstyled">
            <li v-for="(element, index) in exploreList" :key="index">{{ element.name }}</li>
          </ul>
        </div>
        <div class="col-2">
          <h5 class="mb-4">Information</h5>
          <ul class="list-unstyled">
            <li v-for="(element, index) in informationList" :key="index">{{ element.name }}</li>
          </ul>
        </div>
        <div class="col-4">
          <h5 class="mb-4">Instagram <span>@maxcoach</span></h5>
          <div class="my-intagram-pics-container d-flex">
            <img :src="require('../assets/images/artist-blog-03-480x356.jpeg')" alt="Instagram image 1">
            <img :src="require('../assets/images/artist-event-03-250x300.jpg')" alt="Instagram image 2">
            <img :src="require('../assets/images/artist-event-02-250x300.jpg')" alt="Instagram image 3">
          </div>
        </div>
        <div class="col-12 text-center mt-5">
          <p class="my-footer-rights">© 2020 Maxcoach. All Rights Reserved</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name : 'FooterComponent',

  data() {
    return {
      exploreList : [
        {
          name : 'Start here',
        },
        {
          name : 'Success story',
        },
        {
          name : 'Blog',
        },
        {
          name : 'Courses',
        },
        {
          name : 'Contact us',
        },
      ],
      informationList : [
        {
          name : 'Membership',
        },
        {
          name : 'Purchase guide',
        },
        {
          name : 'Privacy policy',
        },
        {
          name : 'Terms of services',
        },
      ]
    }
  },
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";

  .my-padding-footer{
    padding: 3.5rem 20%;
  }
  .my-top-part-footer {
    background-color: #244186;
    h1 {
      font-family: 'Times New Roman', Times, serif;
      font-size: 3.1rem;
    }
    .my-input-email{
      margin-top: 2.5rem;
      background-color: transparent;
      border: none;
      border-bottom: 2px solid #eaedf4;
      color: white;
      &::placeholder {
        color: white;
        font-size: 1.5rem;
        font-weight: 200;
      }
    }
  }

  .list-unstyled {
    li {
      font-weight: 200;
      margin-bottom: .8rem;
    }
  }
  h5 {
    span {
      color: #ef6f31;
      font-weight: 300;
      font-size: 1.05rem;
    }
  }
  .my-intagram-pics-container {
    img {
      width: calc((100% /3) - 20px);
      height: 10rem;
    }
  }
  .my-footer-rights {
    opacity: .5;
  }
</style>