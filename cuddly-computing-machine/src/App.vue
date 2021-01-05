<template>
  <div id="app">
    <Index />
  </div>
</template>

<script>
import Index from "./pages/index";
export default {
  name: "App",
  components: { Index },
};
</script>

<style lang="scss">
@import "@/design/index.scss";
</style>
