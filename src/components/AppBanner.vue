<script>
import AOS from "aos";

export default {
  name: "Home",
  data: () => {
    return {
      theme: "",
    };
  },
  created() {
    this.theme = localStorage.getItem("theme") || "light";
  },
  mounted() {
    this.theme = localStorage.getItem("theme") || "light";
    AOS.init();
  },
  updated() {},
  methods: {},
};
</script>

<template>
  <section
    class="flex flex-col sm:justify-between items-center sm:flex-row mt-12 sm:mt-10"
  >
    <!-- Banner left contents -->
    <div class="w-full md:w-1/3 text-left">
      <h1
        data-aos="fade-right"
        data-aos-once="true"
        class="text-[2.5rem] sm:text-5xl xl:text-6xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10"
      >
        The World's
        <span class="text-header-gradient">Fastest Growing</span> Crypto Web App
      </h1>
      <p
        class="font-general-medium mt-2 text-lg sm:text-xl xl:text-2xl text-center sm:text-left leading-none text-gray-400"
      >
        Stay up-to-date on the latest crypto developments and discover the
        hottest coins on the market with our daily newsletter!
      </p>
    </div>

    <!-- Banner right illustration -->
    <div class="w-full md:w-2/3 text-right float-right">
      <img
        v-if="theme === 'light'"
        src="../assets/images/crypto-icon.png"
        alt="Developer"
      />
    </div>
  </section>
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
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
