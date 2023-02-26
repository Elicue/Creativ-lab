<template>
  <div class="flex flex-col items-center rounded-full border-primary border-2 w-[35vh] h-[50vh] relative">
    <div class="img h-[30vh] w-full">
      <img class="rounded-tl-full rounded-tr-full border-b-primary border-b-2 h-[30vh] object-cover w-full" :src="url" alt="flower">
    </div>
    <div class="txt h-[15vh] w-full items-center flex flex-col justify-around">
      <h3 class="font-rainbow text-2xl">{{ title }}</h3>
      <p class="text-xl">{{ price }}</p>
    </div>
    <div class="basket absolute -bottom-[2vh] bg-rose rounded-full border-primary border-2 h-[6vh] w-[5vh] items-center justify-center flex">
      <img class="w-[3vh] h-[3vh]" src="imgs/basket.svg" alt="panier">
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