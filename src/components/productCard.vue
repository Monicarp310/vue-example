<template>
  <div class="container">
    <v-container fluid>
      <img s v-bind:src="require('./palmerita.jpg')" alt="" />
      <h3>Palmerita de chocolate</h3>
      <h4>Pieza de 425g</h4>
      <h5>1,75€/ud</h5>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "ProductCard",
  props: {
    name: String,
    weight: String,
    price: String
  },
};
</script>

<style scoped>
h5 {
  justify-self: left;
}

.container{
    display: flex;
    flex-direction: column;
    border: 2px;
    border-color: black;
}
</style>
