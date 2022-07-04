<template>
  <div
    class="Box min-h-screen w-screen flex flex-col items-center py-28 relative overflow-hidden"
  >
    <img
      src="@/assets/GaleryTopRight .png"
      alt=""
      class="absolute md:top-0 -top-10 md:right-0 -right-5 md:scale-100 scale-75"
    />
    <img
      src="@/assets/GaleryBottomRight.png"
      alt=""
      class="absolute bottom-10 md:right-20 -right-10 md:scale-100 scale-75"
    />
    <img
      src="@/assets/GaleryDots.png"
      alt=""
      class="absolute bottom-32 md:left-32 -left-20 md:scale-100 scale-75"
    />
    <img
      src="@/assets/GaleryTopLeft.png"
      alt=""
      class="absolute top-32 md:left-12 left-4 md:scale-100 scale-75"
    />
    <img
      src="@/assets/GaleryBottomLeft.png"
      alt="flower"
      class="absolute md:bottom-0 -bottom-6 md:left-0 -left-7 md:scale-100 scale-75"
    />
    <div data-aos="fade-down" class="lg:w-3/4 w-full mx-auto text-center px-16">
      <h1
        class="text-gray-600 xl:text-8xl lg:text-6xl text-5xl font-bold mb-16"
      >
        Galery
      </h1>
      <p
        class="xl:text-4xl lg:text-2xl md:text-lg text-gray-500 leading-normal"
      >
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam
        atque sed nam consequatur corrupti.
      </p>
    </div>
    <div
      class="grid 2xl:gap-32 gap-28 xl:grid-cols-3 lg:grid-cols-2 grid-cols-1 w-full min-h-fit mt-24 md:px-20 px-0 overflow-hidden"
    >
      <CardComponent ImageName="CardPic1.png" data-aos="fade-up" />
      <CardComponent ImageName="CardPic2.png" data-aos="fade-up" />
      <CardComponent ImageName="CardPic3.png" data-aos="fade-up" />
    </div>
  </div>
</template>

<script>
import CardComponent from "./CardComponent.vue";
import AOS from "aos";
import "aos/dist/aos.css"; // You can also use <link> for styles
// ..
AOS.init({
  duration: 750,
});
export default {
  components: { CardComponent },
};
</script>

<style scoped>
.Box {
  padding-left: 8rem;
  padding-right: 8rem;
}
@media (max-width: 768px) {
  .Box {
    padding-left: 1rem;
    padding-right: 1rem;
  }
}
</style>
