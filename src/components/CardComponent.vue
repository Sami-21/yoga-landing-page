<template>
  <v-hover>
    <template v-slot:default="{ hover }">
      <v-card
        tile
        class="mx-auto w-full CardContainer text-center duration-200"
        :elevation="hover ? 20 : 10"
      >
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
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem,
            harum!
          </p>
        </v-card-text>
      </v-card>
    </template>
  </v-hover>
</template>

<script>
export default {};
</script>

<style scoped>
.CardContainer {
  height: 650px;
}

#textContainer {
  background: #2c2c2c;
}
</style>
