<script setup lang="ts">
import Title from "@/components/title.vue";
</script>

<template>
  <div class="content partner-wrap">
    <Title
      title="合作伙伴"
      describe="你可以及时了解公司以及公司产品的相关动态！"
      id="partner"
    />
    <div class="partner-list">
      <div class="img-wrap">
        <img
          alt=""
          src="https://jmy-pic.baidu.com/0/pic/-949803988_-1513211321.jpg"
          class="groot-ui-image-inner"
          style="width: 100%"
        />
      </div>

      <div class="img-wrap">
        <img
          alt=""
          src="https://jmy-pic.baidu.com/0/pic/-208598566_757827758.png"
          class="groot-ui-image-inner"
          style="width: 100%"
        />
      </div>

      <div class="img-wrap">
        <img
          alt=""
          src="https://jmy-pic.baidu.com/0/pic/353585607_310149646.png"
          class="groot-ui-image-inner"
          style="width: 100%"
        />
      </div>

      <div class="img-wrap">
        <img
          alt=""
          src="https://jmy-pic.baidu.com/0/pic/-949803988_-1513211321.jpg"
          class="groot-ui-image-inner"
          style="width: 100%"
        />
      </div>

      <div class="img-wrap">
        <img
          alt=""
          src="https://jmy-pic.baidu.com/0/pic/-949803988_-1513211321.jpg"
          class="groot-ui-image-inner"
          style="width: 100%"
        />
      </div>

      <div class="img-wrap">
        <img
          alt=""
          src="https://jmy-pic.baidu.com/0/pic/-949803988_-1513211321.jpg"
          class="groot-ui-image-inner"
          style="width: 100%"
        />
      </div>

      <div class="img-wrap">
        <img
          alt=""
          src="https://jmy-pic.baidu.com/0/pic/-208598566_757827758.png"
          class="groot-ui-image-inner"
          style="width: 100%"
        />
      </div>

      <div class="img-wrap">
        <img
          alt=""
          src="https://jmy-pic.baidu.com/0/pic/-208598566_757827758.png"
          class="groot-ui-image-inner"
          style="width: 100%"
        />
      </div>

      <div class="img-wrap">
        <img
          alt=""
          src="https://jmy-pic.baidu.com/0/pic/-208598566_757827758.png"
          class="groot-ui-image-inner"
          style="width: 100%"
        />
      </div>

      <div class="img-wrap">
        <img
          alt=""
          src="https://jmy-pic.baidu.com/0/pic/-208598566_757827758.png"
          class="groot-ui-image-inner"
          style="width: 100%"
        />
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.partner {
  &-wrap {
  }

  &-list {
    display: flex;
    gap: 0.625em;
    flex-wrap: wrap;
    .img-wrap {
      box-sizing: border-box;
      overflow: hidden;
      width: calc(100% / 5 - 0.625em);

      border-radius: 2px;
      margin-right: 0.0625em;
      border: 1px solid #eee;
      padding: calc(20 * 0.0625em);
    }
  }
}
</style>
