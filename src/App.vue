<template>
  <div class="global">
    <div data-tauri-drag-region>c</div>
    <HomePage />
    <div class="inf">
      Version：0.3.0<br>
      Digital Class 由 Tarui 强力驱动<br>
      Design by db2333
    </div>
  </div>
</template>

<script>
import HomePage from './components/home.vue'
export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>
.inf {
  color: rgb(91, 91, 91);
  text-align: center;
  font-size: small;
}

.global {
  background-color: rgba(255, 255, 255, 1);
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  overflow: hidden;
}
</style>
