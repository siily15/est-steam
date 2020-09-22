<template>
  <Primarynav />
  <Secendarynav />
</template>

<script>
import Primarynav from "./components/Primarynav.vue";
import Secendarynav from "./components/Secendarynav.vue";

export default {
  name: "App",
  components: {
    Primarynav,
    Secendarynav,
  },
};
</script>
