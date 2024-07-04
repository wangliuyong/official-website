<script setup lang="ts">
import Title from "@/components/title.vue";
</script>

<template>
  <Title title="公司业务" id="service" describe="为商品无障碍流通不懈努力！" />
  <div class="service_card-list content">
    <div class="service_card-item">
      <div class="img-wrap">
        <img
          src="https://offical-web.oss-cn-beijing.aliyuncs.com/FBA.jpg?Expires=1720078067&OSSAccessKeyId=TMP.3KfpeFWvkJou96xRT3pgBq5k2jDmee8micix6n9g6Bc6TT8pDcAh2ywBiDALWg33X9fQT7CXSFBwXa2qDTNW65J72LubKi&Signature=T5Ho1CuZIiJanER%2FIitJNjYzabY%3D"
          alt=""
        />
      </div>
      <div class="des">中东FBA/FBN专线</div>
    </div>

    <div class="service_card-item">
      <div class="img-wrap">
        <img
          src="https://offical-web.oss-cn-beijing.aliyuncs.com/air2.jpg?Expires=1720078121&OSSAccessKeyId=TMP.3KfpeFWvkJou96xRT3pgBq5k2jDmee8micix6n9g6Bc6TT8pDcAh2ywBiDALWg33X9fQT7CXSFBwXa2qDTNW65J72LubKi&Signature=4yebhkk6tPuQUqo2AGyPbLBYub4%3D"
          alt=""
        />
      </div>

      <div class="des">空运/海运门到门</div>
    </div>

    <div class="service_card-item">
      <div class="img-wrap">
        <img
          src="https://offical-web.oss-cn-beijing.aliyuncs.com/owh2.jpg?Expires=1720078198&OSSAccessKeyId=TMP.3KfpeFWvkJou96xRT3pgBq5k2jDmee8micix6n9g6Bc6TT8pDcAh2ywBiDALWg33X9fQT7CXSFBwXa2qDTNW65J72LubKi&Signature=Sn%2FXCZbVqEQdow2%2BkkfQZlW7HQk%3D"
          height="211"
          alt=""
        />
      </div>
      <div class="des">海外仓</div>
    </div>

    <div class="service_card-item">
      <div class="img-wrap">
        <img
          src="https://offical-web.oss-cn-beijing.aliyuncs.com/fcl3.jpg?Expires=1720078145&OSSAccessKeyId=TMP.3KfpeFWvkJou96xRT3pgBq5k2jDmee8micix6n9g6Bc6TT8pDcAh2ywBiDALWg33X9fQT7CXSFBwXa2qDTNW65J72LubKi&Signature=12ekc73VHdURwxcze%2F5goO0JBLI%3D"
          height="211"
          alt=""
        />
      </div>
      <div class="des">海运整体柜清仓</div>
    </div>

    <div class="service_card-item">
      <div class="img-wrap">
        <img
          src="https://offical-web.oss-cn-beijing.aliyuncs.com/package.jpg?Expires=1720078221&OSSAccessKeyId=TMP.3KfpeFWvkJou96xRT3pgBq5k2jDmee8micix6n9g6Bc6TT8pDcAh2ywBiDALWg33X9fQT7CXSFBwXa2qDTNW65J72LubKi&Signature=bFC0EozXScIgwzY8TTMcHOX1rpI%3D"
          height="211"
          alt=""
        />
      </div>
      <div class="des">Saber证书</div>
    </div>
    <div class="service_card-item">
      <div class="img-wrap">
        <img
          src="https://offical-web.oss-cn-beijing.aliyuncs.com/package4.jpg?Expires=1720078251&OSSAccessKeyId=TMP.3KfpeFWvkJou96xRT3pgBq5k2jDmee8micix6n9g6Bc6TT8pDcAh2ywBiDALWg33X9fQT7CXSFBwXa2qDTNW65J72LubKi&Signature=p0%2FyYmn0aeJrZKUBbfP6C%2FgwtF0%3D"
          height="211"
          alt=""
        />
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
