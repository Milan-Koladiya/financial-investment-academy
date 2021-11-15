<template>
<div class="bg_gr">
    <div class="content">
        <img src="../assets/Images/banner/9.png" class="banner" />

        <div class="boxQA">
            <div class="box-title">初心者からでも始められますか？</div>
            <p>はい、可能です。本講座を受講することによって安定した資産形成の手法をゼロから１０まで学ぶことができます。</p>
        </div>

        <div class="boxQA">
            <div class="box-title">会社勤めをしているのですが時間的にはそれでも可能ですか？</div>
            <p>はい、可能です。ライフスタイルに合わせて時間をかける方法も、なるべく時間をかけない方法も両方ありますので、ご安心ください。</p>
        </div>

        <div class="boxQA">
            <div class="box-title">自己資金が少なくても始められますか？</div>
            <p>投資自体は数万円程度から始められます。受講生の中にも数万円から始めて、本業と同じくらいの収入を得ている実績者がいます。</p>
        </div>

        <div class="boxQA">
            <div class="box-title">なぜ無料なのですか？</div>
            <p>当アカデミーでは、日本全体の金融リテラシーを高め、お客様が豊かな生活を送れるようになることをビジョンとしています。それを実現させるための一環として、当講座を提供しています。</p>
        </div>

        <div class="boxQA">
            <div class="box-title">リスクがありますか？</div>
            <p>リスクはあります。リスクがない投資はこの世に存在しません。ですが、リスクを限りなく抑えた投資は存在します。当アカデミーではリスクを徹底的に抑えた安定資産の築き方をお伝えします。</p>
        </div>

        <div class="boxQA">
            <div class="box-title">どうすれば講座で学べますか？何をすれば良いですか？</div>
            <p>本募集ページの「お申し込み」ボタンを押して、まずはオリエンテーション講座をご覧ください。</p>
        </div>

    </div>
</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.bg_gr {

    background: #e0fce3;
    margin: auto;

    .content {
        width: 100%;
        max-width: 900px;
        margin: 0px auto;
        line-height: 0;
        background: none;
        padding: 20px 10px 80px 10px;

        @media (max-width: 768px) {
            max-width: 94% !important;
            padding: 20px 20px 60px 20px;
        }

        .banner {
            margin-top: 50px;
            margin-bottom: 50px;

            @media (max-width: 768px) {
                margin-bottom: 0px;
            }
        }

        .boxQA {
            position: relative;
            margin: 2em 0;
            padding: 20px;
            background: #EDF1F5;
            border-radius: 20px;
        }

        .boxQA .box-title {
            position: relative;
            background: #fff;
            padding: 40px;
            color: #39b54a;
            font-weight: 700;
            border-radius: 20px;
            line-height: 1.5;
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

        .boxQA .box-title:before {
            content: "Q";
            display: inline-block;
            line-height: 40px;
            position: absolute;
            padding: 0em;
            color: white;
            background: #39b54a;
            font-weight: bold;
            width: 45px;
            text-align: center;
            height: 45px;
            line-height: 33px;
            left: -0.5em;
            top: 20px;
            -moz-transform: translateY(-50%);
            -webkit-transform: translateY(-50%);
            -ms-transform: translateY(-50%);
            transform: translateY(-50%);
            border: solid 3px white;
            border-radius: 50%;
            font-size: 25px;
        }

        .boxQA .box-title:after {
            content: "A";
            display: inline-block;
            line-height: 40px;
            position: absolute;
            padding: 0em;
            color: white;
            background: #ffcc00;
            font-weight: bold;
            width: 45px;
            text-align: center;
            height: 45px;
            line-height: 33px;
            left: -0.5em;
            bottom: -80px;
            -moz-transform: translateY(-50%);
            -webkit-transform: translateY(-50%);
            -ms-transform: translateY(-50%);
            transform: translateY(-50%);
            border: solid 3px white;
            border-radius: 50%;
            font-size: 25px;
        }

        .boxQA p {
            padding: 40px;
            margin: 0;
            text-align: left;
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
        font-size: 17px;
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
}
</style>
