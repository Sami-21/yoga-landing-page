<template>
  <div
    class="w-screen grid xl:grid-cols-3 lg:grid-cols-2 grid-cols-1 gap-20 lg:px-20 px-10 py-24 text-center overflow-hidden"
  >
    <div
      data-aos="zoom-in-up"
      class="w-full h-96 flex justify-center items-center flex-col"
    >
      <img src="@/assets/Program1.png" alt="Program1" />
      <div>
        <h1
          class="text-gray-600 text-3xl font-bold leading-tight tracking-wider"
        >
          Program 1
        </h1>
        <p class="text-2xl text-gray-500 leading-normal">
          Lorem ipsum dolor sit.
        </p>
      </div>
    </div>
    <div
      data-aos="zoom-in-up"
      class="w-full h-96 flex justify-center items-center flex-col"
    >
      <img src="@/assets/Program2.png" alt="Program1" />

      <div>
        <h1
          class="text-gray-600 text-3xl font-bold leading-tight tracking-wider"
        >
          Program 2
        </h1>
        <p class="text-2xl text-gray-500 leading-normal">
          Lorem ipsum dolor sit.
        </p>
      </div>
    </div>
    <div
      data-aos="zoom-in-up"
      class="w-full h-96 flex justify-center items-center flex-col"
    >
      <img src="@/assets/Program3.png" alt="Program1" />
      <div>
        <h1
          class="text-gray-600 text-3xl font-bold leading-tight tracking-wider"
        >
          Program 3
        </h1>
        <p class="text-2xl text-gray-500 leading-normal">
          Lorem ipsum dolor sit.
        </p>
      </div>
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

<style></style>
