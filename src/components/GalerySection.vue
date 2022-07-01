<template>
  <section
    id="DanceTour"
    class="min-h-screen w-screen flex flex-col items-center py-28 md:px-32 sm:px-16 px-8"
  >
    <div class="lg:w-3/4 w-full mx-auto text-center px-16">
      <h1
        class="text-gray-600 lg:text-8xl md:text-7xl text-6xl font-bold mb-16"
      >
        Galery
      </h1>
      <p class="text-4xl text-gray-500 leading-normal">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam
        atque sed nam consequatur corrupti.
      </p>
    </div>
    <div
      class="grid gap-40 xl:grid-cols-3 lg:grid-cols-2 grid-cols-1 w-full min-h-fit mt-24 px-24"
    >
      <CardComponent CardTitle="AMERICA" ImageName="images.png" />
      <CardComponent CardTitle="ASIA" ImageName="M2.jpeg" />
      <CardComponent CardTitle="AUSTRALIA" ImageName="M1.jpeg" />
    </div>
  </section>
</template>

<script>
import CardComponent from "./CardComponent.vue";
export default {
  components: { CardComponent },
};
</script>

<style scoped></style>
