<script setup lang="ts">
import Header from "./header.vue";
import Footer from "./footer.vue";
</script>

<template>
  <Header />
  <slot></slot>
  <Footer />
</template>

<style scoped lang="scss"></style>
