<script setup>
import Intro from './components/Intro.vue'
import Block2 from "./components/Block2.vue";
import Block1 from "./components/Block1.vue";
import Block3 from "./components/Block3.vue";
import Widget from "./components/Widget.vue";
</script>

<template>
  <main>
    <Intro />
  </main>
  <Block1 />
  <Block2 />
  <Block3 />
  <Widget />
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
