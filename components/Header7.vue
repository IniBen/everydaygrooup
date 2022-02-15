<template>
  <!-- Section 1 -->
  <section
    class="relative w-full bg-top bg-cover md:bg-center bg3"
    x-data="{ showMenu: false }"
    
  >
    <header>
      <div
        class="
          flex flex-col flex-wrap
          items-center
          px-8
          py-6
          mx-auto
          max-w-7xl
          md:flex-row
        "
      >
        <a
          href="#_"
          class="
            flex
            items-center
            order-first
            mb-4
            font-medium
            text-gray-900
            lg:order-none lg:w-auto
            title-font
            lg:items-center lg:justify-center
            md:mb-0
          "
        >
          <!-- <span
            class="
              text-xl
              font-black
              leading-none
              text-gray-900
              select-none
              logo
            "
            >NewDevz<span class="text-indigo-500">.</span></span
          > -->
          <img src="~/assets/Everyday1.png" alt="">
        </a>
        <nav
          class="
            flex flex-wrap
            items-center
            justify-center
            text-base
            font-bold
            tracking-tight
            md:ml-auto
          "
        >
          <a href="#_" class="mr-5 hover:text-gray-900">Home</a>
          <a href="#_" class="mr-5 hover:text-gray-900">Features</a>
          <a href="#_" class="mr-5 hover:text-gray-900">Pricing</a>
          <a href="#_" class="mr-5 hover:text-gray-900">Blog</a>
        </nav>
        <button
          class="
            inline-flex
            items-center
            px-3
            py-2
            mt-4
            text-sm
            font-bold
            text-gray-700
            bg-gray-200
            border-0
            rounded
            focus:outline-none
            hover:bg-gray-300
            md:mt-0
          "
        >
          Try For Free
          <svg
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            class="w-4 h-4 ml-1"
            viewBox="0 0 24 24"
          >
            <path d="M5 12h14M12 5l7 7-7 7"></path>
          </svg>
        </button>
      </div>
    </header>
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
    <div class="relative flex items-center justify-between w-full h-20 px-8">
      <!-- <a
        href="#_"
        class="
          relative
          flex
          items-center
          h-full
          pr-6
          text-lg
          font-extrabold
          text-white
        "
        >NewDevz<span class="text-green-400">.</span></a
      > -->
      <!-- <nav
        class="
          top-0
          left-0
          flex-col
          items-center
          justify-center
          hidden
          h-full
          space-y-3
          bg-white
          md:justify-end
          md:bg-transparent
          md:space-x-5
          md:space-y-0
          md:relative
          md:flex
          md:flex-row
        "
        :class="{
          'flex fixed top-0 left-0 w-full z-40': showMenu,
          hidden: !showMenu,
        }"
      >
        <a
          href="#_"
          class="
            relative
            text-lg
            font-medium
            tracking-wide
            text-green-400
            transition
            duration-150
            ease-out
            md:text-sm md:text-white
          "
          x-data="{ hover: false }"
          @mouseenter="hover = true"
          @mouseleave="hover = false"
        >
          <span class="block">Home</span>
          <span
            class="
              absolute
              bottom-0
              left-0
              inline-block
              w-full
              h-1
              -mb-1
              overflow-hidden
            "
          >
            <span
              x-show="hover"
              class="
                absolute
                inset-0
                inline-block
                w-full
                h-1 h-full
                transform
                border-t-2 border-green-400
              "
              x-transition:enter="transition ease-out duration-150"
              x-transition:enter-start="scale-0"
              x-transition:enter-end="scale-100"
              x-transition:leave="transition ease-out duration-300"
              x-transition:leave-start="scale-100"
              x-transition:leave-end="scale-0"
            ></span>
          </span>
        </a>
        <a
          href="#_"
          class="
            relative
            text-lg
            font-medium
            tracking-wide
            text-green-400
            transition
            duration-150
            ease-out
            md:text-white md:text-sm
          "
          x-data="{ hover: false }"
          @mouseenter="hover = true"
          @mouseleave="hover = false"
        >
          <span class="block">Features</span>
          <span
            class="
              absolute
              bottom-0
              left-0
              inline-block
              w-full
              h-1
              -mb-1
              overflow-hidden
            "
          >
            <span
              x-show="hover"
              class="
                absolute
                inset-0
                inline-block
                w-full
                h-1 h-full
                transform
                border-t-2 border-green-400
              "
              x-transition:enter="transition ease-out duration-150"
              x-transition:enter-start="scale-0"
              x-transition:enter-end="scale-100"
              x-transition:leave="transition ease-out duration-300"
              x-transition:leave-start="scale-100"
              x-transition:leave-end="scale-0"
            ></span>
          </span>
        </a>
        <a
          href="#_"
          class="
            relative
            text-lg
            font-medium
            tracking-wide
            text-green-400
            transition
            duration-150
            ease-out
            md:text-white md:text-sm
          "
          x-data="{ hover: false }"
          @mouseenter="hover = true"
          @mouseleave="hover = false"
        >
          <span class="block">Pricing</span>
          <span
            class="
              absolute
              bottom-0
              left-0
              inline-block
              w-full
              h-1
              -mb-1
              overflow-hidden
            "
          >
            <span
              x-show="hover"
              class="
                absolute
                inset-0
                inline-block
                w-full
                h-1 h-full
                transform
                border-t-2 border-green-400
              "
              x-transition:enter="transition ease-out duration-150"
              x-transition:enter-start="scale-0"
              x-transition:enter-end="scale-100"
              x-transition:leave="transition ease-out duration-300"
              x-transition:leave-start="scale-100"
              x-transition:leave-end="scale-0"
            ></span>
          </span>
        </a>
        <a
          href="#_"
          class="
            relative
            text-lg
            font-medium
            tracking-wide
            text-green-400
            transition
            duration-150
            ease-out
            md:text-white md:text-sm
          "
          x-data="{ hover: false }"
          @mouseenter="hover = true"
          @mouseleave="hover = false"
        >
          <span class="block">Blog</span>
          <span
            class="
              absolute
              bottom-0
              left-0
              inline-block
              w-full
              h-1
              -mb-1
              overflow-hidden
            "
          >
            <span
              x-show="hover"
              class="
                absolute
                inset-0
                inline-block
                w-full
                h-1 h-full
                transform
                border-t-2 border-green-400
              "
              x-transition:enter="transition ease-out duration-150"
              x-transition:enter-start="scale-0"
              x-transition:enter-end="scale-100"
              x-transition:leave="transition ease-out duration-300"
              x-transition:leave-start="scale-100"
              x-transition:leave-end="scale-0"
            ></span>
          </span>
        </a>
        <a
          href="#_"
          class="
            relative
            text-lg
            font-medium
            tracking-wide
            text-green-400
            transition
            duration-150
            ease-out
            md:text-sm md:text-white
          "
          x-data="{ hover: false }"
          @mouseenter="hover = true"
          @mouseleave="hover = false"
        >
          <span class="block">Contact</span>
          <span
            class="
              absolute
              bottom-0
              left-0
              inline-block
              w-full
              h-1
              -mb-1
              overflow-hidden
            "
          >
            <span
              x-show="hover"
              class="
                absolute
                inset-0
                inline-block
                w-full
                h-1 h-full
                transform
                border-t-2 border-green-400
              "
              x-transition:enter="transition ease-out duration-150"
              x-transition:enter-start="scale-0"
              x-transition:enter-end="scale-100"
              x-transition:leave="transition ease-out duration-300"
              x-transition:leave-start="scale-100"
              x-transition:leave-end="scale-0"
            ></span>
          </span>
        </a>
        <a
          href="#_"
          class="
            flex
            items-center
            px-3
            py-2
            text-sm
            font-medium
            tracking-normal
            text-white
            transition
            duration-150
            bg-green-400
            rounded
            hover:bg-green-500
            ease
          "
        >
          <svg
            class="w-6 h-6 mr-1"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M11 16l-4-4m0 0l4-4m-4 4h14m-5 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h7a3 3 0 013 3v1"
            ></path>
          </svg>
          Log in
        </a>
      </nav> -->

      <!-- Mobile Nav  -->
      <nav
        class="fixed top-0 right-0 z-30 z-50 flex w-10 h-10 mt-4 mr-4 md:hidden"
      >
        <button
          @click="showMenu = !showMenu"
          class="
            flex
            items-center
            justify-center
            w-10
            h-10
            rounded-full
            hover:bg-white hover:bg-opacity-25
            focus:outline-none
          "
        >
          <svg
            class="w-5 h-5 text-gray-200 fill-current"
            x-show="!showMenu"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
          </svg>
          <svg
            class="w-5 h-5 text-gray-500"
            x-show="showMenu"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M6 18L18 6M6 6l12 12"
            ></path>
          </svg>
        </button>
      </nav>
      <!-- End Mobile Nav -->
    </div>
    <div class="relative z-10 max-w-6xl px-10 py-24 mx-auto">
      <div class="flex flex-col items-center h-full lg:flex-row">
        <div
          class="
            flex flex-col
            text-center
            ml-52
            pb-20
            items-center
            justify-center
            w-full
            h-full
            lg:w-2/3 lg:items-start
          "
        >
        <div class="ml-5 text-center sm:px-6 lg:px-8">
          <h1 class="
          text-5xl
          font-bold
          tracking-tight
          text-white
          sm:text-5xl
          md:text-6xl
          xl:text-7xl
          mb-16
        ">Everybody Group</h1>
          <a
          href="#"
          class="
            inline-flex
            items-center
            justify-center
            w-48
            px-5
            py-3
            text-base
            font-bold
            text-indigo-900
            bg-white
            border border-transparent
            rounded-2xl
            shadow
          "
          >Learn More</a>
        </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
  .bg3{
    background-image: url("~/assets/header.png");
    background-size: auto;
  }
</style>