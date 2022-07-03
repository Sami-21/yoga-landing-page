<template>
  <div
    class="w-screen flex justify-center items-center relative overflow-hidden py-20"
  >
    <img
      data-aos="fade-down-left"
      src="@/assets/GaleryTopRight .png"
      alt=""
      class="absolute top-0 md:right-0 -right-10 md:scale-100 scale-75"
    />
    <img
      data-aos="fade-up-left"
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
      data-aos="fade-down-right"
      src="@/assets/GaleryTopLeft.png"
      alt=""
      class="absolute top-32 md:left-12 left-4 md:scale-100 scale-75"
    />
    <img
      data-aos="fade-up-right"
      src="@/assets/GaleryBottomLeft.png"
      alt="flower"
      class="absolute md:bottom-0 -bottom-4 md:left-0 -right-2 md:scale-100 scale-75 -scale-x-100"
    />
    <div data-aos="fade-down" class="lg:w-9/12 w-full text-center px-16">
      <h1
        class="2xl:text-8xl xl:text-6xl lg:text-5xl md:text-4xl text-3xl tracking-wider font-bold mb-16 text-gray-600"
      >
        Get In Touch
      </h1>
      <p class="xl:text-2xl md:text-xl mb-16 text-gray-500">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus
        perferendis dolorum asperiores maiores alias maxime laborum laudantium
        saepe soluta iure?
      </p>

      <form data-aos="fade-up" class="mx-auto relative z-50">
        <input
          class="w-full md:p-6 p-4 bg-white text-xl sm:text-3xl outline-0 text-inherit mb-10 placeholder:text-gray-300"
          type="text"
          name="name"
          placeholder="Your Name"
        />
        <input
          class="w-full md:p-6 p-4 bg-white text-xl sm:text-3xl outline-0 text-inherit mb-10 placeholder:text-gray-300"
          type="text"
          name="gender"
          placeholder="Gender"
        />
        <textarea
          class="w-full h-48 md:p-6 p-4 bg-white text-xl sm:text-3xl outline-0 text-inherit mb-10 placeholder:text-gray-300"
          name="message"
          placeholder="Message"
        />
        <v-btn
          color="#e8c8c3"
          width="250px"
          height="65px"
          class="mt-8 py-4 px-8"
          large
          elevation="0"
          ><span
            class="text-gray-600 xl:text-2xl lg:text-xl md:text-lg font-extrabold"
            >SEND MESSAGE</span
          ></v-btn
        >
      </form>
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
form {
  z-index: 999;
}

input[type="text"],
textarea {
  background: #efefef;
  border: 3px solid #c6c6c6;
}
</style>
