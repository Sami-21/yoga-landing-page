<template>
  <div id="background" class="h-screen w-screen flex items-center gap-10">
    <div
      class="md:w-1/2 w-full h-full flex flex-col justify-center items-start pl-24"
    >
      <h1
        id="title"
        class="text-gray-600 font-bold leading-tight text-left tracking-wider mb-12"
      >
        Yoga Breathing or Pranayama
      </h1>
      <p class="text-2xl text-gray-500 leading-normal">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Distinctio,
        aliquam esse doloremque cum nesciunt alias minus blanditiis consequuntur
        facilis! Asperiores.
      </p>
      <v-btn
        color="#e8c8c3"
        width="250px"
        height="65px"
        class="mt-10 py-4 px-8"
        large
        elevation="0"
        ><span class="text-gray-600 text-2xl font-bold"
          >LEARN MORE
        </span></v-btn
      >
    </div>
    <div class="md:w-1/2 w-full h-full flex justify-center items-center">
      <div class="ImageContainer"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#title {
  font-size: 96px;
}
</style>
