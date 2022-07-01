<template>
  <div class="h-screen w-screen flex items-center gap-10 border-2 border-solid">
    <div class="md:w-1/2 w-full h-full px-12 flex justify-center"></div>
    <div
      class="md:w-1/2 w-full h-full flex flex-col justify-center items-start pr-24"
    >
      <h1
        id="title"
        class="text-gray-600 font-bold leading-tight text-left tracking-wider mb-20"
      >
        Join Now and Get 50% Off
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
        class="mt-20 py-4 px-8"
        large
        elevation="0"
        ><span class="text-gray-600 text-3xl font-bold">JOIN NOW</span></v-btn
      >
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
