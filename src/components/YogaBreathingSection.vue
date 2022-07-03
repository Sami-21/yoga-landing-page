<template>
  <div
    class="min-h-screen w-screen flex md:flex-row flex-col-reverse items-center gap-10 py-16 p-8 relative overflow-hidden"
  >
    <img
      src="@/assets/breathTopLeftFlower.png"
      alt="flower"
      class="absolute md:top-0 -top-4 md:left-0 -left-4 md:scale-100 scale-75"
    />
    <img
      src="@/assets/breathBottomLeftFlower.png"
      alt="flower"
      class="absolute md:bottom-0 -bottom-4 md:left-0 -right-2 md:scale-100 scale-75 -scale-x-100"
    />
    <div
      class="md:w-1/2 w-full h-full flex flex-col justify-center md:items-start items-center md:pl-24 md:px-0 px-12"
    >
      <h1
        id="title"
        class="text-gray-600 2xl:text-8xl xl:text-6xl lg:text-5xl md:text-4xl text-3xl font-bold leading-tight tracking-wider md:mb-20 mb-12 textContainer"
      >
        Yoga Breathing or Pranayama
      </h1>
      <p
        class="xl:text-2xl md:text-xl text-gray-500md:text-left leading-normal"
      >
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
          >LEARN MORE
        </span></v-btn
      >
    </div>
    <div
      id="Background"
      class="md:w-1/2 sm:w-full sm:h-full w-72 h-72 flex justify-center items-center"
    ></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#Background {
  background-image: url("@/assets/BreathWomen.png");
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center center;
}

@media (max-width: 768px) {
  h1,
  p {
    text-align: center;
  }
  .textContainer {
    align-items: center;
  }
}
</style>
