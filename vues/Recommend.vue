<template>
  
  <div class="recommend">
       <img
          src="../assets/Images/recommend.png"
          class="banner"
        />
  </div>
 
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.recommend {
    font-size: 22px;
    margin: 0;
    padding: 0;
   
    font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans", "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue", "Segoe UI", Meiryo, sans-serif;
}
img {
       width: 100%;
    height: 1594px  ;
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
