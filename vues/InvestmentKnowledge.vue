<template>
  <div class="anime_bg">
    <div class="context">
      <div class="content">
        +
        <img src="../assets/Images/banner/4.png" class="banner" />

        <p style="color: #fff; text-align: center">
          当講座の「知識」と「メソッド」を理解すれば<br class="brRes" />
          投資は安定して資産を増やす強力なツールになります。
        </p>

        <div align="center">
          <img src="../assets/Images/graf.png" class="ic2" />
        </div>
      </div>
    </div>

    <div class="area2">
      <ul class="circles">
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
      </ul>
    </div>
    <div class="bubbles">
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
      <div class="bubble"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.anime_bg {
  position: relative;
  .context {
    width: 100%;
    position: absolute;
    top: 0;

    .content {
      width: 900px;
      margin: 0px auto;
      line-height: 0;
      background: none;
      padding: 20px 0px 80px 0px;
      @media (max-width: 768px) {
        max-width: 100% !important;
        padding: 20px 20px 2px 20px;
      }
      .banner {
        margin-top: 50px;
        margin-bottom: 50px;
        @media (max-width: 768px) {
          margin-top: 30px;
          margin-bottom: 13px;
        }
      }
      .ic2 {
        width: 70%;
        margin: 0 auto;
        padding-bottom: 30px;
        @media (max-width: 768px) {
          width: 100%;
        }
      }
    }
  }
  .area2 {
    background: #000066;
    // background: -webkit-linear-gradient(270deg,#8f94fb,#4e54c8);
    width: 100%;
    height: 1000px;
    @media (max-width: 768px) {
      height: 950px;
    }
    @media (max-width: 576px) {
      height: 750px;
    }
    @media (max-width: 426px) {
      height: 690px;
    }
    @media (max-width: 376px) {
      height: 630px;
    }

    .circles {
      position: relative;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      overflow: hidden;
    }
    .circles li:nth-child(1) {
      left: 25%;
      width: 80px;
      height: 80px;
      animation-delay: 0s;
    }
    .circles li {
      position: absolute;
      display: block;
      list-style: none;
      width: 20px;
      height: 20px;
      background: rgba(255, 255, 255, 0.2);
      animation: animate 25s linear infinite;
      bottom: -150px;
    }
  }
  .bubbles {
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: 0;
    overflow: hidden;
    top: 0;
    left: 0;
  }
  .bubble {
    position: absolute;
    bottom: -100px;
    width: 40px;
    height: 40px;
    background: rgba(255, 255, 255, 0.2);
    border-radius: 50%;
    opacity: 0.5;
    animation: rise 25s infinite ease-in;
  }
  .bubble:nth-child(1) {
    left: 25%;
    width: 80px;
    height: 80px;
    animation-delay: 0s;
  }
  .bubble:nth-child(2) {
    left: 10%;
    width: 20px;
    height: 20px;
    animation-delay: 2s;
    animation-duration: 12s;
  }
  .bubble:nth-child(3) {
    left: 70%;
    width: 20px;
    height: 20px;
    animation-delay: 4s;
  }
  .bubble:nth-child(4) {
    left: 40%;
    width: 60px;
    height: 60px;
    animation-delay: 0s;
    animation-duration: 18s;
  }
  .bubble:nth-child(5) {
    left: 65%;
    width: 20px;
    height: 20px;
    animation-delay: 0s;
  }
  .bubble:nth-child(6) {
    left: 75%;
    width: 110px;
    height: 110px;
    animation-delay: 3s;
  }
  .bubble:nth-child(7) {
    left: 35%;
    width: 150px;
    height: 150px;
    animation-delay: 7s;
  }
  .bubble:nth-child(8) {
    left: 50%;
    width: 25px;
    height: 25px;
    animation-delay: 15s;
    animation-duration: 45s;
  }
  .bubble:nth-child(9) {
    left: 20%;
    width: 15px;
    height: 15px;
    animation-delay: 2s;
    animation-duration: 35s;
  }
  .bubble:nth-child(10) {
    left: 85%;
    width: 150px;
    height: 150px;
    animation-delay: 0s;
    animation-duration: 11s;
  }
  @keyframes rise {
    0% {
      transform: translateY(0) rotate(0deg);
      opacity: 1;
      border-radius: 0;
    }
    100% {
      transform: translateY(-1000px) rotate(720deg);
      opacity: 0;
      border-radius: 50%;
    }
  }
}
p {
  line-height: 1.7;
  font-weight: 400;
  color: #1a1a1a;
  font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans",
    "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue",
    "Segoe UI", Meiryo, sans-serif;
  padding: 30px 0 40px 0;
  text-align: center;
  font-size: 22px;
  margin-bottom: 0px;
}

img {
  max-width: 100%;
  height: auto;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  -ms-user-select: none;
}
</style>
