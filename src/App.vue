<template>
  <v-app>
    <v-main>
      <!-- Header area -->
      <app-header />
      <!-- <gpt-header /> -->

      <router-view />

      <!-- Start Footer Area -->
      <app-footer />
    </v-main>
  </v-app>
</template>

<script>
import AppHeader from "@/components/AppHeader.vue";
import AppFooter from "@/components/AppFooter.vue";
import GptHeader from "@/components/GptHeader.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppFooter,
    GptHeader,
  },
};
</script>
