<template>
  <div class="home">
    <app-header></app-header>
    <intro></intro>
    <features></features>
    <productive></productive>
    <team></team>
    <newsletter></newsletter>
    <page-footer></page-footer>
  </div>
</template>

<script>
import AppHeader from "@/cmps/AppHeader.vue";
import Intro from "@/cmps/Intro";
import Features from "@/cmps/Features";
import Productive from "@/cmps/Productive.vue";
import Team from "@/cmps/Team.vue";
import Newsletter from "@/cmps/Newsletter.vue";
import PageFooter from "@/cmps/PageFooter.vue";

export default {
  name: "Home",
  components: {
    AppHeader,
    Intro,
    Features,
    Productive,
    Team,
    Newsletter,
    PageFooter,
  },
};
</script>