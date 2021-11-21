<template>
  <div class="StudentsVoice">
    <div class="content">
      <img src="../assets/Images/banner/8.png" class="banner" />

      <!--カルーセル-->

      <div>
        <VueSlickCarousel v-bind="settings" :autoplay="true" :infinite="true">
          <div>
            <img src="../assets/Images//voice/1.png" />
          </div>
          <div>
            <img src="../assets/Images//voice/2.png" />
          </div>
          <div>
            <img src="../assets/Images//voice/3.png" />
          </div>
          <div>
            <img src="../assets/Images//voice/4.png" />
          </div>
          <div>
            <img src="../assets/Images//voice/5.png" />
          </div>
        </VueSlickCarousel>
      </div>
    </div>
  </div>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";
export default {
  components: { VueSlickCarousel },
  // settings: {
  //     "dots": true,
  //     "dotsClass": "slick-dots custom-dot-class",
  //     "edgeFriction": 0.35,
  //     "infinite": false,
  //     "speed": 500,
  //     "slidesToShow": 1,
  //     "slidesToScroll": 1
  // },
  data() {
    return {
      settings: {
        dots: true,
        dotsClass: "slick-dots custom-dot-class",
        edgeFriction: 0.35,
        infinite: false,
        speed: 500,
        slidesToShow: 1,
        slidesToScroll: 1,
      },
    };
  },
};
</script>

<style lang="scss">
.slick-prev:before {
  content: '←' !important;
  color: #000066 !important;
  font-size: 45px !important;
  font-family: Arial, Helvetica, sans-serif !important;
    @media (max-width: 768px) {
    font-size: 35px !important;
  }
    @media (max-width: 425px) {
    font-size: 25px !important;
  }
    @media (max-width: 320px) {
    font-size: 20px !important;
  }
}

.slick-next:before {
  content: '→' !important;
  color: #000066 !important;
  font-size: 45px !important;
  font-family: Arial, Helvetica, sans-serif !important;
  @media (max-width: 768px) {
    font-size: 35px !important;
  }
    @media (max-width: 425px) {
    font-size: 25px !important;
  }
    @media (max-width: 320px) {
    font-size: 20px !important;
  }
}
// button.slick-prev:before,
// button.slick-next:before {
//   background-color: red !important;
// }
// .StudentsVoice .content .slick-prev::before {
//   background-color: white !important;
//   color: #fff !important;
//   opacity: 1 !important;
// }
// button.slick-prev:before,
// button.slick-next:before {
//   background-color: white !important;
//   color: #000066 !important;
// }
.custom-dot-class {
  display: none !important;
}
// .slick-prev:before {
//   content: '→';
//   color: red;
//   font-size: 30px;
// }

// .slick-next:before {
//   content: '→';
//   color: red;
//   font-size: 30px;
// }
.StudentsVoice {
  font-size: 22px;
  margin: 0;
  padding: 0;
  background: #effaff;
  font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans",
    "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue",
    "Segoe UI", Meiryo, sans-serif;
  @media (max-width: 768px) {
    margin-left: 6%;
    width: 90%;
  }
  .content {
    width: 100%;
    max-width: 900px;
    margin: 0px auto;
    line-height: 0;
    background: none;
    padding: 20px 0px 80px 0px;
    .slick-prev {
      &::before {
        // color: #000066 !important;
      }
    }

    @media (max-width: 768px) {
      max-width: 94% !important;
    }

    .banner {
      margin-top: 50px;
      margin-bottom: 50px;
    }
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
</style>
