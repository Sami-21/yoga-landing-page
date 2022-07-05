<template>
  <div
    id="Background"
    class="min-h-screen w-screen flex items-center gap-10 overflow-hidden"
  >
    <div
      data-aos="fade-right"
      class="
        lg:w-1/2
        h-full
        flex flex-col
        justify-center
        xl:items-start
        items-center
        xl:pl-24
        textContainer
      "
    >
      <h1
        class="
          xl:text-gray-600
          text-gray-100
          2xl:text-8xl
          xl:text-7xl
          lg:text-6xl
          md:text-5xl
          text-4xl
          font-bold
          leading-tight
          tracking-wider
          md:mb-20
          mb-10
        "
      >
        Pregnant Women Program
      </h1>
      <p class="xl:text-3xl lg:text-2xl md:text-xl text-lg xl:text-gray-500 text-white leading-normal">
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
        ><span class="text-gray-600 xl:text-2xl lg:text-xl md:text-lg font-bold"
          >JOIN US NOW</span
        ></v-btn
      >
    </div>
    <div class="xl:block hidden md:w-1/2 h-full px-12 justify-center"></div>
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



#Background {
  background-image: url("@/assets/Pregnant.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  overflow: hidden;
  background-color: #e5e3e1;
}

@media (max-width: 1279px) {
  #Background {
    background:#484F5B;
    background-image: url("@/assets/PregnantTablet.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: right;
    background-blend-mode:multiply;
  }
  .textContainer{
    text-align:center;
    padding :0 100px;
}
 
}
@media (max-width: 767px) {
  #Background {
    background-image: url("@/assets/PregnantMobile.png");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: right;
  }
    .textContainer{
    padding :0 50px;
}
}
</style>
