<template>
  <div class="access-wrapper">
    <img src="~@/assets/title_big_access.gif" />
    <div class="access-container">
      <div class="access-container-left">
        <p style="font-weight: bold">
          〒671-1502<br />
          揖保郡太子町原白毛山921<br />
          TEL&nbsp;079-277-1872<br />
          FAX 079-287-9216
        </p>
        <p class="sub-text">
          ・神姫バス：龍野行「北山」下車&nbsp;&nbsp;徒歩15分<br />
          ・姫路バイパス西行「太子東ランプ」下りる<br />
          ・2つ目の信号（原）左折<br />
          ・新幹線の高架をくぐってすぐ左へ曲がる<br />
          ・昭和瀝青工場脇の新幹線側道を東へのぼる
        </p>
      </div>
      <div class="access-container-right">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d26200.952134605854!2d134.62658!3d34.8281!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3554e162936e5f8b%3A0xdfe35b34dd140eb3!2z44CSNjcxLTE1MDIg5YW15bqr55yM5o-W5L-d6YOh5aSq5a2Q55S65Y6f77yZ77yS77yR!5e0!3m2!1sja!2sjp!4v1615361287928!5m2!1sja!2sjp"
          width="550"
          height="400"
          style="border: 0"
          allowfullscreen=""
          loading="lazy"
        >
        </iframe>
        <a
          href="http://maps.google.co.jp/maps?hl=ja&amp;q=%E5%85%B5%E5%BA%AB%E7%9C%8C%E6%8F%96%E4%BF%9D%E9%83%A1%E5%A4%AA%E5%AD%90%E7%94%BA%E5%8E%9F%EF%BC%99%EF%BC%92%EF%BC%91&amp;ie=UTF8&amp;hq=&amp;hnear=%E5%85%B5%E5%BA%AB%E7%9C%8C%E6%8F%96%E4%BF%9D%E9%83%A1%E5%A4%AA%E5%AD%90%E7%94%BA%E5%8E%9F%EF%BC%99%EF%BC%92%EF%BC%91&amp;z=14&amp;brcurrent=3,0x3554e162936e5f8b:0xdfe35b34dd140eb3,0,0x3554e3dd75f2dd73:0x7ebb5e17a770f4cd&amp;ll=34.8281,134.62658&amp;source=embed"
        >
          大きな地図で見る
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.access-wrapper {
  padding: 0px 30px 30px 30px;
}

.access-container {
  margin-top: 20px;
  margin-bottom: 15%;
  display: flex;
  justify-content: space-between;
}

.access-container-left {
  padding-top: 20px;
}

.access-container-left p {
  margin-top: 20px;
}

.sub-text {
  font-size: 13.6px;
}

.access-container-right a {
  display: block;
  text-align: right;
  margin-top: 20px;
  color: #0099cc;
  text-decoration: underline;
  font-size: 12px;
}

@media screen and (max-width: 480px) {
  .access-wrapper {
    padding: 0px 10px 20px 10px;
  }

  .access-container {
    margin-bottom: 15%;
    display: block;
  }

  .access-container-left {
    padding-top: 0px;
  }

  .access-container-left p {
    font-size: 16px;
    margin-top: 8px;
  }

  .sub-text {
    font-size: 15px;
    margin-bottom: 60px;
  }

  .access-container-right iframe {
    height: 280px;
    width: 100%;
  }

  .access-container-right a {
    display: block;
    text-align: right;
    margin-top: 10px;
    color: #0099cc;
    text-decoration: underline;
    font-size: 14px;
  }
}
</style>
