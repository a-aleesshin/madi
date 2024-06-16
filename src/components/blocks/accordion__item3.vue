<script setup>
import { ref } from 'vue';

const isLiked = ref(false);

const onClick = () => {
  isLiked.value = !isLiked.value;
};
</script>

<template>
  <div @click="onClick" :class="isLiked ? 'active ' : ''" class="accordion__item" data-collapse="#wedo_1">
    <div class="accordion__header">
      <img class="accordion__icon" src="" alt="">
      <div class="accordion__title">Internet of Things (IoT)</div>
    </div>
    <div class="accordion__content" id="wedo_3">
      <p>
        The Internet of Things is also one of the other technological trends of today. This refers to the transmission of data from the Internet to other devices. The Internet of Things is our future, and we have all been using it for years. It has made everything smarter than before. Whether it is smart TVs, smart watches, smart laptops, or anything else, it has improved everything. Now we can lock our house, operate our fan, TV, and everything else with just our phone. The Internet of Things is in the initial stages of development, but it has still made our lives easier and better. It has been estimated that by the year 2030, we will have 50 billion IoT devices and capabilities. We can expect that everything from our home to our kitchen will be handled by these devices.
      </p>
      <p>
        Are you interested in this field of study? Yes. One thing you can be sure of is that you will have the best and most promising career ahead of you if you learn courses related to the Internet of Things (IoT). This course is available for study on online learning platforms like Coursera, Simplilearn, and Udemy and at top universities like Stanford University. Studying courses related to information technology might be more challenging than you think. There are high chances of getting confused and backing out. But you must not lose hope. You can anytime get professional information technology assignments help to understand the courses without having to worry about deadlines and grades. Professional writers are experts and can deal with all your tasks effectively.
      </p>
    </div>
  </div>
</template>
