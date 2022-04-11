<template>
  <div>
    <!-- HERO -->
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


    <!-- ARTIST COACHING -->
    <section class="my-padding-website position-relative">
      <div class="my-shapes-artist-coaching">
        <img class="position-absolute artist-shape-01" :src="require('../assets/images/artist-shape-01.png')" alt="">
        <img class="position-absolute line-shape" :src="require('../assets/images/maxcoach-shape-03.png')" alt="">
        <img class="position-absolute maxcoach-shape-13" :src="require('../assets/images/maxcoach-shape-13.png')" alt="">
      </div>
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
          <div class="my-shapes-video-poster">
            <img class="position-absolute maxcoach-shape-12" :src="require('../assets/images/maxcoach-shape-12.png')" alt="">
            <img class="position-absolute maxcoach-shape-5" :src="require('../assets/images/maxcoach-shape-05.png')" alt="">
            <span class="position-absolute">o</span>
          </div>
          <img class="my-video-poster" :src="require('../assets/images/artist-video-poster.jpg')" alt="Video poster image">
          <img class="my-center-a-div" :src="require('../assets/images/icon-youtube-play.png')" alt="Youtube icon">
        </div>
      </div>
    </section>


    <!-- TESTIMONIALS -->
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
        <div class="col-12 mt-5 text-center">
          <i class="fa-solid fa-circle me-3"></i>
          <i class="fa-solid fa-circle me-3 opacity-25"></i>
          <i class="fa-solid fa-circle me-3 opacity-25"></i>
          <i class="fa-solid fa-circle me-3 opacity-25"></i>
        </div>
      </div>
    </section>


    <!-- LATEST COURSES -->
    <section class="my-padding-website position-relative">
      <div class="my-shapes-latest-courses">
        <img class="position-absolute artist-shape-01" :src="require('../assets/images/artist-shape-01.png')" alt="">
        <h1 class="position-absolute">Courses</h1>
      </div>
      <div class="row">
        <div class="col-12 text-center">
          <h2 class="my-blue-write">Artist coaching</h2>
          <h1 class="mb-5">Latest online Courses</h1>
        </div>
        <div class="my-course-card col-3 mb-5" v-for="(element, index) in onlineCourses" :key="index">
          <img :src="require('../assets/images/' + element.imgName)" :alt="element.name + ''">
          <div class="my-course-desc p-3">
            <p class="fw-bold">{{ element.price }}</p>
            <h5 class="mb-4">{{ element.name }}</h5>
            <div>
              <span class="fw-lighter me-3"><i class="fa-regular fa-file-lines"></i> {{ element.numberLesson }} Lessons</span><span class="fw-lighter"><i class="fa-regular fa-user"></i> {{ element.maxStudents }} Students</span>
            </div>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
          <button class="my-btn-light-orange btn w-25">View all courses <i class="fa-solid fa-arrow-right-long"></i></button>
      </div>
    </section>


    <!-- ARTICLES AND TIPS -->
    <section class="my-padding-website my-bg-latest-blog">
      <div class="row">
        <div class="col-12 text-center">
          <h2 class="my-blue-write">Articles and Tips</h2>
          <h1 class="mb-5">Latest online Courses</h1>
        </div>
        <div class="col-4 my-padding-article-card">
          <div class="my-course-card mt-5 bg-white shadow">
            <img :src="require('../assets/images/artist-blog-03-480x356.jpeg')" alt="">
            <div class="my-course-desc p-3">
              <p class="fw-lighter text-uppercase">Artist</p>
              <h5 class="mb-4">Brush Strokes Energize Trees in Paintings</h5>
              <div>
                <span class="fw-lighter me-3"><i class="fa-regular fa-calendar"></i> May 15, 2020</span><span class="fw-lighter"><i class="fa-solid fa-eye"></i> 688 views</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="my-course-card mb-5 bg-white position-relative">
            <img :src="require('../assets/images/artist-blog-02-500x680.jpg')" alt="">
            <div id="my-desc-self-portrait" class="my-course-desc p-3 position-absolute">
              <p class="text-uppercase fw-bold text-white">Artist</p>
              <h3 class="mb-4 fw-bold">Connection Between Self-Portraits and Identity</h3>
              <div>
                <span class="fw-lighter me-3"><i class="fa-regular fa-calendar"></i> May 15, 2020</span><span class="fw-lighter"><i class="fa-solid fa-eye"></i> 397 views</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col-4 my-padding-article-card">
          <div class="my-course-card bg-white shadow">
            <img :src="require('../assets/images/artist-blog-01-480x356.jpg')" alt="">
            <div class="my-course-desc p-3">
              <p class="fw-lighter text-uppercase">Artist</p>
              <h5 class="mb-4">Pocket-Sized Notebooks Hold Miniature Paintings</h5>
              <div>
                <span class="fw-lighter me-3"><i class="fa-regular fa-calendar"></i> May 15, 2020</span><span class="fw-lighter"><i class="fa-solid fa-eye"></i> 603 views</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 mt-5 text-center">
          <h4>Get into details now? View all posts</h4>
        </div>
      </div>
    </section>


    <!-- UPCOMING EVENTS -->
    <section class="my-padding-website">
      <div class="row">
        <div class="col-12 text-center">
          <h2 class="my-blue-write">Upcoming Events</h2>
          <h1 class="mb-5">Let's Work Together</h1>
        </div>
        <div class="col-6 d-flex">
          <div>
            <img class="my-img-upcoming-events" :src="require('../assets/images/artist-event-04-250x300.jpg')" alt="">
          </div>
          <div class="my-desc-upcoming-events">
            <p class="my-fw-light">NOV 22, 2020</p>
            <h4 class="mb-3">Storytelling Workshop</h4>
            <span class="fw-lighter"><i class="fa-solid fa-location-dot"></i> Texas, US</span>
          </div>
        </div>
        <div class="col-6 d-flex">
          <div>
            <img class="my-img-upcoming-events" :src="require('../assets/images/artist-event-03-250x300.jpg')" alt="">
          </div>
          <div class="my-desc-upcoming-events">
            <p class="my-fw-light">OCT 10, 2020</p>
            <h4 class="mb-3">Painting Art Contest 2020</h4>
            <span class="fw-lighter"><i class="fa-solid fa-location-dot"></i> New York, US</span>
          </div>
        </div>
        <div class="col-6 d-flex">
          <div class="my-desc-upcoming-events">
            <p class="my-fw-light">NOV 23, 2020</p>
            <h4 class="mb-3">International Art Fair 2020</h4>
            <span class="fw-lighter"><i class="fa-solid fa-location-dot"></i> Hamburg, Germany</span>
          </div>
          <div>
            <img class="my-img-upcoming-events" :src="require('../assets/images/artist-event-02-250x300.jpg')" alt="">
          </div>
        </div>
        <div class="col-6 d-flex">
          <div class="my-desc-upcoming-events">
            <p class="my-fw-light">DEC 15, 2020</p>
            <h4 class="mb-3">Street Performance: Call for Artist</h4>
            <span class="fw-lighter"><i class="fa-solid fa-location-dot"></i> Illinois, US</span>
          </div>
          <div>
            <img class="my-img-upcoming-events" :src="require('../assets/images/artist-event-01-250x300.jpg')" alt="">
          </div>
        </div>
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
      &:hover > .my-course-desc{
        border: 2px solid #ef6f31;
        background-color: white;
        transform: translateY(-5rem);
        transition: background-color .2s ease-in-out, border-color .5s ease-in-out, transform .5s ease-in-out;
      }
      .my-course-desc {
        p {
          color: #ef6f31;
        }
      }
    }
  }

  .my-bg-latest-blog {
    background-color: #f5f7fa;
  }
  #my-desc-self-portrait {
    bottom: 0;
    color: white;
  }
  .my-padding-article-card {
    padding: 6rem;
  }

  div {
    .my-img-upcoming-events{
      width: 17rem;
      height: 20rem;
    }
    .my-desc-upcoming-events {
      padding: 6rem 2rem;
    }
  }

  // Start shape section

  .my-shapes-artist-coaching{
    .artist-shape-01{
      transform: rotate(230deg);
      left: -10rem;
    }
    .line-shape{
      opacity: .2;
      left: 0;
      top: 1rem;
      width: 100%;
    }
    .maxcoach-shape-13 {
      top: 20rem;
      right: 0;
    }
  }

  .my-shapes-video-poster{
    .maxcoach-shape-5 {
      z-index: -1;
      top: 1.5rem;
      left: 5.5rem;
    }
    .maxcoach-shape-12 {
      z-index: -1;
      bottom: 1.5rem;
      right: 0;
    }
    span {
      font-size: 8rem;
      color: #ffcfb9;
      top: 9rem;
      right: 5.5rem;
    }
  }

  .my-shapes-latest-courses{
    .artist-shape-01 {
      top: 30rem;
      left: -20rem;
    }
    h1 {
      font-size: 15rem;
      color: white;
      text-shadow: 2px 0 0 #ffcfb9, -2px 0 0 #ffcfb9, 0 2px 0 #ffcfb9, 0 -2px 0 #ffcfb9, 1px 1px #ffcfb9, -1px -1px 0 #ffcfb9, 1px -1px 0 #ffcfb9, -1px 1px 0 #ffcfb9;
      top: 40%;
      right: -20rem;
      transform: rotate(90deg);
    }
  }
  // Start shape section
</style>