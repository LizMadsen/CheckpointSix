<template>
  <router-view />
</template>

<script>
import { computed } from "vue";
import { AppState } from "./AppState";
export default {
  name: "App",
  setup() {
    return {
      AppState: computed(() => AppState),
    };
  },
};
</script>

<style lang="scss">
@import "./assets/scss/main.scss";
</style>
