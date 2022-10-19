<template>
  <div
    class="flex items-center mx-auto border-t pb-10 mb-10 border-gray-200 sm:flex-row flex-col mt-24 pt-16"
  >
    <div

      class="sm:w-32 sm:h-32 h-20 w-20 sm:mr-10 inline-flex items-center justify-center rounded-full bg-gray-100 text-gray-500 flex-shrink-0 relative overflow-hidden"
    >
      <img v-if="image" :src="image" :alt="name" class="w-full h-full object-cover object-center absolute inset-0 my-0" />
    </div>
    <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0">
      <p class="leading-relaxed text-base">
        {{ description }}
      </p>
      <h4 class="text-gray-900 text-lg title-font font-medium mb-2">{{ name }}</h4>
      <a
        v-if="link"
        :href="link"
        target="_blank"
        class="mt-3 text-gray-900 inline-flex items-center"
      >
        {{ company }}
        <svg
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          class="w-4 h-4 ml-2"
          viewBox="0 0 24 24"
        >
          <path d="M5 12h14M12 5l7 7-7 7"></path>
        </svg>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "PersonStatement",
  props: {
    name: {
      type: String,
      required: true,
    },
    image: {
      type: String,
      required: false,
    },
    description: {
      type: String,
      required: false,
    },
    company: {
      type: String,
      required: false,
    },
    link: {
      type: String,
      required: false,
    },
  },
};
</script>
