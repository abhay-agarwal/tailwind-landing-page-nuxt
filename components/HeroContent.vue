<template>
  <div class="pt-24">
    <div
      class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center"
    >
      <!--Left Col-->
      <div
        class="flex flex-col w-full md:w-2/5 justify-center items-start text-center md:text-left"
      >
        <!-- <p class="uppercase tracking-loose w-full">
          Go DTC Everywhere
        </p> -->
        <h1 class="my-4 text-6xl leading-tight alt-text alt-text-shadow">
          The Put-it-Anywhere Buy Button
        </h1>
        <p class="text-xl mb-8 leading-tight">
          Place native shopping carts and buy buttons on any digital property,
          from websites to mobile and everything in between. No more redirects
          or “where to buy” pop-ups.
        </p>

        <button
          class="mx-auto lg:mx-0 hover:underline bg-white text-gray-800 font-bold rounded-full my-6 py-4 px-8 shadow-lg alt-text"
          onclick="
              Calendly.initPopupWidget({
                url: 'https://calendly.com/buywithpoly/intro'
              })
              return false
            "
        >
          Schedule a Demo
        </button>
      </div>
      <!--Right Col-->
      <div class="w-full md:w-3/5 py-6 text-center hero-image">
        <img class="w-full md:w-4/5" src="~/assets/img/phone.png" alt />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroContent'
}
</script>

<style scoped>
.hero-image {
  margin-bottom: -200px;
  overflow: visible;
  z-index: 10;
}
</style>
