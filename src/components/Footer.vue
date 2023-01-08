<template>
  <div class="bg-gray-100">
    <div
      class="container px-5 py-6 mx-auto flex items-center sm:flex-row flex-col"
    >
      <a
        class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900"
      >
        <i data-feather="terminal"></i>
        <span class="ml-3 text-xl">CryptoInsights</span>
      </a>
      <p class="text-sm text-gray-500 sm:ml-6 sm:mt-0 mt-4">
        © {{ copyrightDate }} CryptoInsights —
        <a
          href="https://twitter.com/gryhkn"
          rel="noopener noreferrer"
          class="text-gray-600 ml-1"
          target="_blank"
          >@gryhkn</a
        >
      </p>
      <span
        class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start space-x-1"
      >
        <a
          href="https://github.com/gryhkn"
          target="__blank"
          class="text-gray-400 hover:text-indigo-500 dark:hover:text-indigo-400 cursor-pointer rounded-lg bg-gray-50 dark:bg-ternary-dark hover:bg-gray-100 shadow-sm p-1 duration-500"
        >
          <i data-feather="github" class="w-5 sm:w-8 h-5 sm:h-8"></i>
        </a>
        <a
          href="https://twitter.com/gryhkn"
          target="__blank"
          class="text-gray-400 hover:text-indigo-500 dark:hover:text-indigo-400 cursor-pointer rounded-lg bg-gray-50 dark:bg-ternary-dark hover:bg-gray-100 shadow-sm p-1 duration-500"
        >
          <i data-feather="twitter" class="w-5 sm:w-8 h-5 sm:h-8"></i>
        </a>
        <a
          href="https://gryhkn.medium.com"
          target="__blank"
          class="text-gray-400 hover:text-indigo-500 dark:hover:text-indigo-400 cursor-pointer rounded-lg bg-gray-50 dark:bg-ternary-dark hover:bg-gray-100 shadow-sm p-1 duration-500"
        >
          <i data-feather="book" class="w-5 sm:w-8 h-5 sm:h-8"></i>
        </a>

        <a
          href="https://www.linkedin.com/in/gryhkn/"
          target="__blank"
          class="text-gray-400 hover:text-indigo-500 dark:hover:text-indigo-400 cursor-pointer rounded-lg bg-gray-50 dark:bg-ternary-dark hover:bg-gray-100 shadow-sm p-1 duration-500"
        >
          <i data-feather="linkedin" class="w-5 sm:w-8 h-5 sm:h-8"></i>
        </a>
      </span>
    </div>

  </div>
</template>

<script setup>
import feather from "feather-icons";
import { onMounted, onUpdated } from "vue";

let copyrightDate = new Date().getFullYear();
onMounted(() => {
  feather.replace();
});

onUpdated(() => {
  feather.replace();
});
</script>
