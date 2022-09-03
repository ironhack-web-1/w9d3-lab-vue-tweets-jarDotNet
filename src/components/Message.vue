<template>
  <p className="message">{{ message }}</p>
</template>

<script>
export default {
  name: "Message",
  props: {
    message: {
      type: String,
      default: "",
    },
  },
};
</script>

<style>
</style>