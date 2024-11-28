<script setup>
import MyAlert from "./components/myAlert.vue";
</script>

<template>
  <MyAlert
    heading="Alert"
    message="Change a few things up and try submitting again."
    color="red"
  />
  <MyAlert />
</template>

<style scoped></style>
