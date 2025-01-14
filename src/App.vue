<template>
  <div id="app">
    <div class="container">
      <Skills />
      <Icons />
    </div>
    <footer class="footer">
      <p>© Todos os direitos reservados</p>
    </footer>
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
  min-height: 100vh; /* Garantir que o rodapé fique no fim da página */
}

.container {
  display: flex;
  flex-direction: column;
  width: 100%;
  flex: 1; /* Para ocupar o espaço disponível */
}

.footer {
  text-align: center;
    font-size: x-small;
    width: 40%;
    background-color: #bdc3c775;
    border-radius: 10px;
    color: #000;
}
</style>
