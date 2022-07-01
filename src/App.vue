<template>
  <v-app>
    <NavBar />
    <div class="mt-40">
      <BalanceSection />
    </div>
    <PregnantWomenSection />
    <Programs />
    <YogaBreathing />
    <PromotionSection />
    <GalerySection />
    <YogaTrainingShowSection />
  </v-app>
</template>

<script>
import NavBar from "./components/NavBar";
import BalanceSection from "./components/BalanceSection";
import PregnantWomenSection from "./components/PregnantWomenSection";
import Programs from "./components/3Programs";
import YogaBreathing from "./components/YogaBreathingSection";
import PromotionSection from "./components/PromotionSection";
import GalerySection from "./components/GalerySection";
import YogaTrainingShowSection from "./components/YogaTrainingShowSection";

export default {
  name: "App",

  components: {
    NavBar,
    BalanceSection,
    PregnantWomenSection,
    Programs,
    YogaBreathing,
    PromotionSection,
    GalerySection,
    YogaTrainingShowSection,
  },

  data: () => ({
    //
  }),
};
</script>
