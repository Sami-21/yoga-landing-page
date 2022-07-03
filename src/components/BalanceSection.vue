<template>
  <div
    id="Background"
    class="min-h-screen w-screen flex items-center lg:flex-row flex-col gap-10 py-16 relative"
  >
    <img
      data-aos="fade-right"
      src="@/assets/flowertopleft.png"
      alt="flower"
      class="absolute top-0 md:left-0 -left-10 md:scale-100 scale-75"
    />
    <img
      data-aos="fade-left"
      src="@/assets/flowerTopRight.png"
      alt="flower"
      class="absolute top-0 md:right-0 -right-10 md:scale-100 scale-75"
    /><img
      data-aos="fade-up-left"
      src="@/assets/flowerBottomRight.png"
      alt="flower"
      class="absolute md:bottom-0 -bottom-5 md:right-0 -right-8 md:scale-100 scale-75"
    />
    <img
      data-aos="zoom-in"
      src="@/assets/BalanceWomen.png"
      alt="women"
      class="lg:w-1/2 w-full h-fit px-12 flex justify-center z-20 md:p-0 p-8"
    />
    <div
      data-aos="fade-left"
      class="textContainer lg:w-1/2 w-full h-full flex flex-col justify-center items-start md:pr-24 md:pl-0 px-16"
    >
      <h1
        id="title"
        class="text-gray-600 2xl:text-8xl xl:text-6xl lg:text-5xl md:text-4xl text-3xl font-bold leading-tight tracking-wider md:mb-32 mb-10"
      >
        Balance Your Body and Mind
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
@media (max-width: 1024px) {
  h1,
  p {
    text-align: center;
  }
  .textContainer {
    align-items: center;
  }
}
</style>
