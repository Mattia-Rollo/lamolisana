<template>
  <HeaderComponent />
  <main>
  <ProductList />
  </main>
  <FooterComponent />
</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import ProductList from './components/ProductList.vue';

  export default {
    components: {
    HeaderComponent,
    ProductList,
    FooterComponent
}
}
</script>

<style lang="scss" scoped>

</style>