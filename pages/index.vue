<template>
  <v-row>
    <v-col cols="8" class="frame-content px-8">
      <products></products>
    </v-col>
    <v-col cols="4">
      ORDERS
    </v-col>
  </v-row>
</template>

<script>
import Products from '~/layouts/Products.vue'
export default {
  components: { Products },
  name: 'IndexPage'
}
</script>

<style scoped>
  .frame-content{
    height: 90vh;
    overflow-y: auto;
  }
</style>
