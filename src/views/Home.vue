<template>
  <div class="container mx-auto mt-10">
    <div class="mb-5 sm:mb-8 pb-24">
      <section
        class="relative max-w-screen-xl px-4 sm:px-8 mx-auto grid grid-cols-12 gap-x-6 overflow-hidden"
      >
        <!-- Banner left contents -->
        <div
          class="col-span-12 lg:col-span-6 mt-12 xl:mt-10 space-y-4 sm:space-y-6 px-6 text-center sm:text-left"
        >
          <span
            data-aos="fade-right"
            data-aos-delay="200"
            class="text-base text-gradient font-semibold uppercase p-1 rounded-2xl"
            >Sign Up Today</span
          >
          <h1
            data-aos="fade-right"
            data-aos-delay="200"
            class="text-[2.5rem] sm:text-5xl xl:text-6xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10"
          >
            Get Daily
            <span class="text-header-gradient">Crypto Insights</span> and
            Summaries
          </h1>
          <p
            class="font-general-medium mt-2 text-lg sm:text-xl xl:text-2xl text-center sm:text-left leading-none text-gray-400"
          >
            Stay up-to-date on the latest crypto developments and discover the
            hottest coins on the market with our daily newsletter!
          </p>
        </div>

        <div class="hidden sm:block col-span-12 lg:col-span-6">
          <div class="w-full">
            <img
              data-aos="fade-up"
              data-aos-delay="200"
              src="../assets/icons/hero-image.webp"
              class="-mt-4"
              alt=""
            />
          </div>
        </div>

        <img
          data-aos="fade-up"
          data-aos-delay="200"
          src="../assets/icons/pattern/ellipse-1.png"
          class="hidden sm:block absolute bottom-12 xl:bottom-16 left-4 xl:left-0 w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="200"
          src="../assets/icons/pattern/ellipse-2.png"
          class="hidden sm:block absolute top-4 sm:top-10 right-64 sm:right-96 xl:right-[32rem] w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="200"
          src="../assets/icons/pattern/ellipse-3.png"
          class="hidden sm:block absolute bottom-56 right-24 w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="200"
          src="../assets/icons/pattern/star.png"
          class="hidden sm:block absolute top-20 sm:top-28 right-16 lg:right-0 lg:left-[30rem] w-8"
        />
      </section>
      <div class="flex items-center justify-center">
        <div class="led" v-for="n in 3" :key="n" />
      </div>
    </div>
  </div>

  <section
    class="max-w-screen-xl mx-2 sm:mx-auto px-4 sm:px-6 lg:px-0 py-6 pb-20 sm:py-8 rounded-[2.25rem] sm:rounded-xl bg-gray-100 shadow-lg sm:shadow-md transform lg:-translate-y-12"
  >
    <br />
    <br />
    <img
      data-aos="fade-up"
      data-aos-delay="200"
      src="../assets/icons/pattern/ellipse-3.png"
      class="hidden sm:block absolute bottom-56 right-24 w-6"
    />
    <img
      data-aos="fade-up"
      data-aos-delay="200"
      src="../assets/icons/pattern/star.png"
      class="hidden sm:block absolute top-20 sm:top-28 right-16 lg:right-0 lg:left-[30rem] w-8"
    />

    <section class="w-full my-16 bg-">
      <div
        class="relative max-w-screen-xl px-4 sm:px-8 mx-auto grid grid-cols-12 gap-x-6 overflow-hidden"
      >
        <div
          data-aos="fade-up"
          data-aos-delay="200"
          class="col-span-12 lg:col-span-6"
        >
          <div class="w-full">
            <img src="../assets/images/bitcoin.png" class="w-full" alt="" />
          </div>
        </div>
        <div
          data-aos="fade-up"
          data-aos-delay="200"
          class="col-span-12 lg:col-span-6 px-4 sm:px-6 mt-8"
        >
          <span
            class="text-base text-gradient font-semibold uppercase mb-4 sm:mb-2"
            >Wait!</span
          >
          <h2 class="text-3xl sm:text-4xl font-semibold mb-10 sm:mb-6">
            But that's not all.
          </h2>
          <div class="space-y-4 sm:space-y-2">
            <div class="">
              <div class="bg-gray-100 rounded flex p-4 h-full items-center">
                <svg
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="3"
                  class="text-indigo-500 w-6 h-6 flex-shrink-0 mr-4"
                  viewBox="0 0 24 24"
                >
                  <path d="M22 11.08V12a10 10 0 11-5.93-9.14"></path>
                  <path d="M22 4L12 14.01l-3-3"></path>
                </svg>
                <span class="title-font font-medium"
                  >Stay current on crypto industry news</span
                >
              </div>
            </div>
            <div class="">
              <div class="bg-gray-100 rounded flex p-4 h-full items-center">
                <svg
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="3"
                  class="text-indigo-500 w-6 h-6 flex-shrink-0 mr-4"
                  viewBox="0 0 24 24"
                >
                  <path d="M22 11.08V12a10 10 0 11-5.93-9.14"></path>
                  <path d="M22 4L12 14.01l-3-3"></path>
                </svg>
                <span class="title-font font-medium"
                  >Daily summary of top coins, news, events</span
                >
              </div>
            </div>
            <div class="">
              <div class="bg-gray-100 rounded flex p-4 h-full items-center">
                <svg
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="3"
                  class="text-indigo-500 w-6 h-6 flex-shrink-0 mr-4"
                  viewBox="0 0 24 24"
                >
                  <path d="M22 11.08V12a10 10 0 11-5.93-9.14"></path>
                  <path d="M22 4L12 14.01l-3-3"></path>
                </svg>
                <span class="title-font font-medium"
                  >Stay informed, ahead in crypto world</span
                >
              </div>
            </div>
            <div class="">
              <div class="bg-gray-100 rounded flex p-4 h-full items-center">
                <svg
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="3"
                  class="text-indigo-500 w-6 h-6 flex-shrink-0 mr-4"
                  viewBox="0 0 24 24"
                >
                  <path d="M22 11.08V12a10 10 0 11-5.93-9.14"></path>
                  <path d="M22 4L12 14.01l-3-3"></path>
                </svg>
                <span class="title-font font-medium"
                  >Access condensed summaries of crypto news</span
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </section>
  <br />
  <br />
  <!--Explanation Section-->
  <section class="w-full my-36">
    <div
      class="relative max-w-screen-xl px-4 sm:px-8 mx-auto grid grid-cols-12 gap-x-6 overflow-hidden"
      data-aos="fade-down"
      data-aos-delay="200"
    >
      <div class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6 mt-20">
        <h2 class="text-4xl font-semibold">
          Nope, not <span class="text-header-gradient">Finished</span>
        </h2>
        <p class="text-xl">
          Our website also provides condensed <strong>summaries</strong> of the
          latest crypto news from various sources, allowing you to quickly get
          an
          <span class="text-sky-700">overview of all industry</span> happenings
          and make informed decisions.
        </p>
        <button
          class="w-full sm:max-w-[240px] px-6 py-2 bg-inherit text-gradient border border-[#0c66ee] text-base rounded-2xl"
        >
          Join the waitlist
        </button>
      </div>
      <div class="col-span-12 lg:col-span-7">
        <div class="w-full">
          <img
            src="../assets/undraw_crypto_portfolio.svg"
            class="w-[95%]"
            alt=""
          />
        </div>
      </div>
    </div>
  </section>
  <br />
  <br />
</template>

<script setup>
import { onMounted } from "vue";
import AOS from "aos";

import LandingListItem from "../components/ListItem.vue";

onMounted(() => {
  AOS.init();
});
</script>
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

.bg-blue-gradient,
.text-gradient {
  background: linear-gradient(136.91deg, #468ef9 -12.5%, #0c66ee 107.5%);
}
@keyframes blink {
  50% {
    opacity: 0;
  }
}

.led {
  width: 20px;
  height: 20px;
  background-color: blue;
  border-radius: 50%;
  animation: blink 1s infinite;
}

.led:nth-child(1) {
  animation-delay: 0s;
}

.led:nth-child(2) {
  animation-delay: 0.5s;
}

.led:nth-child(3) {
  animation-delay: 1s;
}

hr.style11 {
  height: 6px;
  background: url(http://ibrahimjabbari.com/images/hr-11.png) repeat-x 0 0;
  border: 0;
}
</style>
