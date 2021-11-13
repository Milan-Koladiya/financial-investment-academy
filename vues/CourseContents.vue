<template>
  <div class="CourseContents">
    <div
      class="intro"
      :style="{ 'background-image': 'url(../assets/Images/bg2.png)' }"
    >
      <div class="content">
        <img src="../assets/Images/banner/contents.png" class="banner" />
        <img src="images/banner/contents.png" class="banner" />

        <div class="content-list">
          <ul>
            <li>リスクを最小限に抑え、高いリターンを積み上げる安定投資法</li>
            <li>投資だけで生きる！新時代の人生設計「FIRE」の実態について</li>
            <li>歴25年の投資家が実践する“負けない投資手法”とは！？</li>
            <li>15年間ずっと勝ち続けている「テクノロジー × 〇〇投資」の話</li>
            <li>初心者でも簡単！年60%のリターンを出した投資の方程式とは？</li>
            <li>コロナショックでも資産を減らさなかった戦略とエビデンス</li>
            <li>真のプロ投資家がポートフォリオに〇〇を組み入れる本当の理由</li>
            <li>大暴落相場でリスクを確実に回避し、逆に資産を積み重ねる方法</li>
            <li>1年で資産を3倍にまで増やした資産管理の考え方と実践の手引</li>
            <li>8割の投資初心者が陥りやすい「落とし穴」と「抜け出し方」</li>
            <li>3.5万円から始めて、8年と2ヶ月でFIREを達成するまでの道のり</li>
            <li>労働収入“だけ”得る日本人、投資収入“も”得る欧米人の老後比較</li>
            <li>経済的自立FIREを実現するために必要なルーティンとその効果</li>
            <li>金融リテラシーの違いが人生全体の資産額に大きく影響する理由</li>
            <li>最も効率よくリターンを追求する投資のメソッドと科学的根拠</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.CourseContents {
  font-size: 22px;
  margin: 0;
  padding: 0;
  font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans",
    "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue",
    "Segoe UI", Meiryo, sans-serif;
  .intro {
    height: auto;
    background: #f2f2f2;
    background-image: url(../assets/Images/bg2.png) !important;
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
      .banner {
        margin-top: 50px;
        @media (max-width: 768px) {
          margin-top: 3px;
        }
      }
      .content-list ul {
        border: solid 5px #000066;
        background: #fff;
        padding: 0 0.5em;
        position: relative;
        font-weight: 900;
        @media (max-width: 768px) {
          margin-top: 13px;
        }
      }
      .content-list ul li {
        line-height: 1.5;
        padding: 0.5em 0 0.5em 1.4em;
        border-bottom: dashed 1px silver;
        list-style-type: none !important;
      }
      .content-list ul li:before {
        font-family: "Font Awesome 5 Free";
        content: "\f138";
        position: absolute;
        left: 0.5em;
        color: #000066;
        font-weight: 900;
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
  font-family: "游ゴシック体", "Yu Gothic", YuGothic, "Hiragino Sans",
    "ヒラギノ角ゴ ProN", apple-system, BlinkMacSystemFont, "Helvetica Neue",
    "Segoe UI", Meiryo, sans-serif;
  padding: 30px 0 40px 0;
  text-align: center;
  font-size: 22px;
}
</style>
