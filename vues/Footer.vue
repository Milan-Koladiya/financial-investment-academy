<template>
  <div class="footer">
   <footer>
        <p style="font-size:15px;">
            <a href="http://financial-investment-academy.com/tokusho/" target="_blank" class="fotter_link">特定商取引に基づく表記</a>　|　<a href="http://financial-investment-academy.com/privacy/" target="_blank" class="fotter_link">プライバシーポリシー</a>
            <br>
            Copyright © 2021 Financial Investment Academy. All Right Reserved.</p>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.footer{
footer {
    background-color: #666;
    padding: 10px;
    text-align: center;
}

footer p {
    color: #fff;
    font-size: 15px;
    font-weight: 500;
    padding: 5px;
        margin-bottom: 0px;
}
.fotter_link {
    text-decoration: none;
    color: #fff;
    transition: all 0.5s;
}
}
p {
    line-height: 1.7;
    font-weight: 400;
    color: #1a1a1a;
    font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans", "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue", "Segoe UI", Meiryo, sans-serif;
    padding: 30px 0 40px 0;
    text-align: center;
    font-size: 22px;
     @media (max-width: 768px) {
     font-size: 13px !important;
    }
}

</style>
