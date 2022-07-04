<template>
  <div
    id="BackgroundColor"
    class="min-h-screen w-screen flex items-center gap-10 py-16 relative overflow-hidden"
  >
    <div
      id="PromotionImage"
      data-aos="fade-right"
      class="h-full xl:w-7/12 lg:w-9/12 w-full absolute bottom-0 left-0 mb-4"
    ></div>
    <div class="md:w-1/2 md:block hidden"></div>
    <div
      data-aos="fade-left"
      class="textContainer md:w-1/2 w-full h-full flex flex-col justify-center md:pr-24 px-12"
    >
      <h1
        class="text-gray-600 2xl:text-8xl xl:text-6xl lg:text-5xl md:text-4xl text-3xl font-bold leading-tight tracking-wider md:mb-20 mb-12 relative z-20"
      >
        Join Now and Get 50% Off
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
import AOS from "aos";
import "aos/dist/aos.css"; // You can also use <link> for styles
// ..
AOS.init({
  duration: 750,
});
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
}
h1::after {
  content: "";
  position: absolute;
  top: -0.25rem;
  left: -4rem;
  width: 400px;
  height: 250px;
  z-index: -1;
  background-image: url("@/assets/Promotion\(2\).png");
  background-position: top left;
  background-repeat: no-repeat;
  background-size: cover;
}

@media (max-width: 1536px) {
  h1::after {
    top: -0.75rem;
    left: -3rem;
    width: 350px;
    height: 200px;
  }
}

@media (max-width: 1024px) {
  h1::after {
    top: -1.25rem;
    left: 0rem;
    width: 350px;
    height: 200px;
  }
}
@media (max-width: 768px) {
  .textContainer {
    align-items: center;
    text-align: center;
  }
  #PromotionImage {
    opacity: 0.75;
    background-position: center;
  }
  h1::after {
    width: 0;
    height: 0;
  }
}
</style>
