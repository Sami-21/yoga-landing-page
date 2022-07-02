<template>
  <div
    id="ShowReel"
    class="w-screen flex items-center justify-between gap-10 py-44"
  >
    <div
      class="md:w-1/2 w-full h-full pl-28 pr-12 flex justify-center items-center"
    >
      <div class="videoContainer bg-black w-full"></div>
    </div>
    <div
      class="md:w-1/2 w-full h-full flex flex-col justify-center items-start pr-40"
    >
      <h1
        class="text-7xl text-gray-600 font-bold leading-tight text-left tracking-wider mb-10 pr-20"
      >
        Yoga Training Video Showreel
      </h1>
      <p class="text-2xl text-gray-500">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Distinctio,
        aliquam esse doloremque cum nesciunt alias minus blanditiis consequuntur
        facilis! Asperiores.
      </p>
      <div class="mt-20">
        <v-btn color="rgb(75 85 99)" tile height="60" width="20" class="mr-16">
          <v-icon large color="#fff">mdi-facebook</v-icon>
        </v-btn>
        <v-btn color="rgb(75 85 99)" tile height="60" width="20" class="mr-16">
          <v-icon large color="#fff">mdi-instagram</v-icon>
        </v-btn>
        <v-btn color="rgb(75 85 99)" tile height="60" width="20" class="mr-16">
          <v-icon large color="#fff">mdi-twitter</v-icon>
        </v-btn>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#ShowReel {
  background-color: #e5ccc6;
  color: #817f7c;
}
.videoContainer {
  height: 550px;
  box-shadow: 10px 10px 36px 0px rgba(0, 0, 0, 0.75);
}
</style>
