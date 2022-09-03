<template>
  <span className="timestamp">{{ time }}</span>
</template>

<script>
export default {
  name: "Timestamp",
  props: {
    time: {
      type: String,
      default: "",
    },
  },
};
</script>

<style>
</style>