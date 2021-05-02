<template>
  <div id="app">
    <socialmedia></socialmedia>
    <overviewtoday></overviewtoday>
  </div>
</template>

<script>
import socialmedia from "./components/social-media.vue";
import overviewtoday from './components/overview-today'
export default {
  name: "App",
  components: {
    socialmedia,
    overviewtoday,
  },
};
</script>

