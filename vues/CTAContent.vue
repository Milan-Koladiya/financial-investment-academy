<template>
  <div class="anime_bg">
    <div class="context">
      <div class="CTAcontent">
        <div align="center">
          <div class="content">
            <img src="../assets/Images/cta_tx.png" class="banner" />

            <!--「#」部分にURLを記述してください-->

            <!-- ここからは変更しないでください -->
            <a
              class="href-add-friend"
              href="https://penguin-asp.com/register/ibs/null"
              style="z-index: 9999"
            >
              <!-- ここまでは変更しないでください -->
              <img
                src="../assets/Images/btn2.png"
                class="pulsate-fwd"
                z-index="9999;"
              />

              <!-- ここからは変更しないでください -->
            </a>
            <!-- ここまでは変更しないでください -->

            <p class="cta_p">
              ※不要だと判断されましたら、いつでもワンクリックで登録の解除ができます。
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="area3">
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
  }
  .CTAcontent {
    width: 100%;
    margin: 0px auto;
    position: absolute;
    line-height: 0;
    background: none;
    z-index: 9999;
  }
  .content {
    width: 100%;
    max-width: 900px;
    margin: 0px auto;
    line-height: 0;
    background: none;
    padding: 20px 20px 80px 20px;
    @media (max-width: 768px) {
      max-width: 94% !important;
      padding: 20px 20px 2px 20px;
    }
  }
  .banner {
    margin-top: 50px;
    margin-bottom: 50px;
  }
  .pulsate-fwd {
    -webkit-animation: pulsate-fwd 1s linear infinite;
    animation: pulsate-fwd 1s linear infinite;
    width: 80%;
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
.cta_p {
  color: #fff;
  margin-top: 95px;
  font-size: 22px;
  @media (max-width: 768px) {
    margin-top: 49px;
  }
}
.area3 {
  background: #000066;
  background: -webkit-linear-gradient(to left, #8f94fb, #4e54c8);
  width: 100%;
  height: 750px;
  @media (max-width: 768px) {
    height: 640px;
  }
  @media (max-width: 576px) {
    height: 540px;
  }
  @media (max-width: 425px) {
    height: 500px;
  }
  @media (max-width: 375px) {
    height: 480px;
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
p {
    line-height: 1.7;
    font-weight: 400;
    color: #1a1a1a;
    font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans", "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue", "Segoe UI", Meiryo, sans-serif;
    text-align: center;
    font-size: 22px;
    @media (max-width: 790px) {
        font-size: 28px;
    }

    @media (max-width: 576px) {
        font-size: 22px;
    }

    @media (max-width: 425px) {
        font-size: 17px;
    }
    .brRes {
        @media (max-width: 768px) {
            content: "";   
        }
    }
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
