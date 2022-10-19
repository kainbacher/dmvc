<template>
  <p class="text-sm text-gray-500 tracking-widest font-medium title-font mb-1">
    {{ text }}
  </p>
</template>

<script>
export default {
  name: "PreTitle",
  props: {
    text: {
      type: String,
      default: "",
    },
  },
};
</script>