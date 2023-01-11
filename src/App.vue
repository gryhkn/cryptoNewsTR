<script setup>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Home from "./views/Home.vue";
import SecondComp from "./components/secondComp.vue";
//import axios from "axios";

// const getNews = async () => {
//   const options = {
//     method: "GET",
//     url: "https://crypto-update-live.p.rapidapi.com/news",
//     headers: {
//       "X-RapidAPI-Key": "278de6fb99msh20661c9202cc213p1f3ef1jsnd54f8a6451a5",
//       "X-RapidAPI-Host": "crypto-update-live.p.rapidapi.com",
//     },
//   };
//   console.log("getNews working");
//   const response = axios
//     .request(options)
//     .then(function (response) {
//       console.log(response.data);
//     })
//     .catch(function (error) {
//       console.error(error);
//     });
// };

//getNews();
</script>

<template>
  <div class="w-full pb-4">
    <div class="pt-0.5">
      <!-- App header -->
      <!-- Header / -->

      <!-- Home-->
      <Home />

      <!-- App footer -->
      <Footer />
    </div>
  </div>
</template>

<style scoped></style>
