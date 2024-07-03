<script setup lang="ts">
import { ref } from "vue";
import { Phone } from "@element-plus/icons-vue";
import type { TabsPaneContext } from "element-plus";

const activeName = ref("first");

const handleClick = (tab: TabsPaneContext, event: Event) => {
  console.log(tab, event);
};
</script>

<template>
  <div class="header-wrap">
    <div
      class="layout_header-wrap flex items-center align-center justify-between h-32 m-auto"
    >
      <div class="layout_header-left">
        <img
          src="https://jmy-pic.baidu.com/0/pic/364490799_-1647483170.jpg"
          alt=""
          class="logo"
          width="290"
          height="48"
        />
      </div>
      <div class="layout_header-right">
        <span class="page-item">首页 <span class="i-border"></span></span>
        <span class="page-item">公司业务 <span class="i-border"></span></span>

        <span class="page-item">公司简介 <span class="i-border"></span></span>

        <el-button type="primary" :icon="Phone"> 联系我们</el-button>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
@import "@/assets/style/variable.scss";

.header-wrap {
  position: sticky;
  z-index: 1000;
  top: 0;
  background-color: #fff;
}
.layout_header {
  &-wrap {
    width: 1190px;
    height: 80px;
  }

  &-right {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 32px;
    height: 100%;

    .page-item {
      position: relative;
      cursor: pointer;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
      font-size: 16px;

      .i-border {
        position: absolute;
        bottom: 0;
        left: 0;
        right: 0;
        height: 2px;
        background-color: $primary;

        display: none;
      }
      &:hover {
        .i-border {
          display: flex;
        }
      }
    }
  }
}
</style>
