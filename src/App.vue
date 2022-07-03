<template>
  <v-app>
    <NavBar />
    <div class="md:mt-40 mt-24 overflow-hidden">
      <BalanceSection />
    </div>
    <PregnantWomenSection />
    <Programs />
    <YogaBreathing />
    <PromotionSection />
    <GalerySection />
    <YogaTrainingShowSection />
    <ContactSection />
    <Footer />
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
import ContactSection from "./components/ContactSection";
import Footer from "./components/FooterSection";

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
    ContactSection,
    Footer,
  },

  data: () => ({
    //
  }),
};
</script>
