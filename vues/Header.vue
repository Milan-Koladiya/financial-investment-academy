<template>
  <div class="header">
    <div class="head">
      <img src="../assets/Images/head_logo.png" class="aos-init" />
    </div>
    <div class="pc">
      <img
        src="../assets/Images/header_pc.png"
        class="head_pc"
        margin="0px calc(50% - 50vw)"
      />
    </div>
    <div class="sp">
      <div class="head_img">
        <img src="../assets/Images/header.png" />
      </div>
    </div>
    <div class="content">
      <div align="center">
        <a
          class="href-add-friend"
          href="https://penguin-asp.com/register/ibs/null"
        >
          <img src="../assets/Images/btn1.png" class="pulsate-fwd head_btn" />
          <!-- ここからは変更しないでください -->
        </a>
        <!-- ここまでは変更しないでください -->
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
body {
  font-size: 22px;
  margin: 0;
  padding: 0;
  font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans",
    "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue",
    "Segoe UI", Meiryo, sans-serif;
  @media (max-width: 1000px) {
    font-size: 40px;
  }
}
body {
  font-size: 22px;
  margin: 0;
  padding: 0;
  font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans",
    "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue",
    "Segoe UI", Meiryo, sans-serif;
}

.wrap {
  overflow: hidden;

  @media (max-width: 768px) {
    overflow: hidden;
  }
}

img {
  max-width: 100%;
  height: auto;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  -ms-user-select: none;
}

.header {
  background: #effaff;

  .head {
    width: 100vw;
    margin: auto;
    background: #000066;
    height: 77px;
    @media (max-width: 768px) {
      height: auto;
    }
    img {
      margin: 10px 20px 5px 30px;
      @media (max-width: 768px) {
        width: 50%;
      }
    }
  }

  .pc {
    display: block !important;
    @media (max-width: 768px) {
      display: none !important;
    }
  }

  .sp {
    display: none !important;

    @media (max-width: 768px) {
      display: block !important;
    }
    // .head_img{
    //     width: 100vw;
    //     height: 1224px;
    //     background-image: url(../assets/Images/header.png);
    //     background-position: center;
    //     margin: auto;
    // }
  }

  .pulsate-fwd {
    -webkit-animation: pulsate-fwd 1s linear infinite;
    animation: pulsate-fwd 1s linear infinite !important;
    width: 80%;
  }

  .content {
    width: 100%;
    max-width: 900px;
    margin: 0px auto;
    line-height: 0;
    background: none;
    padding: 20px 20px 80px 20px;

    @media (max-width: 768px) {
      max-width: 90% !important;
    }
  }
}

@keyframes pulsate-fwd {
  0% {
    transform: scale(1);
  }

  50% {
    transform: scale(1.3);
  }

  100% {
    transform: scale(1);
  }
}
</style>
