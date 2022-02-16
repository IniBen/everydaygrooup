<template>
  <!-- Section 1 -->
  <div>
    <section
    class="relative w-full bg-top bg-cover md:bg-center bg4"
    x-data="{ showMenu: false }"
  >
    <div class="absolute inset-0 w-full h-full bg-gray-900 opacity-25"></div>
    <!-- <div
      class="
        absolute
        inset-0
        w-full
        h-64
        opacity-50
        bg-gradient-to-b
        from-black
        to-transparent
      "
    ></div> -->
    <div class="flex items-center justify-between text-blue-900 h-24 px-8 mx-auto max-w-7xl">

        <a href="#_" class="relative z-10 flex items-center w-auto text-2xl font-extrabold leading-none text-black select-none">
            <img src="~/assets/everyday1.png" alt="">
        </a>

        <nav class="items-center justify-center hidden space-x-8 md:flex">
            <a href="#_" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false" class="relative inline-block text-base text-white font-bold transition duration-150 ease hover:text-blue-300">
                <span class="block">Home</span>
            </a>
            <a href="#_" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false" class="relative inline-block text-base text-white font-bold   transition duration-150 ease hover:text-blue-300">
                <span class="block">About Us</span>
            </a>
            <a href="#_" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false" class="relative inline-block text-base text-white font-bold   transition duration-150 ease hover:text-blue-300">
                <span class="block">Distributorships</span>
            </a>
            <a href="#_" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false" class="relative inline-block text-base text-white font-bold   transition duration-150 ease hover:text-blue-300">
                <span class="block">Brands</span>
            </a>
            <a href="#_" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false" class="relative inline-block text-base text-white font-bold   transition duration-150 ease hover:text-blue-300">
                <span class="block">Careers</span>
            </a>
            <a href="#_" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false" class="relative inline-block text-base text-white font-bold   transition duration-150 ease hover:text-blue-300">
                <span class="block">Contact Us</span>
            </a>
        </nav>
        
        <!-- Mobile Button -->
        <div class="flex items-center justify-center h-full md:hidden">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 8h16M4 16h16"></path>
            </svg>
        </div>
        
    </div>
    <div
            class="
              container
              max-w-lg
              px-4
              py-32
              mx-auto
              text-left
              md:max-w-none md:text-center
            "
          >
            <h1
              class="
                text-5xl
                font-extrabold
                leading-10
                tracking-tight
                
                text-left text-gray-900
                md:text-center
                sm:leading-none
                md:text-6xl
                lg:text-7xl
              "
            >
              <span class="inline md:block text-white">Everyday Group
                        </span>
            </h1>

            <div class="flex flex-col items-center mt-12 text-center">
              <span class="relative inline-flex w-full md:w-auto">
                <a
                  href="#_"
                  type="button"
                  class="
                    inline-flex
                    items-center
                    justify-center
                    w-full
                    px-8
                    py-4
                    text-base
                    font-bold
                    leading-6
                    text-indigo-900
                    bg-white
                    border border-transparent
                    rounded-2xl
                    md:w-auto
                    hover:bg-indigo-500
                    focus:outline-none
                    focus:ring-2
                    focus:ring-offset-2
                    focus:ring-indigo-600
                  "
                >
               Learn More
                </a>
              </span>
              <a href="#" class="mt-3 text-sm text-indigo-500">{{nLt}}</a>
            </div>
          </div>
    <div class="relative z-10 max-w-6xl px-10 py-40 mx-auto">
      <div class="flex flex-col items-center h-full lg:flex-row">
        <div
          class="
            flex flex-col
            items-center
            justify-center
            w-full
            h-full
            lg:w-2/3 lg:items-start
          "
        >
        </div>
        <div class="w-full max-w-sm mt-20 lg:mt-0 lg:w-1/3">
          <div class="relative">
          </div>
        </div>
      </div>
    </div>
  </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
  .bg4{
    background-image: url("~/assets/header.png");
    background-repeat: no-repeat;
    background-size: cover;
  }
</style>