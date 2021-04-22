<template>
  <div class="home">
      <our-mission></our-mission>
      <how-it-works></how-it-works>
      <team></team>
      <carusel-work-with-us></carusel-work-with-us>
      <points></points>
    </div>
</template>

<script>
// @ is an alias to /src
import OurMission from "@/components/OurMission.vue";
import HowItWorks from "@/components/HowItWorks";
import Team from "../components/Team";
import CaruselWorkWithUs from "../components/CaruselWorkWithUs";
import Points from "../components/Points";

export default {

  name: 'Home',
  components: {
    OurMission,
    HowItWorks,
    Team,
    CaruselWorkWithUs,
    Points,
  }
}
</script>

<style scoped>
  .home{
    background: #19181D;
    width: 100%;
  }
</style>
