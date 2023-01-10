<template>
  <div>
    <div v-if="showModal" class="modal-overlay">
      <div class="modal-content">
        <iframe
          src="https://gryhkn.substack.com/embed"
          width="480"
          height="320"
          style="border: 1px solid #eee; background: white"
          frameborder="0"
          scrolling="no"
        ></iframe>
        <button @click="closeM()">Close</button>
      </div>
    </div>
  </div>

  <!-- Header -->

  <nav id="navbar" class="w-full text-neutral-800">
    <!-- Button justify end  -->
    <div class="flex justify-end max-w-screen-xl px-8 mx-auto lg:flex-row py-4">
      <div class="flex items-end justify-end">
        <div class="flex items-end justify-end">
          <button
            class="px-8 xl:px-10 py-3 mt-2 bg-gradient-to-r from-[#468ef9] to-[#0c66ee] text-white rounded-2xl"
            @click="showM()"
          >
            Sign Up
          </button>
        </div>
      </div>
    </div>
  </nav>
  <!-- End Header -->

  <div class="container mx-auto mt-10 max-w-screen-xl">
    <div class="mb-5 sm:mb-8 pb-24">
      <section
        class="px-4 sm:px-8 mx-auto grid grid-cols-6 gap-x-6 overflow-hidden"
      >
        <!-- Banner left contents -->
        <div
          class="col-span-12 lg:col-span-6 mt-12 xl:mt-10 space-y-2 sm:space-y-6 px-6 text-center sm:text-left"
        >
          <span
            data-aos="fade-right"
            data-aos-delay="200"
            class="rounded-2xl p-2 text-white bg-blue-gradient"
            >What?</span
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
      <!-- <div class="flex items-center justify-center">
        <div class="led" v-for="n in 3" :key="n" />
      </div> -->
    </div>
  </div>

  <section
    class="max-w-screen-xl mx-auto w-full text-center sm:px-6 px-4 py-6 sm:py-8 rounded-2xl bg-gray-100 shadow-lg sm:shadow-md"
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
        class="max-w-screen-xl px-4 sm:px-8 mx-auto grid grid-cols-12 gap-x-6 overflow-hidden"
      >
        <div
          data-aos="fade-up"
          data-aos-delay="200"
          class="col-span-12 lg:col-span-6"
        >
          <div class="w-full">
            <img
              src="../assets/images/crypto-icon3.png"
              class="w-full"
              alt=""
            />
          </div>
        </div>

        <div
          data-aos="fade-up"
          data-aos-delay="200"
          class="col-span-12 lg:col-span-6 px-4 sm:px-6 mt-8"
        >
          <span
            class="text-base text-gradient font-semibold uppercase sm:mb-2 text-white p-2 rounded-xl"
            >Wait!
          </span>
          <h2 class="text-3xl sm:text-4xl font-semibold mb-4 sm:mb-2 mt-1">
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
  <!--Explanation Section-->
  <section class="w-full my-12 sm:my-6">
    <div
      class="max-w-screen-xl px-4 sm:px-8 mx-auto grid grid-cols-12 gap-x-6 overflow-hidden"
      data-aos="fade-up"
      data-aos-delay="200"
    >
      <div
        class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6 mt-20 sm:mb-2"
      >
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
          class="w-full sm:max-w-[240px] sm:mb-2 px-6 py-2 text-white bg-inherit text-gradient border border-[#0c66ee] text-base rounded-2xl"
          @click="showM()"
        >
          Join the waitlist
        </button>
      </div>
      <div class="col-span-12 lg:col-span-7 mt-4">
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
  <section
    class="bg-trading-tools max-w-full sm:mx-4 xl:mx-10 my-24 shadow-2xl sm:rounded-2xl overflow-hidden drop-shadow-2xl"
  >
    <div
      class="w-full py-16 flex flex-col items-center sm:flex-col sm:items-center sm:justify-center max-w-screen-xl mx-auto"
    >
      <h2
        data-aos="flip-down"
        data-aos-delay="300"
        class="text-3xl sm:text-4xl font-semibold text-center"
      >
        Get started in just a few minutes
      </h2>
      <div
        data-aos="flip-up"
        data-aos-delay="300"
        class="w-full flex flex-col lg:flex-row items-center justify-between space-y-12 lg:space-y-0 px-4 xl:px-10 mt-16 sm:mt-8"
      >
        <div
          class="max-w-[280px] xl:max-w-[363px] space-y-6 sm:space-y-3 text-center"
        >
          <img
            src="../assets/icons/getting-started/sign-up.png"
            class="max-w-[245px] mx-auto"
            alt=""
          />
          <h3 class="text-xl text-neutral-800 font-semibold">Sign Up</h3>
          <p class="text-sm text-gray-700 leading-relaxed">
            Sign up for free to CryptoInsight.
          </p>
        </div>
        <div
          class="max-w-[280px] xl:max-w-[363px] space-y-6 sm:space-y-3 text-center"
        >
          <img
            src="../assets/icons/getting-started/fund.png"
            class="max-w-[245px] mx-auto"
            alt=""
          />
          <h3 class="text-xl text-neutral-800 font-semibold">Get Insights</h3>
          <p class="text-sm text-gray-700 leading-relaxed">
            Don't forget to check your email every evening. Everything about
            crypto, in just a few sentences.
          </p>
        </div>
        <div
          class="max-w-[280px] xl:max-w-[363px] space-y-6 sm:space-y-3 text-center"
        >
          <img
            src="../assets/icons/getting-started/buy-crypto.png"
            class="max-w-[245px] mx-auto"
            alt=""
          />
          <h3 class="text-xl text-neutral-800 font-semibold">
            Don't Lose Money
          </h3>
          <p class="text-sm text-gray-700 leading-relaxed">
            Keep track of the industry and stay up to date. This way you won't
            lose money. On the contrary, you'll earn more.
          </p>
        </div>
        <img
          src="../assets/icons/getting-started/arrow.png"
          class="hidden lg:inline-block absolute top-32 left-64 xl:left-[22rem] w-24 xl:w-[9.5rem]"
          alt=""
        />
        <img
          src="../assets/icons/getting-started/arrow.png"
          class="hidden lg:inline-block absolute top-32 right-64 xl:right-[22rem] w-24 xl:w-[9.5rem]"
          alt=""
        />
      </div>
    </div>
  </section>
  <div
    class="flex items-center justify-center my-auto sm:flex-col mx-auto mb-10 sm:flex sm:items-center sm:justify-center"
  >
    <!-- <div>
      <button @click="gotoNews()" class="px-8 xl:px-10 py-3 mt-2 bg-gradient-to-r from-[#468ef9] to-[#0c66ee] text-white rounded-2xl">Go to Crypto News Summaries</button>
    </div> -->
    <div>
      <iframe
        src="https://gryhkn.substack.com/embed"
        width="480"
        height="320"
        style="border: 1px solid #eee; background: white"
        frameborder="0"
        scrolling="no"
      ></iframe>
    </div>
  </div>
</template>

<script setup>
import { onMounted, ref } from "vue";
import AOS from "aos";

import LandingListItem from "../components/ListItem.vue";

onMounted(() => {
  AOS.init();
});

const open = ref(false);

const gotoNews = () => {
  console.log("gotoNews");
};

const showModal = ref(false);

const showM = () => {
  showModal.value = true;
};

const closeM = () => {
  showModal.value = false;
};

const deneme = () => {
  console.log("deneme");
};
</script>
<style>
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
  background: linear-gradient(136.91deg, #e10f0f -12.5%, #0c66ee 107.5%);
}

hr.style11 {
  height: 6px;
  background: url(http://ibrahimjabbari.com/images/hr-11.png) repeat-x 0 0;
  border: 0;
}

.modal-overlay {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0, 0, 0, 0.7);
  z-index: 1000;
}

.modal-content {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: white;
  padding: 20px;
  border-radius: 4px;
  z-index: 1000;
}
</style>
