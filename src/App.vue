<template>
  <div id="app">
    <div class="container">
      <Skills />
      <Icons />
    </div>
  </div>
</template>

<script>
import Skills from './components/Skills.vue';
import Icons from './components/Icons.vue';

export default {
  components: {
    Skills,
    Icons
  }
};
</script>

<style>
#app {
  background-color: #fff;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 20px;
}
.container {
  display: flex;
  flex-direction: column;
  width: 100%;
}
</style>
