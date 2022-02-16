<template>
  <div>
    <div>
      <section class="w-full mt-6 mb-12 antialiased bg-white bg3">
        
        <div class="mx-auto  w-full bg-violet-600 bg-opacity-40">
          <!-- Main Hero Content -->
          <div
            class="
              container
              w-full
              px-6
              py-32
              mx-auto
              text-left
              md:max-w-none md:text-center
              bg-indigo-500
              bg-opacity-50
              bg-[length:1920px_600px]

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
              <span class="inline text-white md:block">Grab ‘N’ Munch
              </span>
            </h1>
            <div
              class="
                mx-auto
                mt-5
                text-white
                md:mt-12 md:max-w-lg md:text-center
                lg:text-lg
              "
              contenteditable="true"
            >
              Simplifying the creation of landing pages, blog pages, application
              pages and so much more!
            </div>
            <div class="flex flex-col items-center mt-12 text-center">
              <span class="relative inline-flex w-full md:w-auto">
                
              </span>
              <a href="#" class="mt-3 text-sm text-indigo-500">{{nLt}}</a>
            </div>
          </div>
          <!-- End Main Hero Content -->
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderOne",
  props: ['nHt1','nHt2', 'nLt', 'nPrt1', 'nHt3']
};
</script>

<style>
  .bg3{
    background-image: url("~/assets/iceseafood.png");
    background-repeat: no-repeat;
  }
</style>