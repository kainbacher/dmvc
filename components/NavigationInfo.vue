<template>
  <section class="container mx-auto max-w-4xl pt-16">
    <div class="lg:w-4/5 mx-auto">
      <div class="border-b border-gray-200">
        <nav class="flex flex-wrap -mb-px text-gray-600 text-center" role="tablist">
          <nuxt-link to="/infos" class="inline-block p-4 rounded-t-lg border-b-2">
            architekturINFORM
          </nuxt-link>
          <nuxt-link
            to="/infos/vorarlberg"
            class="inline-block p-4 rounded-t-lg border-b-2"
          >
            Vorarlberg
          </nuxt-link>
          <nuxt-link
            to="/infos/regional"
            class="inline-block p-4 rounded-t-lg border-b-2"
          >
            Regional
          </nuxt-link>
          <nuxt-link
            to="/infos/international"
            class="inline-block p-4 rounded-t-lg border-b-2"
          >
            International
          </nuxt-link>
        </nav>
      </div>
    </div>
  </section>
</template>

<style>
.nuxt-link-exact-active {
  @apply text-gray-900 border-gray-900;
}
</style>