<template>
  <a
    :href="link"
    :title="text"
    :target="target"
    class="inline-flex items-center bg-gray-900 text-gray-200 border-0 py-1 px-3 focus:outline-none hover:bg-gray-700 hover:text-gray-100 rounded text-base"
  >
    {{ text }}
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
  </a>
</template>

<script>
export default {
  name: "ButtonInquiry",
  props: {
    text: {
      type: String,
      default: "Anfrage",
    },
    link: {
      type: String,
      default: "mailto:office@architekturinform.com",
    },
    target: {
      type: String,
      default: "_self",
    },
  },
};
</script>
