<script>
import { RouterLink, RouterView } from "vue-router";
import AppHeader from "@/components/AppHeader.vue";
import AppSlider from "@/components/AppSlider.vue";
import AppServiceArea from "@/components/AppServiceArea.vue";
import AppPortfolio from "@/components/AppPortfolio.vue";
import AppResume from "@/components/AppResume.vue";
import AppContact from "@/components/AppContact.vue";
import AppFooter from "@/components/AppFooter.vue";
import AppClient from "@/components/AppClient.vue";
import AppPricingArea from "@/components/AppPricingArea.vue";
import SinglePortfolio from "@/components/SinglePortfolio.vue";
import SingleBlog from "@/components/SingleBlog.vue";
import AppBlog from "@/components/AppBlog.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppSlider,
    AppServiceArea,
    AppPortfolio,
    AppResume,
    AppContact,
    AppFooter,
    AppPricingArea,
    AppClient,
    SinglePortfolio,
    SingleBlog,
    AppBlog,
  },
  mounted() {
    this.initParticleJS();
  },
  methods: {
    initParticleJS() {
      // eslint-disable-next-line no-undef
      particlesJS(
        "particles-js",

        {
          particles: {
            number: {
              value: 50,
              density: {
                enable: true,
                value_area: 800,
              },
            },
            color: {
              value: ["#ff014f"],
            },
            shape: {
              type: "circle",
              stroke: {
                width: 0,
                color: "#000000",
              },
              polygon: {
                nb_sides: 4,
              },
              image: {
                src: "img/github.svg",
                width: 100,
                height: 100,
              },
            },
            opacity: {
              value: 0.8,
              random: true,
              anim: {
                enable: false,
                speed: 1,
                opacity_min: 0.1,
                sync: false,
              },
            },
            size: {
              value: 4,
              random: true,
              anim: {
                enable: false,
                speed: 40,
                size_min: 0.1,
                sync: false,
              },
            },
            line_linked: {
              enable: false,
              distance: 150,
              color: "#ffffff",
              opacity: 0.4,
              width: 1,
            },
            move: {
              enable: true,
              speed: 6,
              direction: "none",
              random: false,
              straight: false,
              out_mode: "out",
              attract: {
                enable: false,
                rotateX: 600,
                rotateY: 1200,
              },
            },
          },
          interactivity: {
            detect_on: "canvas",
            events: {
              onhover: {
                enable: true,
                mode: "repulse",
              },
              onclick: {
                enable: true,
                mode: "push",
              },
              resize: true,
            },
            modes: {
              grab: {
                distance: 400,
                line_linked: {
                  opacity: 1,
                },
              },
              bubble: {
                distance: 800,
                size: 40,
                duration: 2,
                opacity: 8,
                speed: 3,
              },
              repulse: {
                distance: 200,
              },
              push: {
                particles_nb: 4,
              },
              remove: {
                particles_nb: 2,
              },
            },
          },
          retina_detect: true,
          config_demo: {
            hide_card: false,
            background_color: "#b61924",
            background_image: "",
            background_position: "50% 50%",
            background_repeat: "no-repeat",
            background_size: "cover",
          },
        }
      );
    },
  },
};
</script>

<template>
  <!-- Header area -->
  <app-header />

  <main class="page-wrapper-two">
    <!-- start slider area -->
    <app-slider />

    <!-- Start Service Area -->
    <app-service-area />

    <!-- Start Portfolio Area -->
    <app-portfolio />

    <!-- Start Resume Area -->
    <app-resume />

    <!-- Start Client Area -->
    <app-client />

    <!-- Pricing Area -->
    <app-pricing-area />

    <!-- Start News Area -->
    <app-blog />
    <!-- ENd Mews Area -->

    <!-- Start Contact section -->
    <app-contact />

    <!-- Start Footer Area -->
    <app-footer />

    <!-- modal area -->
    <!-- Modal Portfolio Body area Start -->
    <single-portfolio />

    <!-- Modal Blog Body area Start -->
    <single-blog />

    <!-- Back to  top Start -->
    <div class="backto-top">
      <div>
        <i data-feather="arrow-up"></i>
        <!-- <vue-feather class="" type="arrow-up"></vue-feather> -->
      </div>
    </div>
    <!-- Back to top end -->
  </main>
</template>

<style scoped></style>
