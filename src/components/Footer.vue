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

    </section>
  </div>
</template>

<script>
export default {
  name : 'FooterComponent',
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
</style>