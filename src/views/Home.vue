<template>
  <div class="home">
      <our-mission></our-mission>
      <how-it-works></how-it-works>
    </div>
</template>

<script>
// @ is an alias to /src
import OurMission from "@/components/OurMission.vue";
import HowItWorks from "@/components/HowItWorks";

export default {

  name: 'Home',
  components: {
    OurMission,
    HowItWorks
  }
}
</script>

<style scoped>
  .home{
    background: #19181D;
    width: 100%;
  }
</style>
