<template>
  <v-row>
    <v-col v-for="(product, index) in products" cols="2">
      <v-card :title="product.title" :ripple="true">
        <v-card-actions>
          <v-img
            :src="require(`@/assets/images/products/${product.thumnail}`)"
          ></v-img>
        </v-card-actions>
        <v-card-text align="center" class="product-title" >
          {{ product.title }}
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>


<script>
export default {
  data() {
    return {
      products: [
        {
          id: 1,
          title: "Asus Senfone",
          thumnail: "asus-zenfone.png",
          price: 2000000,
          categoryId: 1,
        },
        {
          id: 2,
          title: "Canon Eos 700D",
          thumnail: "canon-eos-700d.png",
          price: 2000000,
          categoryId: 2,
        },
        {
          id: 3,
          title: "Canon Eos 750D",
          thumnail: "canon-eos-750d.png",
          price: 2000000,
          categoryId: 2,
        },
        {
          id: 4,
          title: "Iphone 6 Silver",
          thumnail: "iphone-6-silver.png",
          price: 2000000,
          categoryId: 1,
        },
        {
          id: 5,
          title: "Lenovo A7000",
          thumnail: "Lenovo-A7000.png",
          price: 2000000,
          categoryId: 1,
        },
        {
          id: 6,
          title: "LG 32 LED TV 32LF550A",
          thumnail: "lg-32-led-tv-32LF550A.png",
          price: 2000000,
          categoryId: 3,
        },
        {
          id: 7,
          title: "LG 32 LED TV 32LF520A",
          thumnail: "lg-led-tv32-32LF520A.png",
          price: 2000000,
          categoryId: 3,
        },
        {
          id: 8,
          title: "MI 4i",
          thumnail: "mi-4i.png",
          price: 2000000,
          categoryId: 1,
        },
        {
          id: 9,
          title: "Nikon D3200",
          thumnail: "nikon-d3200.png",
          price: 2000000,
          categoryId: 2,
        },
        {
          id: 10,
          title: "Nikon D5200",
          thumnail: "nikon-d5200.png",
          price: 2000000,
          categoryId: 2,
        },
        {
          id: 11,
          title: "Samsung Galaxy A3",
          thumnail: "samsung-galaxy-A3.png",
          price: 2000000,
          categoryId: 1,
        },
        {
          id: 12,
          title: "Samsung Galaxy A8",
          thumnail: "samsung-galaxy-A8.png",
          price: 2000000,
          categoryId: 1,
        },
        {
          id: 13,
          title: "Samsung Galaxy Grand Prime",
          thumnail: "samsung-galaxy-grand-prime.png",
          price: 2000000,
          categoryId: 1,
        },
        {
          id: 14,
          title: "Samsung Galaxy Note 3",
          thumnail: "samsung-galaxy-note-3.png",
          price: 2000000,
          categoryId: 1,
        },
        {
          id: 15,
          title: "Sharp 32 LED 32LE265i",
          thumnail: "sharp-32-led-32LE265i.png",
          price: 2000000,
          categoryId: 3,
        },
      ],
    };
  },
};
</script>

<style scoped>
    .product-title{
        white-space: nowrap;
        overflow: hidden;
        text-overflow: ellipsis;
    }
</style>></sty>