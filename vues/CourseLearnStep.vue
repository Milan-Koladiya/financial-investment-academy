<template>
  <div class="CourseLearnStep">
    <div class="content">
      <img src="../assets/Images/banner/5.png" class="banner" />
      <div align="center">
        <img src="../assets/Images/merit.png" class="ic" />
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
.CourseLearnStep {
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

    @media (max-width: 768px) {
      max-width: 94% !important;
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

    .ic {
      width: 100%;
      margin: 0 auto;
      padding-bottom: 30px;
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
