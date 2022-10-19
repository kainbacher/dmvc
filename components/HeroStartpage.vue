<template>
  <section class="bg-gray-50 pb-12">
    <div class="container mx-auto flex">
      <div
        class="mr-auto min-h-96 flex justify-center items-center flex-1 shrink-0 bg-gray-100 overflow-hidden shadow-lg rounded-md relative py-16 md:py-20 xl:py-48"
      >
        <!-- image - start -->
        <img
          src="https://www.architekturinform.com/media/filer_public_thumbnails/filer_public/7b/d8/7bd85683-ad49-4b6c-bc65-62bcfb27bdba/285.jpg__800x600_q95_crop-False.jpg"
          loading="lazy"
          alt="architekturINFORM"
          class="w-full h-full object-cover object-center absolute inset-0 my-0"
        />
        <!-- image - end -->

        <!-- overlay - start -->
        <div class="bg-gray-500 mix-blend-multiply absolute inset-0"></div>
        <!-- overlay - end -->

        <!-- text start -->
        <div class="sm:max-w-xl lg:max-w-6xl flex flex-col items-center relative p-4">
          <p class="text-gray-200 text-lg sm:text-xl text-center mb-4 md:mb-8">
            Architektur entdecken und erleben
          </p>
          <h1
            class="text-white text-4xl sm:text-5xl md:text-6xl font-bold text-center mb-8 md:mb-12"
          >
            Regionale und internationale Exkursionen und Architekturreisen
          </h1>

          <div class="w-full flex flex-col sm:flex-row sm:justify-center gap-4">
            <nuxt-link
              to="/reisen"
              class="inline-block hover:bg-gray-900 focus-visible:ring ring-white text-white border border-white active:text-gray-700 text-sm md:text-base font-semibold text-center rounded-lg outline-none transition duration-100 px-8 py-3"
            >
              Reisen & Exkursionen
            </nuxt-link>

            <nuxt-link
              to="/individuelle-touren"
              class="inline-block hover:bg-gray-900 focus-visible:ring ring-white text-white border border-white active:text-gray-700 text-sm md:text-base font-semibold text-center rounded-lg outline-none transition duration-100 px-8 py-3"
            >
              Individuelle Touren
            </nuxt-link>
          </div>
        </div>
        <!-- text end -->
      </div>
    </div>
  </section>
</template>
