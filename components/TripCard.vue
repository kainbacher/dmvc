<template>
  <nuxt-link
    :to="link"
    class="bg-gray-100 p-2 rounded-lg block hover:bg-gray-200 transition duration-300"
  >
    <img
      class="h-40 rounded w-full object-cover object-center m-0 mb-8"
      :src="image"
      alt="content"
    />
    <h3 class="tracking-widest text-gray-400 text-sm font-medium title-font mb-0">{{ country }}</h3>
    <h2 class="text-lg text-gray-900 font-medium title-font mb-0">{{ destination }}</h2>
    <p class="text-lg text-gray-600 font-medium title-font mb-4">{{ date }}</p>
    <p class="leading-relaxed text-base">
      {{ description }}
    </p>
  </nuxt-link>
</template>

<script>
export default {
  name: 'TripCard',
  props: {
    link: {
      type: String,
      required: true
    },
    image: {
      type: String,
      required: true
    },
    country: {
      type: String,
      required: true
    },
    destination: {
      type: String,
      required: true
    },
    date: {
      type: String,
      required: true
    },
    description: {
      type: String,
      required: true
    }
  }
}
</script>
