<template>
  <div class="skills">
    <h1>MINHAS HABILIDADES</h1>
    <hr />
    <h2>Desenvolvimento Web</h2>
    <hr />

    <div class="section">
      <h2>Introdução à Programação HTML</h2>
      <p>Compreensão do funcionamento da internet na perspectiva do desenvolvedor.</p>
      <p>Uso do HTML para criar páginas multiplataforma seguindo padrões de mercado.</p>
      <p>Práticas de layout e acessibilidade na web.</p>
    </div>

    <hr />

    <div class="section">
      <h2>Introdução ao CSS</h2>
      <p>Estilização e design responsivo de páginas HTML.</p>
      <p>Criação de grades e layouts fluídos com CSS.</p>
      <p>Uso de imagens e gráficos para enriquecer o design.</p>
      <p>Organização e desenvolvimento de projetos web com HTML e CSS.</p>
    </div>

    <hr />

    <div class="section">
      <h2>Planejamento e Desenvolvimento de Landing Pages</h2>
      <p>Prototipagem de layouts no Figma.</p>
      <p>Desenvolvimento de landing pages visualmente atraentes com HTML, CSS e Bootstrap.</p>
      <p>Validação de formulários com JavaScript.</p>
    </div>

    <hr />

    <div class="section">
      <h2>Introdução à Programação JavaScript</h2>
      <p>Introdução às funções e sintaxe JavaScript.</p>
      <p>Desenvolvimento de soluções completas integrando HTML, CSS e JavaScript.</p>
    </div>

    <hr />
  </div>
</template>

<script>
export default {};
</script>

<style>
.skills {
  width: 100%;
  max-width: 1200px;
  text-align: left;
  margin: auto;
}
.section {
  margin-bottom: 20px;
}
hr {
  width: 100%;
  border: none;
  border-top: 1px solid rgba(0, 0, 0, 0.1);
  margin: 20px 0;
}
@media (max-width: 1024px) {
  .section {
    text-align: center;
  }
}
</style>
