<template>
  <div class="volunteer_wrapper">
    <img class="volunteer_title" src="~@/assets/title_big_volunteer.gif" />
    <p class="introduction-text">
      YMCAとは、現在120を越える国と地域で活動している世界最大の青少年団体です。<br />
      精神・知性・身体の均整のとれた成長をめざし、生涯教育の視点から、幼児教育・健康教育・進学教育・語学教育などに取りくんでいます。<br />
      また、ともに生きる社会の実現をめざして国際協力活動やボランティア活動を推進しています。
    </p>
    <div class="recruit-container">
      <div class="recruit-container-left">
        <p class="recruit-text-gray">
          ボランティアリーダーを大募集しています！<br />
          詳しくは
          <span>チラシをクリック</span>
        </p>
        <p class="recruit-text-red">
          現在、新型コロナウイルス感染防止緊急事態宣言の発令により、<br />
          日程・場所・時間が変更となりました。<br />
          下記の日程で<span>ZOOMによるインターネットで実施</span>しています。
        </p>
        <p class="recruit-text-red">
          <span>6/1(月)&nbsp;&nbsp;6/9(火)&nbsp;&nbsp;<s>6/18(木)</s></span>
          （中止）<br />
          6月の説明会開始時間は<span>19:00～19:40</span>
          に変更しています。
        </p>
      </div>
      <div class="recruit-container-right">
        <a href="2020_recruit_leader1.pdf">
          <img src="~@/assets/volunteer_recruit_1.jpg" />
        </a>
        <a href="/2020_recruit_leader2.pdf">
          <img src="~@/assets/volunteer_recruit_2.jpg" />
        </a>
      </div>
    </div>
    <table>
      <tr>
        <td style="font-weight: bold; width: 16%">野外活動リーダー</td>
        <td style="width: 45%">
          幼児年中から高校生の子どもたちと野外活動（近郊の場所でのデイキャンプや太子教育キャンプ場でのキャンプ）を企画・実施して、子どもたちとともに成長していきます。
        </td>
        <td style="width: 20%">
          <span style="font-weight: bold">活動日</span>
          ：定例活動&nbsp;&nbsp;月&nbsp;1回日曜&nbsp;&nbsp;他<br />
          長期休暇&nbsp;&nbsp;特別キャンプ
        </td>
      </tr>
      <tr>
        <td style="font-weight: bold">発達障害サポートリーダー</td>
        <td>
          発達障害およびその周辺の子どもたち（小学～高校）のコミュニケーションやソーシャルスキルの向上をめざし、太子教育キャンプ場で野外活動をとおしてサポートしています。
        </td>
        <td style="text-align: center">同&nbsp;&nbsp;上</td>
      </tr>
    </table>
  </div>
</template>

<style scoped>
.volunteer_wrapper {
  padding: 0px 25px;
  font-size: 14.4px;
}

.volunteer_title {
  margin-bottom: 20px;
}

.introduction-text {
  line-height: 28px;
  margin-bottom: 60px;
}

.recruit-container {
  display: flex;
}

span {
  font-weight: bold;
}

.recruit-text-gray {
  margin-bottom: 20px;
}

.recruit-text-red {
  color: red;
  margin-bottom: 20px;
}

.recruit-container {
  margin-bottom: 30px;
}

.recruit-container-left {
  margin-right: 5px;
}

.recruit-container-right img {
  cursor: pointer;
  margin-right: 30px;
  border: solid #0099cc 1px;
}

table {
  font-size: 12.8px;
  border-collapse: collapse;
  margin-bottom: 70px;
}

td {
  padding: 5px;
  line-height: 24px;
  border: solid #c5d2de 1px;
  vertical-align: top;
}

@media screen and (max-width: 480px) {
  .volunteer_wrapper {
    padding: 0px 10px;
    font-size: 16px;
  }

  .volunteer_title {
    width: 300px;
    margin-bottom: 20px;
  }

  .introduction-text {
    line-height: 32px;
    margin-bottom: 60px;
  }

  .recruit-container {
    display: block;
  }

  .recruit-container-right {
    text-align: center;
  }

  .recruit-container-right img {
    margin-bottom: 30px;
    width: 80%;
  }

  table {
    font-size: 14px;
  }

  td {
    line-height: 24px;
  }
}
</style>
