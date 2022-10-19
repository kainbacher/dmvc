<template>
  <header class="bg-gray-50 text-gray-600 body-font py-8">
    <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
      <nuxt-link to="/"  class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
        <Logo />
      </nuxt-link>
      <nav
        class="md:ml-auto md:mr-auto flex flex-wrap items-center text-base justify-center "
      >
        <nuxt-link to="/reisen" class="mr-5 hover:text-gray-900">Reisen & Exkursionen</nuxt-link>
        <nuxt-link to="/individuelle-touren" class="mr-5 hover:text-gray-900">Individuelle Touren</nuxt-link>
        <nuxt-link to="/berichte" class="mr-5 hover:text-gray-900">Reiseberichte</nuxt-link>
        <nuxt-link to="/infos" class="mr-5 hover:text-gray-900">architektur INFORM</nuxt-link>
        <nuxt-link to="/kontakt" class="mr-5 hover:text-gray-900">Kontakt</nuxt-link>
      </nav>
      <ButtonInquiry />
    </div>
  </header>
</template>

<style scoped>
a.nuxt-link-active {
  @apply text-gray-900;
}
</style>