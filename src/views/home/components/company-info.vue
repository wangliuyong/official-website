<script setup lang="ts">
import Title from "@/components/title.vue";
</script>

<template>
  <div class="content company_info-wrap">
    <Title title="公司信息" describe="客户第一，服务至上！" id="company-info" />
    <div class="desc">
      xxxx物流，创始团队拥有十余年中东跨境物流管理经验，原阿里资深产品专家领衔提供技术支持，坚持用科技赋能物流，通过自主研发的数字化管理系统，依托大数据智能解析，实现高危订单拦截，物流路由动态切换，实时跨境回款等增值服务，整合链路优质资源，自营清关渠道，自建中东海外仓，自有本土派送团队，致力干跨境中东的头程物流、进口清关、海处仓、本地配送等全链路服务，为中东跨境商家提供稳定、高效的物流体验，赋能商家掘金中东。
    </div>
    <el-button type="primary"> 查看更多</el-button>
  </div>
</template>

<style scoped lang="scss">
.company_info {
  &-wrap {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    .desc {
      color: #333;
      font-size: 16px;
      line-height: 30px;
      margin-bottom: 20px;
    }
  }
}
</style>
