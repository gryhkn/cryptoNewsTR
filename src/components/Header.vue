<template>
  <nav id="navbar" class="relative z-10 w-full text-neutral-800">
    <div
      class="flex flex-col max-w-screen-xl px-8 mx-auto lg:items-center lg:justify-between lg:flex-row py-4"
    >
      <div
        class="flex flex-col lg:flex-row items-center space-x-4 xl:space-x-8"
      >
        <div class="w-full flex flex-row items-center justify-between py-6">
          <div>
            <img
              src="../assets/undraw_bitcoin.svg"
              class="w-8 xl:w-28"
              alt="Logo"
            />
          </div>
          <button
            class="rounded-lg lg:hidden focus:outline-none focus:shadow-outline"
            @click="open = !open"
          ></button>
        </div>
      </div>
      <div :class="[open ? 'flex' : 'hidden lg:flex']" class="space-x-3">
        <button
          class="px-8 xl:px-10 py-3 mt-2 bg-gradient-to-r from-[#468ef9] to-[#0c66ee] text-white rounded-2xl"
        >
          Sign Up
        </button>
      </div>
    </div>
  </nav>
</template>

<script setup>
let open = false;
let dropdownNavbar = false;

function dropdownToggler() {
  dropdownNavbar = !dropdownNavbar;
}
</script>
