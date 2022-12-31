<script setup>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Home from "./views/Home.vue";
import SecondComp from "./components/secondComp.vue";
</script>

<template>
  <div class="w-full pb-4">
    <div class="pt-0.5">
      <!-- App header -->
      <Header />

      <!-- Home-->
      <Home />

      <!-- App footer -->
      <Footer />
    </div>
  </div>
</template>

<style scoped>
.text-header-gradient {
  background: rgb(57, 132, 244);
  background: linear-gradient(
    169.4deg,
    #3984f4 -6.01%,
    #0cd3ff 36.87%,
    #2f7cf0 78.04%,
    #0e65e8 103.77%
  );
}

.bg-blue-gradient,
.text-gradient {
  background: linear-gradient(136.91deg, #468ef9 -12.5%, #0c66ee 107.5%);
}
</style>
