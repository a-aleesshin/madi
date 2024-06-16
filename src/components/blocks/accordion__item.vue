<script setup>
import { ref } from 'vue';

const isLiked = ref(true);

const onClick = () => {
  isLiked.value = !isLiked.value;
};
</script>

<template>
  <div @click="onClick" :class="isLiked ? 'active ' : ''" class="accordion__item" data-collapse="#wedo_1">
    <div class="accordion__header">
      <img class="accordion__icon" src="" alt="">
      <div class="accordion__title">Artificial Intelligence and Machine Learning</div>
    </div>
    <div class="accordion__content" id="wedo_1">
      <p>Artificial intelligence, most commonly known as AI, refers to training machines to act smartly. For many years, contributions have been made in this field to let machines do all the work of humans. In 2023, we can proudly say that more advancement has been made in this field, and machines are not just machines anymore; they are capable of doing everything. They are equal to humans and can learn, work, take decisions, predict risks, and do many more things.

      </p>
    </div>
  </div>
</template>
