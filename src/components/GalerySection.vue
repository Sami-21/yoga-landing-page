<template>
  <div
    class="min-h-screen w-screen flex flex-col items-center py-28 md:px-32 sm:px-16 px-8 relative"
  >
    <img
      src="@/assets/GaleryTopRight .png"
      alt=""
      class="absolute top-0 md:right-0 -right-10 md:scale-100 scale-75"
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
      class="absolute md:bottom-0 -bottom-4 md:left-0 -right-2 md:scale-100 scale-75 -scale-x-100"
    />
    <div class="lg:w-3/4 w-full mx-auto text-center px-16">
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
      class="grid gap-28 xl:grid-cols-3 lg:grid-cols-2 grid-cols-1 w-full min-h-fit mt-24 md:px-24 px-6"
    >
      <CardComponent ImageName="CardPic1.png" />
      <CardComponent ImageName="CardPic2.png" />
      <CardComponent ImageName="CardPic3.png" />
    </div>
  </div>
</template>

<script>
import CardComponent from "./CardComponent.vue";
export default {
  components: { CardComponent },
};
</script>

<style scoped></style>
