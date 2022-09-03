<template>
  <span className="user" v-if="userData">
    <span className="name">{{ userData.name }}</span>
    <span className="handle">@{{ userData.handle }}</span>
  </span>
</template>

<script>
export default {
  name: "User",
  props: {
    userData: {
      type: Object,
      default: null
    }
  },
};
</script>

<style>
</style>