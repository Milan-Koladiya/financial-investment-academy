<template>
<div class="step">

    <div class="content">
        <img src="../assets/Images/banner/6.png" class="banner" />
        <img src="../assets/Images/step1.png" class="banner" />
        <p>
            本募集ページより当講座のラインに登録し、<br class="brRes">
            まず初めにオリエンテーション講座を受講していただきます。
            <br><br>
            オリエンテーション講座では、<br class="brRes">
            如何にして投資でFIREしていくのか、<br class="brRes">
            安定的に資産を増やす上で重要な投資の考え方等をお伝えしていきます。
        </p>
        <img src="../assets/Images/step2.png" class="banner" />

        <p>
            オリエンテーション講座を受講したら、<br class="brRes">
            次にプレミアライブ講座を予約してください。
            <br><br>
            プレミアライブ講座はオリエンテーション講座のページより予約できます。
            <br><br>
            プレミアライブ講座では、<br class="brRes">『投資だけで本業を超える収入を得るための具体的な手法』についてお伝えします。

        </p>

        <img src="../assets/Images/step3.png" class="banner" />

        <p>
            プレミア講座を受講し終えたら、実際に投資を実践していきます。<br class="brRes">FIREを目指して投資を学びながら資産形成に励んでいきましょう。

        </p>

    </div>
</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.step {
    height: auto;
    background: #f2f2f2;
    background-image: url(../assets/Images/bg.png) !important;
    background-position: top;
    background-repeat: no-repeat;
    margin: auto;

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
                margin-top: -8px;
                margin-bottom: 13px;
            }
        }
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
    @media (max-width: 790px) {
        font-size: 28px;
    }

    @media (max-width: 576px) {
        font-size: 22px;
    }

    @media (max-width: 425px) {
        font-size: 21px;
    }
    .brRes {
        @media (max-width: 768px) {
            content: "";   
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

    @media (max-width: 768px) {
        max-width: 100%;
    }
}
</style>
