<script setup lang="ts">
import Slide from "./components/slide.vue";
import Service from "./components/service.vue";
import CompanyInfo from "./components/company-info.vue";
import Partner from "./components/partner.vue";
import Contact from "./components/contact.vue";
</script>

<template>
  <!-- 轮播图 -->
  <Slide />
  <!-- 公司业务 -->
  <Service />
  <div class="margin-top25"></div>
  <!-- 公司简介 -->
  <CompanyInfo />
  <div class="margin-top25"></div>
  <Partner />
  <div class="margin-top25"></div>
  <Contact />
</template>

<style scoped lang="scss">
.margin-top25 {
  height: 2.5em;
}
</style>
