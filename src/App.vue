<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Principal from "@/components/Principal.vue";
import Rodape from "@/components/Rodape.vue";
import Cabecalho from "@/components/Cabecalho.vue";
export default {
  components: { MenuLateral, Principal,Rodape, Cabecalho},
};
</script>
<template>
  <MenuLateral />
  <Cabecalho />
  <main id="content">Principal</main>
  <Rodape />
</template>
<style></style>
