<script setup>
import { ref } from 'vue';

const isLiked = ref(false);

const onClick = () => {
  isLiked.value = !isLiked.value;
};
</script>

<template>
  <div :class="isLiked ? 'active ' : ''" class="widget-form">
    <iframe
        allow="microphone;"
        width="350"
        height="430"
        src="https://console.dialogflow.com/api-client/demo/embedded/7df5eff2-71e8-4b7f-9b2e-2de3113252ee">
    </iframe>
  </div>
  <div class="widget-button">
    <button @click="onClick" class="widget-btn"></button>
  </div>

</template>

<style scoped>
  .widget-form {
    position: fixed;
    right: 50px;
    bottom: 100px;
    z-index: 1000;
    display: none;
  }

  .widget-form.active {
    display: block;
  }

  .widget-form-wrapper {
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;
    justify-content: space-between;

    width: 500px;
    height: 700px;
    padding: 20px;

    background: #fff;
    border-radius: 30px;
    box-shadow: 4px 4px 8px 0px rgba(34, 60, 80, 0.2);
  }

  .widget-button {
    position: fixed;
    right: 50px;
    bottom: 50px;
    z-index: 1000;
  }

  .widget-btn {
    width: 2.2em;
    height: 2.2em;
    font-size: inherit;
    cursor: pointer;
    border: 0;
    border-radius: 50%;
    background-color: inherit;
    background-image: url(https://yastatic.net/s3/home/alice_popup/fab-icon-new.svg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: 2.2em;
    transition: transform ease-out .15s;
    will-change: transform;
  }

  .widget-form-form form {
    display: block;
    width: 100%;
  }

  .widget-form-form form input {
    width: 100%;
    border: 1px solid #17cad0;
    padding: 10px;
    border-radius: 30px;
  }

  .widget-form-form form .widget-btn {
    display: block;
    width: 100%;
    border-radius: 30px;
    padding: 10px;
    margin-top: 20px;
    margin-bottom: 0;
    font-size: 14px;
    font-weight: 400;
    color: #fff;
    text-align: center;
    background: #17cad0;
    height: auto;
  }

  .widget-form-text {
    height: 100%;
    overflow-y: scroll;
  }

  .widget-form-text p {
    margin-bottom: 10px;
  }
</style>