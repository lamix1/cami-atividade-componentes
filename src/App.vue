<script>
import MenuLateral from "@/components/MenuLateral.vue";
import CabecalhoPrincipal from "./components/CabecalhoPrin.vue";
import MenuPrincipal from "./components/MenuPrin.vue";
import RodapePrincipal from "./components/RodapePrin.vue";
export default {
  components: {
    MenuLateral,
    CabecalhoPrincipal,
    MenuPrincipal,
    RodapePrincipal,
  },
};
</script>
<template>
  <MenuLateral />
  <CabecalhoPrincipal />
  <MenuPrincipal />
  <RodapePrincipal />
</template>
<style></style>