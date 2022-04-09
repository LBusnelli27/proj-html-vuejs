<template>
  <div>
    <section class="my-hero my-bg-beige d-flex justify-content-between position-relative">
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


    <section class="my-padding-website">
      <div class="row">
        <div class="col-12 text-center mb-5">
          <h2 class="my-blue-write">Artist coaching</h2>
          <h2>I understand what it takes to create</h2>
          <h2>I can help you with</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-3">
          <img class="mb-3" :src="require('../assets/images/artist-box-image-01.png')" alt="Online Courses image">
          <h4 class="fw-light">Online Courses</h4>
          <p class="my-fw-light">Online art coaching now offers you a very powerful way to redesign your artist mind</p>
        </div>
        <div class="col-3">
          <img class="mb-3" :src="require('../assets/images/artist-box-image-02.png')" alt="One to One image">
          <h4 class="fw-light">One to One</h4>
          <p class="my-fw-light">Getting the necessary clarity about the current state to help you improve your ability</p>
        </div>
        <div class="col-3">
          <img class="mb-3" :src="require('../assets/images/artist-box-image-03.png')" alt="Anywhere image">
          <h4 class="fw-light">Anywhere</h4>
          <p class="my-fw-light">Access to valuable and portable program which alow you to setup and live anywhere you want</p>
        </div>
        <div class="col-3">
          <img class="mb-3" :src="require('../assets/images/artist-box-image-04.png')" alt="On Time image">
          <h4 class="fw-light">On Time</h4>
          <p class="my-fw-light">Online art coaching now offers you a very powerful way to redesign your artist mind</p>
        </div>

        <div class="col-6 text-center p-5">
          <img src="https://maxcoach.thememove.com/main/wp-content/uploads/sites/1/2020/05/artist-quote-icon.png" alt="">
          <h1 class="my-big-text">I coach and mentor visual artists, like you, to Create Like You Mean It</h1>
          <h2 class="my-blue-write">Martin Garrix</h2>
        </div>
        <div class="col-6 p-5">
          <p class="my-fw-light mt-5">
            As a coach and mentor, my ultimate goal is to motivate visual artists toward inspired action. I help you get you back on track to being the productive, creative, meaningful and authentic artist you truly want to be.I support artists in crafting and living a creative life as well as feeling good about themselves and their art.
          </p>
          <p class="my-fw-light my-4">
            As an artist and an educator for nearly 30 years, I understand what it takes to create.
          </p>
          <button class="my-btn-light-orange btn">Get started today</button>
        </div>

        <div class="col-12 py-5 text-center position-relative">
          <img class="my-video-poster" :src="require('../assets/images/artist-video-poster.jpg')" alt="Video poster image">
          <img class="my-center-a-div" :src="require('../assets/images/icon-youtube-play.png')" alt="Youtube icon">
        </div>
      </div>
    </section>


    <section class="my-bg-beige py-5">
      <div class="row justify-content-around">
        <div class="col-12 text-center">
          <h2 class="my-blue-write">Testimonials</h2>
          <h1 class="mb-5">Why do people love me?</h1>
        </div>

        <div class="my-testimonial-card col-3">
          <h4>It's a choice of quality for people with special needs</h4>
          <p class="my-fw-light">I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.</p>
          <div class="d-flex align-items-center">
            <div class="me-3">
              <img :src="require('../assets/images/artist-testimonial-avatar-02.jpg')" alt="Florence Themes profile img">
            </div>
            <div>
              <h5 class="my-name-avatar">Florence Themes</h5>
              <p class="fw-light opacity-50">/ Multimedia Admin</p>
            </div>
          </div>
        </div>
        <div class="my-testimonial-card col-3">
          <h4>High level of efficiency and scientific teaching methods</h4>
          <p class="my-fw-light">I am free to learn at my own pace, follow my own schedule and choose the subject I want to learn from the syllabus. Great study portal for people like me.</p>
          <div class="d-flex align-items-center">
            <div class="me-3">
              <img :src="require('../assets/images/artist-testimonial-avatar-04.jpg')" alt="Florence Themes profile img">
            </div>
            <div>
              <h5 class="my-name-avatar">Mina Hollace</h5>
              <p class="fw-light opacity-50">/ Freelancer</p>
            </div>
          </div>
        </div>
        <div class="my-testimonial-card col-3">
          <h4>Professional team of specialists and passionate mentors at reach </h4>
          <p class="my-fw-light">I need to get a certification for English proficiency and MaxCoach is my best choice. Their tutors are smart and professional when dealing with students.</p>
          <div class="d-flex align-items-center">
            <div class="me-3">
              <img :src="require('../assets/images/artist-testimonial-avatar-01.jpg')" alt="Florence Themes profile img">
            </div>
            <div>
              <h5 class="my-name-avatar">Madley Pondor</h5>
              <p class="fw-light opacity-50">/ IT Specialist</p>
            </div>
          </div>
        </div>
      </div>
    </section>


    <section class="my-padding-website">
      <div class="row">
        <div class="col-12 text-center">
          <h2 class="my-blue-write">Artist coaching</h2>
          <h1 class="mb-5">Latest online Courses</h1>
        </div>
        <div class="my-course-card col-3 mb-5" v-for="(index, element) in onlineCourses" :key="element">
          <img :src="require('../assets/images/' + index.imgName)" alt="">
          <div class="my-couse-desc p-3">
            <p class="fw-bold">{{ index.price }}</p>
            <h5 class="mb-4">{{ index.name }}</h5>
            <div>
              <span class="fw-lighter me-3">{{ index.numberLesson }} Lessons</span><span class="fw-lighter">{{ index.maxStudents }} Students</span>
            </div>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
          <button class="my-btn-light-orange btn w-25">View all courses</button>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name : 'MainComponent',

  data() {
    return {
      onlineCourses : [
        {
          imgName : 'artist-course-08-480x480.jpg',
          price : '$18.00',
          name : 'The Acrylic Painting Academy',
          numberLesson : 4,
          maxStudents : 50
        },
        {
          imgName : 'artist-course-07-480x480.jpg',
          price : '$21.00',
          name : 'Drawing and Shading: Complete Course',
          numberLesson : 14,
          maxStudents : 50
        },
        {
          imgName : 'artist-course-06-480x480.jpg',
          price : '$19.00',
          name : 'The Color Theory for Digital Artist',
          numberLesson : 7,
          maxStudents : 50
        },
        {
          imgName : 'artist-course-05-480x480.jpg',
          price : '$35.00',
          name : 'Ultimate Guide to Digital Sketching for Beginners',
          numberLesson : 14,
          maxStudents : 50
        },
        {
          imgName : 'artist-course-04-480x480.jpg',
          price : '$19.00',
          name : 'Portrait Drawing The Smart Way',
          numberLesson : 2,
          maxStudents : 50
        },
        {
          imgName : 'artist-course-03-480x480.jpg',
          price : '$19.00',
          name : 'Mastering Watercolor Painting from Beginer',
          numberLesson : 9,
          maxStudents : 50
        },
        {
          imgName : 'artist-course-02-480x480.jpg',
          price : '$25.00',
          name : 'The Art & Science of Drawing',
          numberLesson : 4,
          maxStudents : 50
        },
        {
          imgName : 'artist-course-01-480x480.jpg',
          price : '$22.00',
          name : 'The Colored Pencil Drawing Courses',
          numberLesson : 6,
          maxStudents : 50
        },
      ]
    }
  },
}
</script>

<style lang="scss">
@import "../assets/scss/style.scss";

  .my-hero {
    height: 70vh;
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
  .my-video-poster{
    width: 80%;
    &:hover {
      cursor: pointer;
    }
  }
  .my-testimonial-card {
    background-color: white;
    padding: 3rem;
    h4 {
      margin-bottom: 1.8rem;
    }
    p {
      margin-bottom: 2.5rem;
    }
    div {
      div {
        img {
          border-radius: 50%;
          width: 5rem;
        }
        .my-name-avatar {
            margin-top: 2rem;
        }
      }
    }
  }

  section {
    .my-course-card {
      img {
        width: 100%;
      }
      .my-couse-desc {
        p {
          color: #ef6f31;
        }
      }
    }
  }
</style>