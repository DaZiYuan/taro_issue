<template>
  <view class="index">
    {{ config.title }}
    <!-- <NumberDisplay /> -->
    <!-- <NumberSubmit /> -->
  </view>
</template>

<script lang="ts">
// import NumberDisplay from "../../components/NumberDisplay.vue";
// import NumberSubmit from "../../components/NumberSubmit.vue";
import { config } from "@/config/data";
export default {
  name: "index-page",
  data() {
    return {
      config,
    };
  },
  components: {
    // NumberDisplay,
    // NumberSubmit,
  },
};
</script>

<style>
.index {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
