<template>
  <div id="Background" class="min-h-screen w-screen flex items-center gap-10">
    <div
      data-aos="fade-right"
      class="md:w-1/2 w-full h-full flex flex-col justify-center items-start md:pl-24 py-16 md:px-0 textContainer"
    >
      <h1
        class="text-gray-600 2xl:text-8xl xl:text-6xl lg:text-5xl md:text-4xl text-3xl font-bold leading-tight tracking-wider md:mb-20 mb-10"
      >
        Pregnant Women Program
      </h1>
      <p class="xl:text-2xl md:text-xl text-gray-500 leading-normal">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Distinctio,
        aliquam esse doloremque cum nesciunt alias minus blanditiis consequuntur
        facilis! Asperiores.
      </p>
      <v-btn
        color="#e8c8c3"
        width="225px"
        height="65px"
        class="md:mt-20 mt-10 py-4 px-8"
        large
        elevation="0"
        ><span class="text-gray-600 xl:text-2xl lg:text-xl md:text-lg font-bold"
          >JOIN US NOW</span
        ></v-btn
      >
    </div>
    <div class="md:flex hidden md:w-1/2 h-full px-12 justify-center"></div>
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
#Background {
  background-image: url("@/assets/Pregnant.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  overflow: hidden;
  background-color: #e5e3e1;
}
@media (max-width: 768px) {
  #Background {
    background-image: url("@/assets/PregnantMobile.png");
    background-position: right right;
  }
  .textContainer {
    align-items: center;
    text-align: center;
  }
}
</style>
