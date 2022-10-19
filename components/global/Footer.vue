<template>
  <footer class="text-gray-600 body-font bg-gray-50">
    <div
      class="container px-5 py-24 mx-auto flex md:items-center lg:items-start md:flex-row md:flex-nowrap flex-wrap flex-col"
    >
      <div class="w-40 flex-shrink-0 md:mx-0 mx-auto text-center md:text-left">
        <nuxt-link to="/" class="">
          <Logo />
        </nuxt-link>
      </div>
      <div
        class="flex-grow flex flex-wrap md:pl-20 -mb-10 md:mt-0 mt-10 md:text-left text-center"
      >
        <div class="lg:w-1/3 md:w-1/2 w-full px-4">
          <p class="mb-10">
            Schillerstraße 28a<br />
            6850 Dornbirn / Österreich<br />
            <br />
            <a href="tel:+436642301643" class="hover:text-gray-900">+43 664 2301643</a><br />
            <a href="mailto:office@architekturinform.com" title="E-Mail an architekturINFORM" class="hover:text-gray-900">office@architekturinform.com</a>
          </p>
        </div>
        <div class="lg:w-1/3 md:w-1/2 w-full px-4">
          <nav class="list-none mb-10">
            <li>
              <nuxt-link to="/" class="text-gray-600 hover:text-gray-900">Startseite</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/reisen" class="text-gray-600 hover:text-gray-900">Reisen & Exkursionen</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/beriechte" class="text-gray-600 hover:text-gray-900">Reiseberichte</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/infos" class="text-gray-600 hover:text-gray-900">architektur INFORM</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/kontakt" class="text-gray-600 hover:text-gray-900">Kontakt</nuxt-link>
            </li>
          </nav>
        </div>
        <div class="lg:w-1/3 md:w-1/2 w-full px-4">
          <nav class="list-none mb-10">
            <li>
              <nuxt-link
                to="/kontakt"
                class="text-gray-600 hover:text-gray-900"
                title="Kontakt"
                >Kontakt</nuxt-link
              >
            </li>
            <li>
              <nuxt-link
                to="/impressum"
                class="text-gray-600 hover:text-gray-900"
                title="Impressum"
                >Impressum</nuxt-link
              >
            </li>
            <li>
              <nuxt-link
                to="/datenschutz"
                class="text-gray-600 hover:text-gray-900"
                title="Datenschutz"
                >Datenschutz</nuxt-link
              >
            </li>
            <li>&nbsp;</li>
            <li>
              <nuxt-link
                to="/kontakt"
                class="text-gray-600 hover:text-gray-900"
                title="Newsletter Anmeldung"
                >Newsletter Anmeldung</nuxt-link
              >
            </li>
          </nav>
        </div>
      </div>
    </div>
    <div class="bg-gray-100">
      <div class="container mx-auto py-4 px-5 flex flex-wrap flex-col sm:flex-row">
        <p class="text-gray-500 text-sm text-center sm:text-left">
          © 2020 architektur INFORM
        </p>
        <span class="inline-flex sm:ml-auto sm:mt-0 mt-2 justify-center sm:justify-start">
          <a class="text-gray-500">
            <svg
              fill="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="w-5 h-5"
              viewBox="0 0 24 24"
            >
              <path
                d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"
              ></path>
            </svg>
          </a>
          <a class="ml-3 text-gray-500">
            <svg
              fill="currentColor"
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="0"
              class="w-5 h-5"
              viewBox="0 0 24 24"
            >
              <path
                stroke="none"
                d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"
              ></path>
              <circle cx="4" cy="4" r="2" stroke="none"></circle>
            </svg>
          </a>
        </span>
      </div>
    </div>
  </footer>
</template>
