<script setup>
defineProps({
  heading: {
    typeof: "string",
    default: "Info Alert",
  },
  message: {
    typeof: "string",
    default: "This is the default messagenp.",
  },
  color: {
    typeof: "string",
    default: "blue",
  },
});
</script>

<template>
  <div
    class="p-4 mb-4 text-sm rounded-lg"
    :class="`text-${color}-900 bg-${color}-100`"
    role="alert"
  >
    <span class="font-medium">{{ heading }}</span> {{ message }}
  </div>
</template>

<style scoped></style>
