<template>
  <div class="tech">
    <div class="content">
      <img src="../assets/Images/banner/7.png" class="banner" />

      <p style="color: #fff">
        当講座では安定した資産形成を目指すために<br class="brRes" />
        テクノロジーを駆使した<br class="brRes" />
        取引手法についても解説します。

        <br /><br />
        相場を科学することで、"運に任せない投資”を<br class="brRes" />
        実践することが可能です。
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.tech {
  height: auto;
  background: #040418;
  background-image: url(/_nuxt/assets/Images/bg3.png) !important;
  background-position: top;
  background-repeat: no-repeat;
  margin: auto;

  .content {
    width: 900px;
    margin: 0px auto;
    line-height: 0;
    background: none;
    padding: 20px 20px 80px 20px;
    @media (max-width: 768px) {
      max-width: 100% !important;
      padding: 20px 20px 2px 20px;
    }
  }
  .banner {
    margin-top: 50px;
    margin-bottom: 50px;
    @media (max-width: 768px) {
      margin-bottom: 0px;
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
