<template>
  <v-card tile class="mx-auto w-full CardContainer text-center" elevation="10">
    <v-img
      class="white--text imageContainer"
      height="300px"
      :src="require(`@/assets/${ImageName}`)"
    >
    </v-img>

    <v-card-text class="text--primary px-4 pb-6">
      <div class="text-gray-600 text-3xl pt-8 font-semibold mb-4">
        Facilis Gravida
      </div>

      <p class="text-xl text-gray-500">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem, harum!
      </p>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  props: {
    ImageName: String,
  },
};
</script>

<style scoped>

.imageContainer{
  background-size:cover;
}

.CardContainer:hover {
    transform: translateY(-35px) scale(1.1);
  }

@media (max-width: 767px) {
  .CardContainer:hover {
    transform: translateY(-35px);
  }
}

</style>
