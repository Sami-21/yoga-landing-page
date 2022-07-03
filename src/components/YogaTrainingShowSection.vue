<template>
  <div
    id="ShowReel"
    class="w-screen flex lg:flex-row flex-col-reverse items-center justify-between gap-10 lg:py-40 py-20"
  >
    <div
      class="lg:w-1/2 w-full h-full lg:pl-28 lg:pr-12 px-10 flex justify-center items-center"
    >
      <div
        class="videoContainer bg-black w-full flex justify-center items-center"
      >
        <!-- <v-icon dark size="225">mdi-play</v-icon> -->
      </div>
    </div>
    <div
      class="lg:w-1/2 w-full h-full flex flex-col justify-center lg:items-start items-center lg:pr-40 px-8"
    >
      <h1
        class="2xl:text-8xl xl:text-6xl lg:text-5xl md:text-4xl text-3xl text-gray-600 font-bold leading-tight tracking-wider mb-10"
      >
        Yoga Training Video Showreel
      </h1>
      <p class="xl:text-2xl md:text-xl text-gray-500">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Distinctio,
        aliquam esse doloremque cum nesciunt alias minus blanditiis consequuntur
        facilis! Asperiores.
      </p>
      <div class="md:mt-20 mt-10">
        <v-btn
          color="rgb(75 85 99)"
          tile
          height="60"
          width="20"
          class="md:mr-16 mr-8"
        >
          <v-icon large color="#fff">mdi-facebook</v-icon>
        </v-btn>
        <v-btn
          color="rgb(75 85 99)"
          tile
          height="60"
          width="20"
          class="md:mr-16 mr-8"
        >
          <v-icon large color="#fff">mdi-instagram</v-icon>
        </v-btn>
        <v-btn color="rgb(75 85 99)" tile height="60" width="20" class="">
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
  overflow: hidden;
}
.videoContainer {
  height: 550px;
  box-shadow: 10px 10px 36px 0px rgba(0, 0, 0, 0.75);
  background-image: url("@/assets/ShowReel.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
}

@media (max-width: 1024px) {
  h1,
  p {
    text-align: center;
  }
  .videoContainer {
    height: 350px;
  }
}
</style>
