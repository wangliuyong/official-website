<script setup lang="ts">
import Title from "@/components/title.vue";
import FBA from "../../../assets/FBA.jpg";
import air2 from "../../../assets/air2.jpg";
import owh2 from "../../../assets/owh2.jpg";
import fcl3 from "../../../assets/fcl3.jpg";
import package3 from "../../../assets/package.jpg";
import package4 from "../../../assets/package4.jpg";
</script>

<template>
  <Title title="公司业务" id="service" describe="为商品无障碍流通不懈努力！" />
  <div class="service_card-list content">
    <div class="service_card-item">
      <div class="img-wrap">
        <img :src="FBA" alt="" />
      </div>
      <div class="des">中东FBA/FBN专线</div>
    </div>

    <div class="service_card-item">
      <div class="img-wrap">
        <img :src="air2" alt="" />
      </div>

      <div class="des">空运/海运门到门</div>
    </div>

    <div class="service_card-item">
      <div class="img-wrap">
        <img :src="owh2" height="211" alt="" />
      </div>
      <div class="des">海外仓</div>
    </div>

    <div class="service_card-item">
      <div class="img-wrap">
        <img :src="fcl3" height="211" alt="" />
      </div>
      <div class="des">海运整体柜清仓</div>
    </div>

    <div class="service_card-item">
      <div class="img-wrap">
        <img :src="package3" height="211" alt="" />
      </div>
      <div class="des">Saber证书</div>
    </div>
    <div class="service_card-item">
      <div class="img-wrap">
        <img :src="package4" height="211" alt="" />
      </div>
      <div class="des">B2C小包</div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.service_card {
  &-list {
    width: 1190px;
    display: flex;
    gap: 16px;
    margin: 0 auto;
    flex-wrap: wrap;
  }

  &-item {
    overflow: hidden;
    cursor: pointer;
    width: calc(100% / 4 - 16px);
    border-radius: 4px;
    transition: all 0.3s ease-in-out;

    &:hover {
      box-shadow: 0 4px 24px 0 rgba(0, 0, 0, 0.13);
      img {
        transform: scale(1.1);
      }
    }

    .img-wrap {
      overflow: hidden;
      height: 187px;
    }
    img {
      transition: all 0.3s ease-in-out;
      width: 100%;
      transform: scale(1);
    }
    .des {
      display: flex;
      justify-content: center;
      justify-content: center;
      border-bottom-left-radius: 4px;
      border-bottom-right-radius: 4px;
      font-size: 18px;
      box-sizing: border-box;
      padding: calc(16 * 0.0625em);
      color: #333;
      border: #f5f5f5 1px solid;
      font-size: 18px;
      word-break: break-word;
      font-weight: 500;
    }
  }
}
</style>
