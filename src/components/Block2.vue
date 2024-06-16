<script setup>
import { ref } from 'vue';
import Accordion__item from "@/components/blocks/accordion__item.vue";
import Accordion__item2 from "@/components/blocks/accordion__item2.vue";
import Accordion__item3 from "@/components/blocks/accordion__item3.vue";

const isLiked = ref(false);

const onClick = () => {
  isLiked.value = !isLiked.value;
};
</script>

<template>
  <section class="section">
    <div class="container">

      <div class="section__header">
        <h3 class="section__suptitle">History of Technological Revolution</h3>
        <h2 class="section__title">Top Technology Trends in 2023</h2>
        <div class="section__text">
          <p>The revolution is not a new concept; it has existed since ancient times. There are many great examples of revolution in this world. A few of the examples are the financial-agricultural revolution (1600–1740), the industrial revolution (1780–1840), the scientific-technical revolution (1940–1970), the technical revolution, or Second Industrial Revolution (1870–1920), and the information and telecommunications revolution. No one can readily conclude when the technological revolution started, but we can predict that most of the technological revolution occurred in the 19th century. There is no doubt that the technological revolution is a boom for our industry. The era of multiple technological innovations is termed a revolution in technology.
          </p>
          <p>
            Daniel Smihula has termed the concept “Smihula Waves,” which discusses the different waves of technological processes. This chapter discusses the different technological revolutions, such as the Indo-European technological revolution (1900–1100 BC), the Germano-Slavic technological revolution (300–700 AD), the Renaissance technological revolution (1340–1470 AD), the Celtic and Greek technological revolution (700–200 BC), and the Mediaeval technological revolution (930–1200 AD).
          </p>
        </div>
      </div>

      <div class="wedo">
        <div class="wedo__item">
          <img class="wedo__img" src="../assets/images/block2.jpg" alt="">
        </div>

        <div class="wedo__item">

          <div class="accordion">
            <Accordion__item />
            <Accordion__item2 />
            <Accordion__item3 />
          </div><!-- /.accordion -->

        </div><!-- /.wedo__item -->
      </div><!-- /.wedo -->

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
</style>