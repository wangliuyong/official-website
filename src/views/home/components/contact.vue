<script setup lang="ts"></script>

<template>
  <div class="contact-wrap">
    <dic class="contact-message content">
      <div>
        <h1>联系我们</h1>
        <div class="message-item">
          <span class="label">公司地址：</span>
          <span class="value"
            >广东省广州市广州市白云区石槎路穗新创意园2号楼601</span
          >
        </div>

        <div class="message-item">
          <span class="label">QQ：</span>
          <span class="value">1355498705</span>
        </div>

        <div class="message-item">
          <span class="label">微信：</span>
          <span class="value">1355498705</span>
        </div>

        <div class="message-item">
          <span class="label">邮箱：</span>
          <span class="value">1355498705</span>
        </div>

        <div class="message-item">
          <span class="label">工作时间：</span>
          <span class="value">09:00~24:00</span>
        </div>
        <div class="message-item">
          <span class="label">联系电话：</span>
          <span class="value">1355498705 王白菜</span>
        </div>
      </div>

      <div class="qr">
        <span class="weixin-label">官方微信</span>
        <img
          width="200"
          src="https://fleetan.com/static/img/wx.df00749.jpg"
          alt=""
        />
      </div>
    </dic>
  </div>
</template>

<style scoped lang="scss">
.contact-wrap {
  background-image: url("https://jmy-pic.wejianzhan.com/0/pic/97f9c4280e42c3a5e46e93db4c2a9495.png");
  color: rgb(255, 255, 255) !important;
  height: 27.75em;
  width: auto;
  box-sizing: border-box;
  background-position: center center;
  background-repeat: no-repeat;
  background-size: auto 100%;
  padding: 70px 0;
  .qr {
    margin-top: 2.25em;
  }
  .weixin-label {
    line-height: 2.5;
  }

  .contact-message {
    display: flex;
    align-items: center;
    justify-content: space-between;
    h1 {
      font-weight: 500;
      font-size: 30px;
      color: rgb(255, 255, 255) !important;
    }

    .message-item {
      display: flex;
      align-items: center;
      margin-top: 1.25em;
      line-height: 1.5;
      font-size: 16px;

      .label {
        display: flex;
        justify-content: space-between;
        width: 84px;
      }

      .value {
      }
    }
  }
}
</style>
