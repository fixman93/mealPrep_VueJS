<template>
  <v-app>
    <app-navigation></app-navigation>
    <home-hero></home-hero>
    <home-details></home-details>
    <home-plans></home-plans>
  </v-app>
</template>

<script>
import AppNavigation from "@/components/AppNavigation";
import HomeHero from "@/components/HomeHero";
import HomeDetails from "@/components/HomeDetails";
import HomePlans from "@/components/HomePlans";
export default {
  name: "App",
  components: {
    AppNavigation,
    HomeHero,
    HomeDetails,
    HomePlans
  }
};
</script>

<style>
</style>