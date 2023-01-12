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
          scrolling="yes"
        ></iframe>
        <button
          @click="closeM()"
          class="font-bold bg-blue-300 text-white rounded-2xl p-1"
        >
          Kapat
        </button>
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
            Kayıt Ol
          </button>
        </div>
      </div>
    </div>
  </nav>
  <!-- End Header -->

  <div class="container mx-auto mt-10 max-w-screen-xl">
    <div class="mb-5 sm:mb-8 pb-24">
      <section class="relative px-4 sm:px-8 mx-auto grid grid-cols-12 gap-x-6">
        <!-- Banner left contents -->
        <div
          class="col-span-12 lg:col-span-6 mt-12 xl:mt-10 space-y-2 sm:space-y-6 px-6 text-center sm:text-left"
        >
          <span
            data-aos="fade-right"
            data-aos-delay="200"
            class="rounded-2xl p-2 text-white bg-blue-gradient"
            >Nedir?</span
          >
          <h1
            data-aos="fade-right"
            data-aos-delay="200"
            class="text-[2.5rem] sm:text-5xl xl:text-6xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10"
          >
            Günlük
            <span class="text-header-gradient">Kripto para</span>,
            <span class="text-header-blockchain"> Blockchain</span>,
            <span class="text-header-defi"> DeFi</span> ve daha fazlasının
            Özetleri
          </h1>
          <Menu> </Menu>

          <p
            class="font-general-medium mt-2 text-lg sm:text-xl xl:text-2xl text-center sm:text-left leading-none text-gray-400"
          >
            Kripto paralar ve blockchain dünyasındaki en önemli ve güncel haber
            özetlerini

            <a
              class="underline decoration-indigo-500"
              @mouseover="hover = true"
              @mouseleave="hover = false"
              >(sadece ikişer cümle ile)</a
            >
            <span v-if="hover" class="text-indigo-500 bg-blue-300"
              >State-of-the-art AI yöntemlerini kullanarak</span
            >
            her akşam saat 20:00'de e-posta adresinize gönderiyoruz.
          </p>
        </div>

        <div class="hidden sm:block col-span-12 lg:col-span-6">
          <div class="w-full">
            <img
              data-aos="fade-up"
              data-aos-delay="100"
              src="../assets/icons/hero-image.webp"
              class="-mt-4"
              alt=""
            />
          </div>
        </div>

        <img
          data-aos="fade-up"
          data-aos-delay="100"
          src="../assets/icons/pattern/ellipse-1.png"
          class="hidden sm:block absolute bottom-12 xl:bottom-16 left-4 xl:left-0 w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="100"
          src="../assets/icons/pattern/ellipse-2.png"
          class="hidden sm:block absolute top-4 sm:top-10 right-64 sm:right-96 xl:right-[32rem] w-6"
        />
        <img
          data-aos="fade-up"
          data-aos-delay="100"
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
        class="relative max-w-screen-xl px-4 sm:px-8 mx-auto grid grid-cols-12 gap-x-6"
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
            class="text-base text-gradient font-semibold sm:mb-2 text-white p-2 rounded-xl"
            >Bekleyin!
          </span>
          <h2 class="text-3xl sm:text-4xl font-semibold mb-4 sm:mb-2 mt-1">
            Daha Bitmedi
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
                  >Piyasayı yakından takip edin</span
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
                  >Kriptoda günlük en önemli haber/olay/etkinliklerin özeti. Hem
                  de Türkçe!</span
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
                  >Günün en çok yükselen kripto paraları ve daha fazlası</span
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
                  >Yakın zamanda gelişmiş analizler ve ekstra içerikler de
                  cabası!
                </span>
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
      class="relative max-w-screen-xl px-4 sm:px-8 mx-auto grid grid-cols-12 gap-x-6"
      data-aos="fade-up"
      data-aos-delay="200"
    >
      <div
        class="col-span-12 lg:col-span-5 space-y-6 px-4 sm:px-6 mt-20 sm:mb-2"
      >
        <h2 class="text-4xl font-semibold">
          Hayır, <span class="text-header-gradient">daha</span> bitmedi
        </h2>
        <p class="text-xl">
          Yakın zamanda burada anlık olarak önemli haberlerin
          <strong>özetlerini</strong> okuyabilecek ve
          <span class="text-sky-700">sektöre büyük çerçeveden</span> bakabilecek
          araçları bulabileceksiniz.
        </p>
        <button
          class="w-full sm:max-w-[240px] sm:mb-2 px-6 py-2 text-white bg-inherit text-gradient border border-[#0c66ee] text-base rounded-2xl"
          @click="showM()"
        >
          ŞİMDİ ABONE OL!
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
    class="relative sm:mx-4 xl:mx-10 my-24 shadow-2xl sm:rounded-2xl drop-shadow-2xl"
  >
    <div
      class="py-16 flex flex-col items-center sm:flex-col sm:items-center sm:justify-center max-w-screen-xl mx-auto"
    >
      <h2
        data-aos="flip-down"
        data-aos-delay="300"
        class="text-3xl sm:text-4xl font-semibold text-center"
      >
        Bir dakikada ücretsiz abone olun!
      </h2>
      <div
        data-aos="flip-up"
        data-aos-delay="300"
        class="relative w-full flex flex-col lg:flex-row items-center justify-between space-y-12 lg:space-y-0 px-4 xl:px-10 mt-16 sm:mt-8"
      >
        <div
          class="max-w-[280px] xl:max-w-[363px] space-y-6 sm:space-y-3 text-center"
        >
          <img
            src="../assets/icons/getting-started/sign-up.png"
            class="max-w-[245px] mx-auto"
            alt=""
          />
          <h3 class="text-xl text-neutral-800 font-semibold">Abone Ol</h3>
          <p class="text-sm text-gray-700 leading-relaxed">
            Kripto haber özetlerine ücretsiz abone ol.
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
          <h3 class="text-xl text-neutral-800 font-semibold">Takipte Kal</h3>
          <p class="text-sm text-gray-700 leading-relaxed">
            Her akşam mailinizi kontrol etmeyi unutmayın. Unutmayın, kripto
            hakkında en önemli şeyler ve sadece ikişer cümle.
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
          <h3 class="text-xl text-neutral-800 font-semibold">Akıllı Yatırım</h3>
          <p class="text-sm text-gray-700 leading-relaxed">
            Piyasayı yakından takip ederek daha fazla kazanın.
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
    class="flex items-center justify-center mb-4 my-auto sm:flex-col mx-auto"
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
import {
  // Directives
  VTooltip,
  Tooltip,
  Menu,
} from "floating-vue";

import "floating-vue/dist/style.css";

onMounted(() => {
  AOS.init();
});

const hover = ref(false);

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
.v-popper .v-popper--theme-menu .v-popper--theme-dropdown {
  padding: 20px;
}

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
.text-header-blockchain {
  background: rgb(57, 132, 244);
  background: linear-gradient(
    169.4deg,
    #11284b -6.01%,
    #04677d 36.87%,
    #13eb69 78.04%,
    #f40303 103.77%
  );
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
.text-header-defi {
  background: rgb(57, 132, 244);
  background: linear-gradient(
    169.4deg,
    #1e9600 -6.01%,
    #fff200 12.87%,
    #ff0000 78.04%,
    #f40303 103.77%
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
