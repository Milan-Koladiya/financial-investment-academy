<template>
<div class="coursegoal">
    <div class="content">
        <img src="../assets/Images/banner/2.png" class="banner" />
        <p style="text-align: center">

            先進国の中で最も金融知識が乏しい日本で<br class="brRes">
            投資という学問を正しく広めていきたい
            <br><br>
            そして、
            <br><br>
            皆様が投資収益だけで暮らしていく<br class="brRes">
            FIREを実現してくことを本気で目指しています。
        </p>
        <div align="center">
            <img src="../assets/Images/image.png" class="ic2" />
        </div>
    </div>
</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.coursegoal {
    background: #effaff;

    .content {
        width: 100%;
        max-width: 900px;
        margin: 0px auto;
        line-height: 0;
        background: none;
        font-size: 22px;
        padding: 20px 20px 80px 20px;
        background: #effaff;

        @media (max-width: 790px) {
            font-size: 26px;
        }

        @media (max-width: 576px) {
            font-size: 22px;
        }

        @media (max-width: 425px) {
            font-size: 17px;
        }

        @media (max-width: 768px) {
            width: 94%;
        }

        .banner {
            margin-top: 50px;
            margin-bottom: 50px;

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

.brRes {
    @media (max-width: 768px) {
        content: "";   
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
}
</style>
