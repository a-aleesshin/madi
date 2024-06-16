<template>
  <div class="intro" id="intro">
    <div class="intro__image">
      <img src="../assets/images/intro-2.jpg">
    </div>
    <div class="container">
      <div class="intro__inner">
        <h2 class="intro__suptitle">Future innovations</h2>
        <h1 class="intro__title">Technology Revolution</h1>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Intro */
.intro {
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 100%;
  height: 100vh;
  min-height: 820px;
  position: relative;

  //background: url("../assets/images/img-intro.jpg") center no-repeat;
  //-webkit-background-size: cover;
  //background-size: cover;
}

.intro__image {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  z-index: -1;

  display: block;
  width: 100%;
  height: 100%;
}

.intro__image img {
  display: block;
  width: 100%;
  height: 100%;

  object-fit: cover;
}

.intro__inner {
  width: 100%;
  max-width: 880px;
  margin: 0 auto;

  text-align: center;
}

.intro__title {
  color: #2a2c2c;
  font-size: 80px;
  font-weight: 700;
  text-transform: uppercase;
  line-height: 1;
}

.intro__title:after {
  content: "";
  display: block;
  width: 60px;
  height: 3px;
  margin: 60px auto;

  background-color: #fff;
}

.intro__suptitle {
  margin-bottom: 20px;

  font-family: 'Kaushan Script', cursive;
  font-size: 72px;
  color: #2a2c2c;
}
</style>