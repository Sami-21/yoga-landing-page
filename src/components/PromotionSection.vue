<template>
  <div
    id="BackgroundColor"
    class="
      w-screen
      flex
      lg:flex-row
      flex-col-reverse
      lg:justify-between
      justify-around
      items-center
      sm:py-32
      py-16
      relative
      overflow-hidden
    "
  >
    <div
      id="PromotionImage"
      data-aos="fade-right"
      class="
        2xl:h-10/12
        h-full
        xl:w-7/12
        lg:w-9/12
        w-full
        absolute
        bottom-0
        left-0
        sm:mb-20
        mb-12
      "
    ></div>
    <div class="md:w-1/2 w-full h-1/2 block"></div>
    <div data-aos="fade-left" class="textContainer lg:w-1/2 w-10/12 ">
      <h1
        class="
          text-gray-600
          2xl:text-8xl
          xl:text-7xl
          lg:text-6xl
          md:text-5xl
          text-3xl
          font-bold
          leading-tight
          tracking-wider
          md:mb-20
          sm:mb-12
          mb-4
          relative
          z-20
        "
      >
        Join Now and Get 50% Off
      </h1>
      <p
        class="
          xl:text-4xl
          lg:text-2xl
          md:text-xl
          text-lg
          md:text-gray-500
          leading-normal
          relative
          z-20
        "
      >
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Distinctio,
        aliquam esse doloremque cum nesciunt alias minus blanditiis consequuntur
        facilis! Asperiores.
      </p>
      <v-btn
        color="#e8c8c3"
        width="250px"
        height="65px"
        class="md:mt-20 sm:mt-10 mt-4 py-4 px-8"
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
import "aos/dist/aos.css";

AOS.init({
  duration: 750,
});

export default {};
</script>

<style scoped>
.textContainer { 
  height:fit-content;
  text-align:left;
  padding-right: 4rem;
}
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

@media (max-width: 1535px) {
  h1::after {
    top: -0.75rem;
    left: -3rem;
    width: 350px;
    height: 200px;
  }
}

@media (max-width: 1023px) {
  #BackgroundColor {
    height: calc(90vh - 200px) !important;
  }
  .textContainer {
    padding-right: 0rem;
    text-align:center;
  }
 
  h1::after {
    top: -1.25rem;
    left: 0rem;
    width: 350px;
    height: 200px;
  }
}
@media (max-width: 767px) {
  #PromotionImage {
    opacity: 0.75;
  }
  h1::after {
    width: 0;
    height: 0;
  }
}

@media (max-width: 400px) {
  #BackgroundColor{
    height:650px !important;
  }

}
</style>
