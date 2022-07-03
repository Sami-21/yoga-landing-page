<template>
  <div
    id="BackgroundColor"
    class="min-h-screen w-screen flex items-center gap-10 py-16 relative"
  >
    <div
      id="PromotionImage"
      class="h-full xl:w-7/12 lg:w-9/12 w-full absolute bottom-0 left-0 mb-4"
    ></div>
    <div class="md:w-1/2 md:block hidden"></div>
    <div
      class="textContainer md:w-1/2 w-full h-full flex flex-col justify-center md:pr-24 px-12 z-20"
    >
      <h1
        class="text-gray-600 2xl:text-8xl xl:text-6xl lg:text-5xl md:text-4xl text-3xl font-bold leading-tight tracking-wider md:mb-20 mb-12 z-40 relative"
      >
        Join Now and Get 50% Off
        <!-- <img
          src="@/assets/Promotion(2).png"
          alt=""
          class="absolute top-0 left-0 w-96 h-56"
        /> -->
      </h1>
      <p class="xl:text-2xl lg:text-lg md:text-gray-500 leading-normal">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Distinctio,
        aliquam esse doloremque cum nesciunt alias minus blanditiis consequuntur
        facilis! Asperiores.
      </p>
      <v-btn
        color="#e8c8c3"
        width="250px"
        height="65px"
        class="md:mt-20 mt-10 py-4 px-8"
        large
        elevation="0"
        ><span class="text-gray-600 xl:text-2xl lg:text-xl md:text-lg font-bold"
          >JOIN NOW</span
        ></v-btn
      >
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#BackgroundColor {
  background-color: #eeeae7;
}
#PromotionImage {
  background-image: url("@/assets/Promotion.png");
  background-repeat: no-repeat;
  background-position: left bottom;
  background-size: contain;
  z-index: 1;
}
/* h1::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 400px;
  height: 250px;
  z-index: 1;
  background-image: url("@/assets/Promotion\(2\).png");
  background-position: top left;
  background-repeat: no-repeat;
  background-size: cover;
} */

@media (max-width: 768px) {
  .textContainer {
    align-items: center;
    text-align: center;
  }
  #PromotionImage {
    opacity: 0.75;
    background-position: center;
  }
}
</style>
