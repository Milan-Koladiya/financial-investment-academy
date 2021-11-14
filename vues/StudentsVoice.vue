<template>
  <div class="StudentsVoice">
    <div class="content">
      <img src="../assets/Images/banner/8.png" class="banner" />

      <!--カルーセル-->

      <div>
        <VueSlickCarousel  v-bind="settings" >
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
    import VueSlickCarousel from 'vue-slick-carousel'
    import 'vue-slick-carousel/dist/vue-slick-carousel.css'
    // optional style for arrows & dots
    import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
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
              "dots": true,
              "dotsClass": "slick-dots custom-dot-class",
              "edgeFriction": 0.35,
              "infinite": false,
              "speed": 500,
              "slidesToShow": 1,
              "slidesToScroll": 1
            },
          }
        },
    };
</script>

<style lang="scss" scoped>
.StudentsVoice {
  font-size: 22px;
  margin: 0;
  padding: 0;
  background: #effaff;
  font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans",
    "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue",
    "Segoe UI", Meiryo, sans-serif;

  .content {
    width: 100%;
    max-width: 900px;
    margin: 0px auto;
    line-height: 0;
    background: none;
    padding: 20px 20px 80px 20px;
    .slick-prev{
        &::before{
            color: #000066 !important;
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
