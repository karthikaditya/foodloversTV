<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main> -->
  <iframe src="https://www.google.com/maps/d/embed?mid=1ekHqxQnhoTzFedEyZhLkc99udUkh9Bw&ehbc=2E312F" frameborder="0"
    marginheight="0" marginwidth="0" width="100%" height="100%" scrolling="auto"></iframe>
</template>

<style>
html {
  overflow: auto;
}

html,
body,
div,
iframe {
  margin: 0px;
  padding: 0px;
  height: 100%;
  border: none;
}

iframe {
  display: block;
  width: 100%;
  border: none;
  overflow-y: auto;
  overflow-x: hidden;
}
</style>
