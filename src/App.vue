<template>
  <div id="app">
    <HeaderBar />
    <!-- <div class="main-section content-title-group">
      <h2 class="title">Nannies</h2>
      <div>We'll start here</div>
    </div> -->
    <div class="main-section columns">
      <main class="column">
        <Nannies />
      </main>
    </div>
  </div>
</template>

<script>
import HeaderBar from "@/components/header-bar";
import Nannies from "@/components/nannies";

export default {
  name: "App",
  components: { HeaderBar, Nannies },
};
</script>

<style lang="scss">
@import "@/design/index.scss";
</style>
