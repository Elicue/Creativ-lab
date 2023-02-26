<template>
  <div>
    <div class="img">
      <img :src="url" alt="flower">
    </div>
    <div class="txt">
      <h3>{{ title }}</h3>
      <h3>{{ price }}</h3>
    </div>
    <div class="basket">
      <img src="imgs/basket.svg" alt="panier">
    </div>
  </div>
</template>

<script>

  export default {
    name : 'CatView',

    props: {
      url: String,
      title: String,
      price: String
    }
  }

</script>