<template>
  <div class="fire">
    <div class="anime_bg">
      <div class="context">
        <div class="content">
          <img src="../assets/Images/banner/1.png" class="banner" />

          <p style="color: #fff; text-align: center">
            FIREとは「Financial Independence（経済的自立）」と<br
              class="brRes"
            />
            「Retire Early（早期退職）」の頭文字からなり<br class="brRes" />
            投資収益だけで暮らしていくことで個人がさらに<br class="brRes" />
            豊かな人生設計していく生き方そのものを表します。
            <br /><br />
            欧米を中心に起こったFIREムーブメントは全世界に拡大し<br
              class="brRes"
            />
            日本でも実践しようとする人が増えています。
          </p>

          <div align="center">
            <img src="../assets/Images/fire_books.png" class="ic2" />
          </div>
        </div>
      </div>

      <div class="area1">
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
.fire {
  font-size: 22px;
  margin: 0;
  padding: 0;
  background: #effaff;
  font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans",
    "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue",
    "Segoe UI", Meiryo, sans-serif;

  .anime_bg {
    position: relative;

    .context {
      width: 100%;
      position: absolute;
      top: 0;

      .content {
        width: 100%;
        max-width: 900px;
        margin: 0px auto;
        line-height: 0;
        background: none;
        padding: 20px 20px 80px 20px;

        @media (max-width: 768px) {
          width: 94%;
        }

        .banner {
          margin-top: 50px;
          margin-bottom: 50px;
        }
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

    .area1 {
      background: #000066;
      background: -webkit-linear-gradient(to left, #8f94fb, #4e54c8);
      width: 100%;
      height: 1370px;

      @media (max-width: 768px) {
        height: 1300px;
      }
      @media (max-width: 576px) {
        height: 920px;
      }
      @media (max-width: 576px) {
        height: 780px;
      }
      @media (max-width: 576px) {
        height: 730px;
      }

      .circles {
        position: relative;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        overflow: hidden;
        list-style: none;
      }
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

  @media (max-width: 768px) {
    font-size: 26px;
    margin-top: -34px;
  }

  @media (max-width: 576px) {
    font-size: 17px;
  }
}
.brRes {
  @media (max-width: 768px) {
    content: "";
  }
}
.circles li:nth-child(1) {
  left: 25%;
  width: 80px;
  height: 80px;
  animation-delay: 0s;

  .circles li {
    position: absolute;
    display: block;
    list-style: none;
    height: 20px;
    background: rgba(255, 255, 255, 0.2);
    animation: animate 25s linear infinite;
    bottom: -150px;
  }
}

img {
  vertical-align: middle;
  border-style: none;
  max-width: 100%;
  height: auto;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  -ms-user-select: none;
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
</style>
