<template>
  <div
    class="w-screen flex justify-center items-center relative overflow-hidden py-20"
  >
    <div class="lg:w-9/12 w-full text-center px-16">
      <h1
        class="lg:text-7xl md:text-6xl text-5xl tracking-wider font-bold mb-16 text-gray-600"
      >
        Get In Touch
      </h1>
      <p class="lg:text-3xl md:text-2xl text-xl mb-16 text-gray-500">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus
        perferendis dolorum asperiores maiores alias maxime laborum laudantium
        saepe soluta iure?
      </p>
      <form action="" class="mx-auto">
        <input
          class="w-full p-6 bg-white text-xl sm:text-3xl outline-0 text-inherit mb-10 placeholder:text-gray-300"
          type="text"
          name="name"
          placeholder="Your Name"
        />
        <input
          class="w-full p-6 bg-white text-xl sm:text-3xl outline-0 text-inherit mb-10 placeholder:text-gray-300"
          type="text"
          name="gender"
          placeholder="Gender"
        />
        <textarea
          class="w-full h-48 p-6 bg-white text-xl sm:text-3xl outline-0 text-inherit mb-10 placeholder:text-gray-300"
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
          ><span class="text-gray-600 text-2xl font-extrabold"
            >SEND MESSAGE</span
          ></v-btn
        >
      </form>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
input[type="text"],
textarea {
  background: #efefef;
  border: 3px solid #c6c6c6;
}
/* input[type="text"]::placeholder,
textarea::placeholder {
  background: #efefef;
  border: 3px solid #c6c6c6;
} */
</style>
