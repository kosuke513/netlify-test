<template>
  <div>
    <div id="fb-root"></div>
    <script
      async
      defer
      crossorigin="anonymous"
      src="https://connect.facebook.net/ja_JP/sdk.js#xfbml=1&version=v10.0"
      nonce="oV9VJ4sr"
    ></script>
    <div class="top-container">
      <p style="font-weight: bold">
        姫路YMCAは、「太子教育キャンプ場」改め「太子遊びと冒険の森」という名称に変更しました。
      </p>
      <br />
      <p>
        また、より多くの方に親しんでいただけるよう、会員はじめ全国の方々から愛称を募り約150もの愛称候補が集まりました。
      </p>
      <br />
      <p>
        それらの中から選考委員で5つの愛称に選考し、夏のキャンプにてこどもたちに投票をしてもらいました。
      </p>
      <p>
        その結果、愛称は、神奈川県鎌倉市にお住いの友久&nbsp;健さんが送ってくださった「ASOBO」に決まりました！
      </p>
      <br />
      <p>
        皆様、今後とも
        <span style="font-weight: bold">
          「太子遊びと冒険の森&nbsp;&nbsp;ASOBO」
        </span>
        をよろしくお願いします。
      </p>
      <div class="volunteer-leader-link">
        <NuxtLink to="/volunteer">
          ■ボランティアリーダー大募集！<span class="responsive-hide"
            >&nbsp; &nbsp;</span
          ><br class="responsive-show" />詳しくはこちら■
        </NuxtLink>
      </div>
    </div>
    <div class="joining-program-container">
      <img
        src="~@/assets/home_program_banner.jpg"
        class="joining-program-banner"
      />
      <div class="daycamp-container">
        <div class="daycamp-container-left">
          <p class="container-title">
            ■2021年度デイキャンププログラムのご案内
            <span style="font-weight: normal">
              （子ども会など団体でのご利用）
            </span>
          </p>
          <img src="~@/assets/description_button.gif" />
          <p class="big-text">【現地説明会】</p>
          <p style="font-size: 12.8px">
            以下いずれかの日程で、説明会にご参加ください。
          </p>
          <p style="font-size: 12.8px">
            2021年5月8日（土）&nbsp;14：00～15：30
          </p>
          <p style="font-size: 12.8px">
            2021年6月5日（土）&nbsp;14：00～15：30
          </p>
          <div class="pamphlet-container">
            <div class="pamphlet-container-left">
              <img class="pamphlet-img" src="~@/assets/daycamp_chirashi1.jpg" />
              <br />
              <a href="/2021day_1.pdf" style="font-size: 16px">
                ご案内チラシ
              </a>
              <span>(pdfファイル)</span>
            </div>
            <div class="pamphlet-container-right">
              <img class="pamphlet-img" src="~@/assets/daycamp_chirashi2.jpg" />
              <br />
              <a href="/2021day_2.pdf" style="font-size: 16px">
                ご案内チラシ
              </a>
              <span>(pdfファイル)</span>
            </div>
          </div>
          <div class="pamphlet-container">
            <div class="pamphlet-container-left">
              <img src="~@/assets/asobo_map.jpg" style="width: 286px" />
            </div>
            <div class="pamphlet-container-right">
              <img src="~@/assets/title_daycamp.gif" style="margin-top: 50px" />
              <NuxtLink to="/daycamp">
                <img
                  src="~@/assets/description_button.gif"
                  style="margin-left: 30px"
                />
              </NuxtLink>
            </div>
          </div>
        </div>
        <div class="daycamp-container-right">
          <p class="container-title">
            2021年2月22日（月）10時より <br />
            お申し込み受付中
          </p>
          <a
            href="https://docs.google.com/forms/d/e/1FAIpQLSffPbB2KA61UBsANFJPYdVbKcMN7xZChbaqyseMf-nrUH2NSQ/viewform"
          >
            <img class="asobo-form" src="~@/assets/asobo_form.gif" />
          </a>
          <a class="asobo-reserve">
            <p>予約可能人数の確認はコチラ</p>
            <img src="~@/assets/daycamp_calender.gif" />
          </a>
          <div class="asobo-reserve-text">
            <p style="color: red">
              上記カレンダーリンク先よりデイキャンプ
              <span style="font-weight: bold">予約可能人数をご確認</span>
              のうえ、
              <br />
              お申し込みフォームにご記入ください。
            </p>
            <p>
              ※更新の時間差により、ご希望の日程に添えない場合がありますので
              <span style="color: red">第2希望、第3希望日</span>
              をご記入下さい
            </p>
          </div>
          <div class="asobo-reserve-table">
            <div class="asobo-reserve-table-header">
              <p>
                デイキャンプお申し込み後、
                <br />
                関係書類等を郵送します。
              </p>
              <br />
              <p style="font-size: 13.6px; line-height: 13.6px">
                書類到着後、下記のファイルをダウンロードし、メール添付にてご送信をお願い致します。
              </p>
              <p
                style="
                  font-size: 13.6px;
                  font-weight: bold;
                  padding-bottom: 2px;
                "
              >
                送信先メールアドレス
              </p>
              <p style="font-weight: bold; line-height: 18px">
                ■
                <a href="mailto:yoyakuyagai@himejiymca.org"
                  >yoyakuyagai@himejiymca.org</a
                >
              </p>
            </div>
            <div class="asobo-reserve-table-row">
              <p class="asobo-row-title">■プログラム申込書</p>
              <p class="asobo-row-link">
                （
                <a href="/2021form.xls" download="2021_YMCA_form.xls"
                  >エクセルファイルダウンロード</a
                >
                ）
              </p>
            </div>
            <div class="asobo-reserve-table-row">
              <p class="asobo-row-title">■参加者名簿</p>
              <p class="asobo-row-link">
                （
                <a href="/2021list.xls" download="2021_YMCA_list.xls"
                  >エクセルファイルダウンロード</a
                >
                ）
              </p>
            </div>
            <div class="asobo-reserve-table-row">
              <p class="asobo-row-title">■キャンセル・追加連絡票</p>
              <p class="asobo-row-link">
                （
                <a href="/2021cancel.xls" download="2021_YMCA_cancel.xls"
                  >エクセルファイルダウンロード</a
                >
                ）
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="spring-container">
        <div class="spring-container-left">
          <p class="container-title">■2020年度&nbsp;&nbsp;春のプログラム</p>
          <div class="spring-container-items">
            <div class="spring-container-texts">
              <p style="font-weight: bold">
                スプリングデイキャンプ（日帰り2日間）
              </p>
              <p style="font-weight: bold">
                2021年3月20日（土・休）・21日（日）
                <span style="font-weight: normal">2日間</span>
              </p>
              <p style="font-size: 12.8px">
                対象：幼児（年中）〜小学6年生&nbsp;&nbsp;20名
                <br />
                費用：
                <br />
                ・参加費12,100円（消費税込）
                <br />
                ・YMCA臨時会費1,100円&nbsp;&nbsp;※2020年度YMCA会員の方は不要
                <br />
                内容：
                <br />
                「ASOBOの原始人になってけもの狩りに挑戦！！」
                <br />
                すみかづくり、火おこし器での火おこし、けもの狩りの道具（弓矢など）、けもの狩り、原始人のおやつづくりなど
                <br />
                場所：YMCA太子遊びと冒険の森ASOBO
              </p>
            </div>
            <div class="spring-container-image">
              <a href="~@/assets/2021_haru.pdf">
                <img src="~@/assets/2021_spring_program.gif" />
                <p>詳細ちらしPDF</p>
              </a>
            </div>
          </div>
        </div>
        <div class="spring-container-right">
          <a
            href="https://docs.google.com/forms/d/e/1FAIpQLSf2Si0KHXD9qV0_ZvrHastOHdzMpHTmD8Za97WBPHLlNVDUqg/viewform?gxids=7628"
          >
            <img src="~@/assets/spring_form.gif" />
          </a>
        </div>
      </div>
      <div class="activity-container">
        <div class="activity-container-left">
          <p class="container-title">
            ■野外活動の楽しさを体験しよう＼(^o^)／
            <br />
            <span style="font-size: 12.8px; font-weight: normal">
              ※野外活動クラブは、年間登録前に1回限り、月々の参加日のみでの体験参加が可能です。
            </span>
          </p>
          <p class="activity-left-notation">
            ※詳しくは、右のチラシの左側中段をご覧下さい。
          </p>
          <a class="activity-reserve-button">
            野外活動体験
            <span style="font-weight: bold">■お申し込みは&nbsp;こちら！</span>
          </a>
          <hr style="margin-bottom: 16px" />
          <p class="container-title">
            ■2020年度&nbsp;&nbsp;野外活動クラブ&nbsp;&nbsp;（月1回、年間登録制）
          </p>
          <div class="activity-form-container">
            <div class="activity-form-container-left">
              <p>■2020年度</p>
              <p style="font-weight: bold">
                詳しくは、右のチラシをご覧下さい。
              </p>
            </div>
            <div class="activity-form-container-right">
              <img src="~@/assets/activity_form.gif" />
            </div>
          </div>
        </div>
        <div class="activity-container-right">
          <a
            href="https://docs.google.com/forms/d/e/1FAIpQLSf2WexRfIUJeHMc2RtC88NrDFmFYwwR08Itra0w6GMEtaHjjA/viewform"
          >
            <img
              class="activity-right-pamphlet"
              src="~@/assets/activity_chirash.jpg"
            />
            <p style="font-weight: bold">案内ちらしダウンロード</p>
          </a>
          <img
            class="activity-right-title"
            src="~@/assets/title_activity.gif"
          />
          <NuxtLink to="/camp">
            <img
              class="activity-right-button"
              src="~@/assets/description_button.gif"
            />
          </NuxtLink>
        </div>
      </div>
      <div
        class="fb-page"
        data-href="https://www.facebook.com/himejiymca/"
        data-tabs="timeline"
        data-width="400"
        data-height="500"
        data-small-header="false"
        data-adapt-container-width="true"
        data-hide-cover="false"
        data-show-facepile="true"
      >
        <blockquote
          cite="https://www.facebook.com/himejiymca/"
          class="fb-xfbml-parse-ignore"
        >
          <a href="https://www.facebook.com/himejiymca/">姫路YMCA</a>
        </blockquote>
      </div>
    </div>
    <div class="about-container">
      <p style="font-weight: bold">
        姫路YMCAは、財団法人からNPO法人へ組織変更となり、太子キャンプ場に事務所を移転し【青少年活動】をしています。
      </p>
      <p>・キリスト教精神を基盤とする団体です。</p>
      <p>
        ・ボランティアとスタッフの協働により、団体運営・プログラム運営がなされています。
      </p>
      <p>
        ・非営利公益団体として地域のニーズに即したプログラムを提供しています。
      </p>
      <p>
        ・青少年はもとより、あらゆる年代、性別、宗教の人びとがかかわっています。
      </p>
      <p>・120を超える国と地域にひろがる国際団体です。</p>
    </div>
    <div class="banner-container">
      <a href="https://www.ymcajapan.org/">
        <img src="~@/assets/ymca_association.gif" />
      </a>
      <a href="https://www.ymcajapan.org/campaign/camp100th/">
        <img src="~@/assets/ymca_story.jpg" />
      </a>
      <a href="/leader.docx" download="leader.docx">
        <img src="~@/assets/volunteer_leader_recruitment.jpg" />
      </a>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.top-container {
  padding-left: 65px;
  color: red;
  font-size: 14.4px;
}

.volunteer-leader-link {
  background-color: #ffcc66;
  text-align: center;
  margin: 35px auto;
  width: 400px;
}

.volunteer-leader-link a {
  display: inline-block;
  background-color: #ffcc66;
  font-size: 16px;
  font-weight: bold;
  padding: 5px;
  margin: 5px;
}

.joining-program-container {
  margin: 20px;
}

.joining-program-banner {
  margin-bottom: 30px;
}

.container-title {
  color: red;
  font-weight: bold;
  font-size: 16px;
  margin-bottom: 20px;
}

.daycamp-container {
  display: flex;
  border: solid #87c8d1 2px;
  margin-bottom: 40px;
}

.daycamp-container-left {
  border-right: solid #87c8d1 2px;
  width: 610px;
  padding: 7px;
}

.big-text {
  font-size: 24px;
  font-weight: bold;
  margin-top: 20px;
}

.joining-program-container {
  font-size: 14.4px;
}

.pamphlet-container {
  margin-top: 20px;
  display: flex;
}

.pamphlet-container-left {
  padding-right: 20px;
  padding-bottom: 30px;
}

.pamphlet-img {
  border: #0099cc 1px solid;
  margin-bottom: 20px;
}

.daycamp-container-right {
  width: 296px;
  text-align: center;
}

.daycamp-container-right a {
  color: #0099cc;
  text-decoration: #0099cc;
  text-decoration-line: underline;
}

.daycamp-container-right .container-title {
  margin-top: 20px;
  margin-bottom: 20px;
}

.asobo-form {
  display: block;
  margin: 0px 10px 20px 10px;
}

.asobo-reserve {
  cursor: pointer;
  font-weight: bold;
  margin: 0 auto;
}

.asobo-reserve img {
  border: 1px #0099cc solid;
}

.asobo-reserve-text {
  margin: 20px 15px;
  font-size: 12.8px;
  text-align: left;
}

.asobo-reserve-table {
  text-align: left;
  border: salmon 1px solid;
  margin: 15px 15px 65px 15px;
}

.asobo-reserve-table p {
  line-height: 14.4px;
}

.asobo-reserve-table-header {
  color: #666666;
  padding: 20px 5px;
  background-color: #ffeaea;
}

.asobo-reserve-table-row {
  background-color: #ffffff;
  border-top: salmon 1px solid;
  padding: 5px;
  font-size: 12.8px;
}

.asobo-row-title {
  color: red;
  font-weight: bold;
}

.spring-container {
  display: flex;
  border: solid #87c8d1 2px;
  margin-bottom: 40px;
}
.spring-container-left {
  border-right: solid #87c8d1 2px;
  width: 610px;
  padding: 7px;
}

.spring-container-texts {
  width: 382px;
  margin-right: 50px;
}

.spring-container-items {
  display: flex;
  margin-bottom: 40px;
}

.spring-container-image img {
  border: #0099cc 1px solid;
}

.spring-container-image a {
  cursor: pointer;
  color: #0099cc;
  text-decoration: #0099cc;
  text-decoration-line: underline;
  font-size: 12px;
}

.spring-container-right {
  width: 296px;
  text-align: center;
}

.spring-container-right img {
  margin-top: 30px;
  width: 280px;
}

.activity-container {
  display: flex;
  border: solid #87c8d1 2px;
  margin-bottom: 40px;
}

.activity-container-left {
  border-right: solid #87c8d1 2px;
  width: 610px;
  padding: 7px;
}

.activity-left-notation {
  font-weight: bold;
  color: #666666;
  margin: 10px 0px 40px 30px;
  font-size: 12.8px;
}

.activity-reserve-button {
  background-color: #ffcccc;
  margin-left: 40px;
  margin-bottom: 80px;
  padding: 8px;
  font-size: 12.8px;
  border: 2px solid red;
  display: inline-block;
}

.activity-form-container {
  display: flex;
}

.activity-form-container-left p {
  font-size: 12.8px;
  margin-left: 16px;
}

.activity-form-container-right img {
  width: 250px;
  margin-left: 16px;
}

.activity-container-right {
  text-align: center;
}

.activity-right-pamphlet {
  margin-top: 10px;
  border: 1px #0099cc solid;
}

.activity-right-title {
  margin-top: 40px;
  width: 160px;
}

.activity-right-button {
  width: 160px;
  margin-bottom: 10px;
}

.fb-page {
  position: relative;
  margin-top: 30px;
  margin-bottom: 30px;
  left: 50%;
}

.about-container {
  color: #666666;
  font-size: 11.4px;
  margin-left: 16px;
  margin-bottom: 30px;
  line-height: 20px;
}

.banner-container {
  margin-left: 16px;
  margin-bottom: 30px;
}

.banner-container img {
  margin-right: 30px;
}

.responsive-show {
  display: none;
}

@media screen and (max-width: 480px) {
  .top-container {
    padding: 0px 10px;
    font-size: 16px;
  }

  .volunteer-leader-link {
    background-color: #ffcc66;
    text-align: center;
    margin: 35px auto;
    width: 100%;
  }

  .joining-program-container {
    margin: 20px;
  }

  .joining-program-banner {
    width: 120%;
    margin-bottom: 30px;
  }

  .container-title {
    font-weight: bold;
    font-size: 18px;
  }

  .daycamp-container {
    width: 100%;
    display: block;
    text-align: center;
    margin-bottom: 40px;
  }

  .daycamp-container-left {
    border-right: none;
    width: 100%;
  }

  .joining-program-container {
    font-size: 16px;
  }

  .pamphlet-container {
    margin-top: 20px;
    display: block;
  }

  .pamphlet-container-left {
    padding-right: 0px;
    padding-bottom: 0px;
  }

  .pamphlet-img {
    margin-bottom: 20px;
  }

  .daycamp-container-right {
    width: 100%;
    text-align: center;
  }

  .asobo-form {
    display: block;
    text-align: center;
    margin: 0px auto 20px auto;
  }

  .asobo-reserve {
    cursor: pointer;
    font-weight: bold;
    margin: 0 auto;
  }

  .asobo-reserve img {
    border: 1px #0099cc solid;
  }

  .asobo-reserve-text {
    font-size: 14px;
  }

  .asobo-reserve-table p {
    line-height: 15px;
    line-height: 24px;
  }

  .asobo-reserve-table-row {
    font-size: 14px;
  }

  .spring-container {
    display: block;
  }

  .spring-container-left {
    border-right: none;
    width: 100%;
  }

  .spring-container-texts {
    width: 96%;
    margin: 0 auto;
  }

  .spring-container-items {
    display: block;
    margin-bottom: 0px;
  }

  .spring-container-image {
    margin-top: 20px;
    text-align: center;
  }

  .spring-container-image img {
    width: 75%;
  }

  .spring-container-image a {
    text-align: center;
    font-size: 16px;
  }

  .spring-container-right {
    width: 100%;
    text-align: center;
    margin-bottom: 20px;
  }

  .activity-container {
    display: block;
  }

  .activity-container-left {
    border-right: none;
    width: 100%;
    padding: 7px;
  }

  .activity-left-notation {
    margin: 10px auto 20px auto;
    font-size: 13px;
  }

  .activity-reserve-button {
    margin: 0 15px 40px 15px;
    text-align: center;
    font-size: 14px;
    display: block;
  }

  .activity-form-container {
    display: block;
  }

  .activity-form-container-left p {
    font-size: 14px;
    margin-left: 16px;
  }

  .activity-form-container-right img {
    width: 250px;
    margin-top: 10px;
    margin-left: 32px;
  }

  .activity-right-pamphlet {
    margin-top: 10px;
  }

  .activity-right-title {
    display: block;
    width: 60%;
    margin: 40px 20% 5px 20%;
  }

  .activity-right-button {
    width: 190px;
    margin-bottom: 30px;
  }

  .fb-page {
    left: 0%;
  }

  .about-container {
    color: #666666;
    font-size: 14px;
    margin: 30px 12px;
    line-height: 28px;
  }

  .banner-container {
    text-align: center;
    margin-left: 0px;
    margin-bottom: 30px;
  }

  .banner-container img {
    width: 75%;
    margin-right: 0px;
    margin-bottom: 20px;
  }

  .responsive-show {
    display: block;
  }

  .responsive-hide {
    display: none;
  }
}
</style>
