<template>
  <v-hover>
    <template v-slot:default="{ hover }">
      <v-card
        tile
        class="mx-auto w-full CardContainer text-center"
        :elevation="hover ? 20 : 10"
      >
        <v-img
          class="white--text align-end"
          height="350px"
          :src="require(`@/assets/${ImageName}`)"
        >
        </v-img>

        <v-card-text class="text--primary px-4 pb-6">
          <div class="text-gray-600 text-3xl pt-8 font-semibold mb-4">
            Facilis Gravida
          </div>

          <p class="text-xl text-gray-500">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem,
            harum!
          </p>
        </v-card-text>
      </v-card>
    </template>
  </v-hover>
</template>

<script>
export default {
  props: {
    ImageName: String,
  },
};
</script>

<style scoped>
.CardContainer {
  height: fit-content;
  transition-duration: 1000ms;
}
.CardContainer:hover {
  transform: translateY(-30px) scale(1.1);
}

#textContainer {
  background: #2c2c2c;
}
</style>
