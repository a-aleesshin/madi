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
      <div class="accordion__title">5G Network</div>
    </div>
    <div class="accordion__content" id="wedo_2">
      <p>If you are someone who was born in the late 90s or early 20s, then you must be well aware of the uses of 2G and 3G, right? How the internet used to buffer for minutes to load a single video? At those times, people were not aware of browsing the Internet. Things became faster and easier after the introduction of the 4G network. Everyone started to browse the Internet without any difficulty.</p>
      <p>
        There is no denying that many people still use 4G networks, but we have stepped into the 5G network. This network has revolutionized our lives and introduced us to advanced technologies. It has been estimated that by the year 2027, more than 4 billion people will subscribe to this service and start getting the benefits of this data-driven service. All the top telecom companies have started initiatives to reach everyone worldwide with this service. In addition to this, new measures and network design proposals have also been made for the development of 6G.
      </p>
    </div>
  </div>
</template>
