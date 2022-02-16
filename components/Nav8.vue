<template>
  <div class="">
      
<!-- Section 1 -->
<section class="relative bg-white">
    <div class="flex items-center justify-between text-blue-900 h-24 px-8 mx-auto max-w-7xl">

        <a href="#_" class="relative z-10 flex items-center w-auto text-2xl font-extrabold  leading-none text-black select-none inline-flex items-center justify-center text-base font-bold leading-6 bg-gray-100 border border-transparent rounded-full
                  ">
            <img src="~/assets/everydaygroup.png" alt="">
        </a>

        <nav class="items-center justify-center hidden space-x-8 md:flex">
            <a href="#_" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false" class="relative inline-block text-base font-bold  uppercase transition duration-150 ease hover:text-blue-300">
                <span class="block">Home</span>
            </a>
            <a href="#_" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false" class="relative inline-block text-base font-bold  uppercase transition duration-150 ease hover:text-blue-300">
                <span class="block">About Us</span>
            </a>
            <a href="#_" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false" class="relative inline-block text-base font-bold  uppercase transition duration-150 ease hover:text-blue-300">
                <span class="block">Subsidiaries</span>
            </a>
            <a href="#_" x-data="{ hover: false }" @mouseenter="hover = true" @mouseleave="hover = false" class="relative inline-block text-base font-bold  uppercase transition duration-150 ease hover:text-blue-300">
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
</section>

  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>