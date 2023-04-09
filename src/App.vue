<template>
  <MainHeader />
  <div class="page">
    <div class="intro">
      <div class="intro__inner">
        <div class="container">
          <h2 class="intro__subtitle">Creative Template</h2>
          <h1 class="intro__title">Welcome to MoGo</h1>

          <a class="btn" href="#">Learn More</a>
        </div>
      </div>
      <div class="slider">
        <div class="container">
          <div class="slider__inner">
            <div class="slider__item active">
              <span class="slider__num">01</span>
              <span class="slider__text">Intro</span>
            </div>
            <div class="slider__item">
              <span class="slider__num">02</span>
              <span class="slider__text">Work</span>
            </div>
            <div class="slider__item">
              <span class="slider__num">03</span>
              <span class="slider__text">About</span>
            </div>
            <div class="slider__item">
              <span class="slider__num">04</span>
              <span class="slider__text">Contacts</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--intro-->
  </div>
</template>

<script>
import MainHeader from "./components/MainHeader.vue";
export default {
  components: {
    MainHeader,
  },
  data() {
    return {};
  },
};
</script>

<style>
body {
  background: #676767;
}
</style>
