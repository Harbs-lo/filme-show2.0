<script setup>
import BlocoFilme from "../components/BlocoFilme.vue";
import CompRodape from "../components/CompRodape.vue";
</script>

<template>
  <body>
    <div class="pesquisa">
      <input type="text" placeholder="Pesquisar" />
      <button>Pesquisar</button>
    </div>
    <div class="reposta">
      <h1>Resultados:</h1>
      <div class="conteudoR">
        <BlocoFilme picture_src="src/assets/img/avatar.jpg" pic_link="/filme" />
        <BlocoFilme picture_src="src/assets/img/avatar.jpg" pic_link="/filme" />
        <BlocoFilme picture_src="src/assets/img/avatar.jpg" pic_link="/filme" />
        <BlocoFilme picture_src="src/assets/img/avatar.jpg" pic_link="/filme" />
        <BlocoFilme picture_src="src/assets/img/avatar.jpg" pic_link="/filme" />
      </div>
      <div class="conteudoRF">
        <BlocoFilme picture_src="src/assets/img/avatar.jpg" pic_link="/filme" />
        <BlocoFilme picture_src="src/assets/img/avatar.jpg" pic_link="/filme" />
        <BlocoFilme picture_src="src/assets/img/avatar.jpg" pic_link="/filme" />
        <BlocoFilme picture_src="src/assets/img/avatar.jpg" pic_link="/filme" />
        <BlocoFilme picture_src="src/assets/img/avatar.jpg" pic_link="/filme" />
      </div>
    </div>
    <CompRodape />
  </body>
</template>
