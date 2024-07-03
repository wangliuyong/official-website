<script setup lang="ts">
import { Phone } from "@element-plus/icons-vue";

const openWl = () => {
  window.open("http://120.79.45.105/#/order-track");
};
</script>

<template>
  <div class="footer-wrap content">
    <span class="page-item">首页 <span class="i-border"></span></span>
    <span class="page-item">公司业务 <span class="i-border"></span></span>
    <span class="page-item" @click="openWl"
      >物流追踪 <span class="i-border"></span
    ></span>

    <span class="page-item">公司简介 <span class="i-border"></span></span>

    <el-button type="primary" :icon="Phone"> 联系我们</el-button>
  </div>

  <div class="copyright">
    Copyright © 广州安时达国际供应链有限公司
    地址：广东省广州市广州市白云区石槎路穗新创意园2号楼601
  </div>
</template>

<style scoped lang="scss">
@import "@/assets/style/variable.scss";

.footer-wrap {
  margin-top: 40px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 30px 0;
  .page-item {
    padding-right: 3.125em;
    padding-left: 3.125em;
    text-align: center;
    display: inline-block;
    position: relative;
    font-weight: 500;
    color: #333;
    font-size: 16px;
    cursor: pointer;

    &::after {
      content: "";
      position: absolute;
      right: 0;
      top: 50%;
      border-right: 1px solid #d8d8d8;
      margin-top: -0.4375em;
      height: 0.875em;
    }
  }
}

.copyright {
  font-size: 12px;
  display: block;

  line-height: 2;
  text-align: center;
  color: #666;
  margin-left: calc(10 * 0.0625em);
  padding-bottom: 20px;
}
</style>
