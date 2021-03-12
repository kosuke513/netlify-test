<template>
  <div>
    <CampIndex></CampIndex>
    <img class="outdoor-banner" src="~@/assets/title_big_outdoor.gif" />
    <div class="outdoor-container">
      <div class="outdoor-container-left">
        <div class="outdoor-introduction-text">
          <p>親子が共に協力して様々な野外活動に取り組んでいきます</p>
          <p>
            親子の絆を深めると共に、他の家族と親睦を深め、環境教育も考えていきます
          </p>
        </div>
        <div class="outdoor-left-texts">
          <ul>
            <li>
              家族のプログラムです。<br />
              おじいちゃん、おばあちゃんの参加もOKです。<br />
              <br />
            </li>
            <li>
              参加ご希望の方は、トップページのお申し込みフォームから、<br />
              必要事項をご記入の上、お申し込みください。<br />
              <a>domein of this homepage</a><br />
              <br />
            </li>
          </ul>
        </div>
        <img src="~@/assets/outdoor_introduce_images.jpg" />
      </div>
      <div class="outdoor-container-right">
        <p class="outdoor-right-title">2020年度</p>
        <p style="font-weight: bold">※プログラムは変更になる場合もあります</p>
        <table>
          <tr>
            <td>4/29（水・祝）</td>
            <td>たけのこ堀り</td>
          </tr>
          <tr>
            <td>
              6/7（日）、<br />
              6/27（土）
            </td>
            <td>流しそうめん</td>
          </tr>
          <tr>
            <td>8/30（日）</td>
            <td>ペットボトルロケットで遊ぼう！</td>
          </tr>
          <tr>
            <td>9/6（日）</td>
            <td>ジビエ料理に挑戦しよう！</td>
          </tr>
          <tr>
            <td>11/29（日）</td>
            <td>クリスマスリースを作ろう！</td>
          </tr>
          <tr>
            <td>1/10（日）</td>
            <td>お餅つきを楽しもう！</td>
          </tr>
        </table>
        <div class="outdoor-right-texts">
          <p style="font-weight: bold">●集合・解散場所</p>
          <p>YMCA太子遊びと冒険の森&nbsp;ASOBO</p>
          <p style="font-weight: bold">●活動場所</p>
          <p>YMCA太子遊びと冒険の森&nbsp;ASOBO</p>
        </div>
        <CampJampTop></CampJampTop>
      </div>
    </div>
  </div>
</template>

<style scoped>
.outdoor-banner {
  margin-top: 10px;
  margin-left: 20px;
}

.outdoor-container {
  display: flex;
  color: #666666;
  padding: 10px;
}

.outdoor-container-left {
  width: 520px;
  margin-right: 20px;
}

.outdoor-container-left img {
  width: 450px;
}

.outdoor-introduction-text {
  margin-left: 20px;
  margin-bottom: 20px;
  font-size: 12.8px;
}

.outdoor-left-texts {
  margin-left: 16px;
  font-size: 13.6px;
  line-height: 24px;
}

.outdoor-container-right {
  font-size: 12.8px;
}

.outdoor-right-title {
  margin-top: 16px;
  font-size: 16px;
  line-height: 28px;
  font-weight: bold;
}

.outdoor-right-texts {
  margin-top: 20px;
  font-size: 13.6px;
  margin-bottom: 270px;
}

table {
  border: solid 1px #c8dddd;
  border-collapse: collapse;
  width: 345px;
}

td {
  font-weight: bold;
  padding: 8px 6px;
}

td {
  border: solid 1px #c8dddd;
  border-collapse: collapse;
}

@media screen and (max-width: 480px) {
  .outdoor-banner {
    width: 95%;
    margin-top: 0px;
    margin-bottom: 20px;
    margin-left: 0px;
  }

  .outdoor-container {
    display: block;
    padding: 10px;
  }

  .outdoor-container-left {
    width: 100%;
    margin-right: 20px;
  }

  .outdoor-container-left img {
    width: 100%;
  }

  .outdoor-introduction-text {
    margin-left: 0px;
    margin-bottom: 20px;
    font-size: 15px;
    line-height: 28px;
  }

  .outdoor-left-texts {
    margin-left: 0px;
    font-size: 14px;
    line-height: 28px;
  }

  li {
    line-height: 24px;
  }

  .outdoor-container-right {
    font-size: 14px;
  }

  .outdoor-right-title {
    margin-top: 60px;
    font-size: 18px;
    line-height: 28px;
    font-weight: bold;
  }

  .outdoor-right-texts {
    font-size: 15px;
    margin-bottom: 40px;
  }
}
</style>
