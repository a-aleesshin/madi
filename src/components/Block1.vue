<template>
  <section class="section" id="services">
    <div class="container">

      <div class="section__header">
        <h2 class="section__title">3 things to tell your peers</h2>
      </div>

      <div class="services">
        <div class="services__item  services__item--border">
          <div class="services__text">
            Intelligent applications feature behaviors and outcomes as a result of learning driven by one or more AI techniques.
          </div>
        </div>

        <div class="services__item  services__item--border">
          <div class="services__text">
            They will create value and disrupt markets by learning, adapting and generating new ideas and outcomes.
          </div>
        </div>

        <div class="services__item  services__item--border">
          <div class="services__text">
            Hype over GenAI is spurring more demand for these types of intelligent outcomes.
          </div>
        </div>
      </div>

    </div><!-- /.container -->
  </section>
</template>

<style scoped>
/* Services */

.services {
  display: flex;
  flex-wrap: wrap;
}

.services__item {
  width: 33.33333%;
  padding: 0 35px 40px 0;
  position: relative;
  margin-bottom: 40px;
}

.services__icon {
  position: absolute;
  top: 0;
  left: 28px;
  z-index: 1;
}

.services__title {
  margin-bottom: 10px;

  font-size: 14px;
  color: #333;
  text-transform: uppercase;
}

.services__text {
  font-size: 15px;
  color: #999;
}

/* Devices */

.devices {
  width: 100%;
  max-width: 600px;
  margin: 0 auto;
  position: relative;
}

.devices__item {
  display: block;
  max-width: 100%;
  height: auto;
}

.devices__item--iphone {
  position: absolute;
  bottom: -80px;
  right: 0;
  z-index: 1;
}
</style>