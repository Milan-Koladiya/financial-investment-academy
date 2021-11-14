<template>
<div class="CourseOutline">
    <div class="content">
        <img src="../assets/Images/banner/3.png" class="banner" />
        <p style="text-align: center">
            シンプルで簡単、だけど誰も教えてくれない<br class="brRes">
            安定した資産を築くための<br class="brRes">
            投資について分かりやすく解説します。
        </p>
        <div align="center">
            <img src="../assets/Images/hikaku.png" class="ic2" />
        </div>
        <p style="text-align: center">
            20年以上、相場を研究し続けた現役投資家が<br class="brRes">
            徹底的にリスクを抑えた投資手法を公開します
        </p>
    </div>
</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.CourseOutline {
    font-size: 22px;
    margin: 0;
    padding: 0;
    background: #effaff;
    font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans", "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue", "Segoe UI", Meiryo, sans-serif;

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
                margin-bottom: 9px;
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

img {
    max-width: 100%;
    height: auto;
    user-select: none;
    -moz-user-select: none;
    -webkit-user-select: none;
    -ms-user-select: none;
}

p {
    line-height: 1.7;
    font-weight: 400;
    color: #1a1a1a;
    font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans", "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue", "Segoe UI", Meiryo, sans-serif;
    padding: 30px 0 40px 0;
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
</style>
