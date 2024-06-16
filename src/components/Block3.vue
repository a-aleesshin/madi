<template>
  <section class="section">
    <div class="container">

      <div class="section__header">
        <h2 class="section__title">Impact of a Technological Revolution</h2>
      </div>

      <div class="wedo">
        <div class="wedo__item">
          <div class="section__text">
            <p>There is a one-going debit: is the technology revolution a boon or bane? Yes, it is true. It has both positivity and negativity. If we positively use technology, it can be the best thing, but if we use it in a negative way, it can destroy society. Remember the destruction caused during the Hiroshima-Nagasaki attack? It was one of the biggest destructions to date in human history. Now it is a perfect example that if technology can cure, it can destroy too. We should be cautious while using any technique and be assured that technology is used for a good purpose.</p>
            <p>
              The following points will help you learn more about the technology revolution’s disadvantages:
            </p>
            <ul>
              <li>
                The digital revolution, or technological revolution, has increased the chances of fraud. Today, everything is globally connected, which has increased the chances of fraud.
              </li>
              <li>
                Artificial intelligence and machine learning are being developed to benefit mankind. However, these advancements can also be dangerous to humans. A few of the examples include an AI that can do the work of a human and can replace them in the future. We often hear about financial frauds where AI is used to create fake images and convince other parties.
              </li>
              <li>
                Technology can be the biggest helper for students, which would simplify their long workdays and help them score good grades. For example, there are a lot of online class help services that provide assistance to students. Whenever you wonder, I wish I could pay someone to take my online class,” you can seek assistance immediately and improve your academic performance. But overdependence on technology can also affect students learning cycles too. If you are a school or college student, you must be aware of how you use technology for your studies.
              </li>
            </ul>
          </div>
        </div>

        <div class="wedo__item">
          <img class="wedo__img" src="../assets/images/block3.jpg" alt="">
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* We do */
.wedo {
  display: flex;
  flex-wrap: wrap;
  margin: 0 -15px;
}

.wedo__item {
  width: 50%;
  padding: 0 15px;
}

.wedo__img {
  display: block;
  max-width: 100%;
  height: auto;
}

/* Accordion */

.accordion__item {
  margin-bottom: 10px;
  border: 1px solid #e5e5e5;
}

.accordion__item.active .accordion__content {
  display: block;
}

.accordion__item.active .accordion__header {
  border-bottom-color: #e5e5e5;
}

.accordion__item.active .accordion__header:after {
  transform: translateY(-50%) rotate(-45deg);
  margin-top: 5px;
}

.accordion__header {
  padding: 15px 20px 15px 65px;
  position: relative;

  border-bottom: 1px solid transparent;
  cursor: pointer;
}

.accordion__header:after {
  content: "";
  display: block;
  width: 16px;
  height: 16px;

  border-top: 2px solid #ccc;
  border-right: 2px solid #ccc;

  position: absolute;
  top: 50%;
  right: 20px;
  z-index: 1;

  transform: translateY(-50%) rotate(135deg);
}

.accordion__icon {
  position: absolute;
  top: 50%;
  left: 20px;
  z-index: 1;

  transform: translateY(-50%);
}

.accordion__content {
  padding: 15px 20px;
  display: none;

  font-size: 15px;
  color: #999;
  font-style: italic;
  font-weight: 300;
}

.accordion__title {
  font-size: 14px;
  color: #333;
  text-transform: uppercase;
}
</style>
<script setup>
</script>