<template>
  <div class="recommend">
    <img src="../assets/Images/recommend1.png" alt="" />
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
.recommend {
  width: 100vw;
  // height: 1594px;
  // background-image: url(../assets/Images/recommend1.png);
  background-position: center;
  margin: auto;
}
img {
  width: 100%;
  // height: 1594px  ;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  -ms-user-select: none;
  background-position: center;
  margin: auto;
}
img.banner {
  @media (max-width: 768px) {
    max-height: 1567px;
    max-width: 187%;
    margin-left: -43%;
    width: auto;
    height: auto;
  }
}
</style>
