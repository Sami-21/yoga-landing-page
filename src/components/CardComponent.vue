<template>
  <v-card tile class="mx-auto w-full CardContainer text-center" elevation="15">
    <v-img
      class="white--text align-end"
      height="400px"
      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
    >
    </v-img>

    <v-card-text class="text--primary px-4">
      <div class="text-gray-600 text-5xl pt-8 font-semibold mb-4">
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
    CardTitle: String,
  },
};
</script>

<style scoped>
.CardContainer {
  height: 615px;
}

#textContainer {
  background: #2c2c2c;
}
</style>
