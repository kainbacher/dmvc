<template>
  <main
    class="container mx-auto max-w-4xl py-16 flex justify-center items-center min-h-screen"
  >
    <section class="max-w-md">
      <h1 class="font-serif tracking-widest font-normal text-6xl mb-8">DVMC</h1>
      <hr class="my-8 border-gray-800" />
      <p class="text-gray-500">
        DMVC bietet den Vertrieb, Verkauf, Beratung, Marketing, Organisation,
        Kommunikation, Energiemanagement und die Vermarktung von Produkten aller Art an.
      </p>
      <hr class="my-8 border-gray-800" />
      <p class="text-gray-400 mb-8">
        <a
          href="https://www.google.com/maps/place/Lagerstrasse+4,+9200+Gossau,+Schweiz/@47.4112834,9.2726642,17z/data=!3m1!4b1!4m5!3m4!1s0x479ae0edb290623f:0xf8372034c32d432e!8m2!3d47.4112834!4d9.2748529"
          title="Open Google Maps"
          target="_blank"
          class="text-gray-400 hover:text-gray-100 transition-all duration-700"
        >
          Lagerstrasse 4<br />
          9200 Gossau / Schweiz <br />
        </a>
      </p>
      <button
        @click="mailto"
        class="inline-flex justify-center items-center text-gray-300 border border-gray-700 py-2 px-4 rounded-md transition-all duration-700 hover:border-gray-500 hover:text-gray-200 ring-2 ring-gray-800"
        href="#"
        title="E-Mail an DVMC"
      >
        <svg
          class="mr-2"
          xmlns="http://www.w3.org/2000/svg"
          width="16"
          height="16"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <line x1="22" y1="2" x2="11" y2="13" />
          <polygon points="22 2 15 22 11 13 2 9 22 2" />
        </svg>
        E-Mail
      </button>
      <hr class="my-8 border-gray-800" />
    </section>
  </main>
</template>

<script>
export default {
  head() {
    return {
      title: "DVMC AG",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "DVMC AG",
        },
      ],
    };
  },
  methods: {
    mailto() {
      window.location.href = "mailto:jd@dvmc.ch";
    },
  },
};
</script>
